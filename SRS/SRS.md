## SRS ViveBus application.
<p align="center">
Universidad Autónoma de Ciudad Juárez</br>
División Multidisciplinaria de Ciudad Universitaria</br>
Departamento de Ingeniería Electricidad y Computación</br>
</p>
<br>
<p align="center">
<img width="270" height="270" 
  src="http://www.uacj.mx/comunicacion/PublishingImages/Escudo%20UACJ%202015/Escudo%20uacj%202015-color-sin%20fondo.png">
</p>
<br>
<p align="right">
Development of software requirements</br>
</br>
ViveBus application</br>
</br>
César Antonio Cano Reyna</br>

</br>

</br>
May 2019
</p>

# Table of contents
1. [Introduction](#Introduction)
    - [Purpose](#Purpose)
    - [Scope](#Scope)
    - [Definitions, acronyms, and abbreviations](#Definitions-acronyms-and-abbreviations)
    - [References](#References)
    - [Overview](#Overview)

2. [Overrall description](#Overall-description)
    - [Product perspective](#Product-perspective)
       - [Product Functions](#Product-functions) 
    - [User characteristics](#User-characteristics)
    - [constraints](#constraints)
    - [Assumptions and dependencies](#Assumptions-and-dependencies)
3. [Specific requirements](#Specific-requirements) 
    - [Interface](#Interface)
    - [Requirements](#requirements)
       - [Functional requirements](#Functional-requirements)
       - [Non-Functional requirements](#Non-Functional-requirements) 
3. [Appendices](#Appendices) 
   - [Elicitation process](#Elicitation-process)
   - [Business Managment Process](#Business-Managment-Process) 









## Introduction
### Purpose: 
* The purpose of this SRS is to provide the specifications of the application for Vivebus mobile devices, which will provide a better service to all people who approach this public transport and have a smart phone. The main objective is to inform the operation of the application not only to passengers, but also to anyone interested in boarding this transport.


Return to the [table of contents](#Table-of-contents).

### Scope: 
* The name of the finish product it will be “ViveBus App”. 
* The application should promote the benefits offered by the ViveBus application and offer a simple way to travel and get to know each of the stations picked up throughout the city.
* In addition, new stops can be created in which every passenger of the vivebus descends.
* The application will not be responsible for total theft or loss of smartphones.
* The benefits of this application is that those interested have an easier way to find information about the stations, as well as to choose which station they go to, their main objective is to facilitate the way of traveling around the city.


Return to the [table of contents](#Table-of-contents).
### Definitions, acronyms, and abbreviations
Terms | Definition
----- | -------------
ViveBus | Bus Rapid Transit.
App | The term app is an abbreviation of the English voice application and tends to be used to refer to a computer application for mobile devices and tablets.
UML | Unified Modeling language 
Mercedes Benz | German company luxury vehicle manufacturer
Stakeholder | Any person with an interest in the project.
Public transport | Public transport includes the means of transport in which passengers are not the owners of the same, being served by third parties (public or private companies). Public transport helps the movement of people from one point to another in an area of a city, each person paying a set fee depending on their route.
GPS | The GPS is a navigation system based on 24 satellites (21 operative and 3 backup), in orbit on the planet earth that sends information about the position of a person or object at any time and weather conditions.


Return to the [table of contents](#Table-of-contents).
### References
* debitoor. (s.f.). debitoor. Obtenido de https://debitoor.es/glosario/app-movil
* Significados. (31 de 10 de 2018). Significados. Obtenido de https://www.significados.com/gps/
* smovilidad. (s.f.). smovilidad. Obtenido de https://smovilidad.edomex.gob.mx/transporte_publico


Return to the [table of contents](#Table-of-contents).
### Overview 
* Section 1.- Focused on the explanation, objectives, goals and description of the document.
* Section 2.- General description of the system with information oriented to the client or end user
* Section 3.- Specific requirements and specific terms for the development team
* Section 4.- Appendices


Return to the [table of contents](#Table-of-contents).
## Overall description
### Business Managment Process
* To the business process management we have the [Elicitation process](#Elicitation-process), of which a diagram was made:

### Main diagram

![GitHub Logo](/SRS/Images/Vivebus.png)

### Sub-process #1 - Install the app 

![GitHub Logo](/SRS/Images/Install.png)

### Sub-process #2 - Fill in a request for a new

![GitHub Logo](/SRS/Images/Fill.png)

### Sub-process #3 - Create the new station

![GitHub Logo](/SRS/Images/Create.png)


Here we have the project in visual paradigm with all the processes for a better visualization:
[Vivebus proyect](https://github.com/RequirementEngineering/ch-re-CesarCanoReyna/blob/master/SRS/Vivebus.vpp)


Return to the [table of contents](#Table-of-contents).
### Product perspective 
  * The final product consist in guide people through an application for smartphones through the different vivebus stations spread throughout Ciudad Juárez, for this it will be necessary to install on the smartphone and enable the GPS to connect to the app, it is important to take into account that only works on Android, to be more accurate from version 4.4.4 onwards.


Return to the [table of contents](#Table-of-contents).
### Product functions 
  * Check the names of the stations.
  * Alarm to know in which station it is.
  * Show map of the city in real time.
  * Show location on the map of each existing station.
  * Show the name in order of each station.
  * Creation of new stops in the application.
  * Track your location through the gps
  * Show what position of the map you are in through a red dot.

Return to the [table of contents](#Table-of-contents).
### User characteristics 

User  | Description
----- | -------------
End user | They can only navigate through the application and the map it has. This means that you can only interact and search all Viveus stations on the interface, as well as send e-mails to request a new Vivebus station.
Owner | You do not have to navigate in the application, its function is to modify and update the stations on the map, in order to upload the new .apk file to the Play Store so that users can update the application.
Employee | Can will have access to the data, being able to modify them and confirm that the information is valid, in addition to being in charge of locating the points of the stations on the map.


Return to the [table of contents](#Table-of-contents).
### Constraints 
  * Have an Android 4.4.4 operating system onwards.
  * Only compatible with Android products
  * It is required to have the screen on at all times.
  * The application requires that the gps is always on.
  * If you do not have an electronic account, it will be impossible to make the request for the creation of a new stop.

  
Return to the [table of contents](#Table-of-contents).
### Assumptions and dependencies
  * The gps needs to be on all the time.
  * If you want to make the location calculate faster, you need internet connection.
  * A smartphone is required.
  * The creation of a new stop will have to be certified and validated by the developer


Return to the [table of contents](#Table-of-contents).
## Specific requirements 
In this section we will talk more in detail of all requirements for the development of the app, the interface should be simple and easy to visualize, so that the user can navigate quickly through it without many complications, the stations must be in order to how they are located throughout the city, so that in this way, the user does not have to look one by one to find the one they want, thus making the application more intuitive and easier to understand.

### Interface
  * Principal screen 
     - In the main window you can see the vivebus logo.
     - It will have a menu that indicates the stations to choose, from independence to the station that is in the centro, next they will be shown in descending order all the existing stations until the moment, since in this way they will appear in the application
   
Stations|
------- |
 Presidencia|
 Valderas|
 Vicente Guerrero|
 Monumento|
 Sanders|
 San Antonio|
 Aserraderos|
 Jarudo|
 Minatitlán|
 Sierra madre|
 Ponciano Arriaga|
 Pavo Real|
 Fco. I. Madero|
 La presa|
 Óscar Flores|
 Parral|
 Tecnológico|
 Camboya|
 Oasis|
 El granjero|
 Piña|
 Toronja Roja|     
 Hiedra|
 Las torres 1|
 Las torres 2|
 Babícora|
 Morelos|
 Oaxaca|
 Durango|
 Zapata|
 Los ejidos|
 Ramón Rayón|
 Leona Vicario|
 Indenpendencia|

![GitHub Logo](/SRS/Images/Troncal.jpg)
      
* Map screen
  - In this window we are shown the map of Ciudad Juárez, which will already have all the stations marked with a red dot.   
  - The position of the user who makes use of the application through the gps with a blue dot is also shown.

* Request screen for a new stop
  - First you will have to log in with an e-mail account to try.
  - Once logged in, the map of Ciudad Juarez is shown, where you will leave red dots to mark the location of the new stop.
  - Once we have put the red dot, we will click on continue and an email will automatically be sent to the administrator of the application with the coordinates of the red dot placed by the user.
  
## Requirements
### Functional requirements

General use case

![GitHub Logo](/SRS/Images/General.png)
User  | Description
----- | -------------
Name |
Autor |
Date |
Brief Description |
Actors |
Pre-conditions |
Normal flow |
Alternative flow |
Post-conditions |

 ![GitHub Logo](/Employee.png)

   * End users
     * The end user can send new stations.
     * Can choose which station to travel to.
     * Test the finished product
     * Can see each station in the app
     * Can send suggestions to the developer
     * Can rate the app
     
      ![GitHub Logo](/End.png)
      
   * Owner
     * Can modificate the map.
     * Can modificate the stations.
     * Does not have to navigate in the application.
     
     ![GitHub Logo](/Owner.png)

   * Employee  
     * Can will have access to the data.
     * Confirm the points of the stations in the map.
     * confirm that the information is correct.
     * The employee make the programmation.

  ### Non-Functional requirements  
    * The app must always be connected through the gps.
    * Every time a new station is added, an update of the app should be launched.
    * You can not access the app if you do not have Android higher than 4.4.4.
    * The smartphone screen should always be on.
    
