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
       - [User requirements](#User-requirements) 
       - [System requirements](#System-requirements)
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


Return to the [table of contents](#Table-of-contents).
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
  
  
Return to the [table of contents](#Table-of-contents).
## Requirements
### Functional requirements

#### General use case

![GitHub Logo](/SRS/Images/General.png)

User  | Description
----- | -------------
Name | Vivebus app
Autor | César Antonio Cano Reyna
Date | 26/04/2019
Brief Description | You will have a main task, which is the use and modification of the Vivebus application.
Actors | Developer and user
Pre-conditions | That the application is in use and have contact with the developer
Normal flow | * Developer.- Modificate the app, Create new stations. * User.- check the app, Travel throughout the city.
Alternative flow | In case of failure of the application, restart the app.
Post-conditions | All information sent by users must be saved.


#### Specific use case - Create new station

![GitHub Logo](/SRS/Images/CreateStations.png)

User  | Description
----- | -------------
Name | Create new stations
Autor | César Antonio Cano Reyna
Date | 26/04/2019
Brief Description | The developer creates the new Vivebus stations.
Actors | Developer
Pre-conditions | Verify information
Normal flow | * The developer creates the new station and introduces the new information in the app
Alternative flow | 
Post-conditions | New stations created within the application are saved


#### Specific use case - Log in/ log out

![GitHub Logo](/SRS/Images/Log.png)

User  | Description
----- | -------------
Name | Log in / Log out
Autor | César Antonio Cano Reyna
Date | 26/04/2019
Brief Description | User and developer interact through emails
Actors | Developer and user
Pre-conditions | You must have logged in with any email address.
Normal flow | * The user must log in to send coordinates of the new station.
Alternative flow | 
Post-conditions | 


#### Specific use case - Modificate the app

![GitHub Logo](/SRS/Images/ModificateApp.png)

User  | Description
----- | -------------
Name | Modificate the app
Autor | César Antonio Cano Reyna
Date | 26/04/2019
Brief Description | The administrator modifies the app to add new stops for the Vivebus transport.
Actors | Developer
Pre-conditions | The user should have sent the coordinates of the new stop.
Normal flow | * The developer enters the new coordinates in the application.
Alternative flow | 
Post-conditions | The application must be updated.


#### Specific use case - Travel throughout the city

![GitHub Logo](/SRS/Images/Travel.png)

User  | Description
----- | -------------
Name | Travel throughout the city
Autor | César Antonio Cano Reyna
Date | 26/04/2019
Brief Description | The user travels throughout the city making use of the Vivebus application.
Actors | User
Pre-conditions | Have the Vivebus application installed on a Smartphone.
Normal flow | * the user makes use of the application and will finish using it until he has reached the destination marked within the app.
Alternative flow | Travel through the city without the use of the Vivebus application.
Post-conditions | Finish our trip in the vivebus units having made use of the application.


Return to the [table of contents](#Table-of-contents).

  ### Non-Functional requirements  
    * The app must always be connected through the gps.
    * Every time a new station is added, an update of the app should be launched.
    * You can not access the app if you do not have Android higher than 4.4.4.
    * The smartphone screen should always be on.
    * You must log in to create a new station, you can not use this tool if that requirement is not met.
    * The application must show at all times the map of the city with its respective stations ordered as requested.
    * Each received coordinate must be stored in the developer's email for inspection and verification.
    

Return to the [table of contents](#Table-of-contents).

### User requirements
1. The application must be able to update itself and save new stations for its use.
2. The developer can access to his account and validity the coordinates sent by the user for new stops or edit an existing one.
3. The user can make use of the application if he has Android 4.4.4 or higher.
4. The application must be updated from the store Play store.
5. The application must be fluid and fast, so the map must already be integrated into the application.
6. The application should be easy to visualize and understand.
 
 
Return to the [table of contents](#Table-of-contents).
### System requirements
1.
   * 1.1 The application must be updated for users, the administrator account must be in charge of generating the new stations.
   * 1.2 Each update must be an improvement of your predecessor.
   * 1.3 The administrator's account will be in charge of verifying the existence of the coordinates sent by the users.


2.
   * 2.1 The developer will need to login for the validation of the coordinates.
   * 2.2 To edit an existing stop you need permission from the vivebus managers, however, to generate a new one simply you can verify that the received information is correct.


3.
   * 3.1 If the user has any other operating system different from Android, they can not use the application.
   * 3.2 The user with Android must ensure that they have the operating system 4.4.4 or higher.


4.
   * 4.1 In order for the user to access the new version of the application, it must be downloaded from the Play store.
   * 4.2 The application can only be updated from Play store, if it is downloaded or updated from another site, it will be breaking the rules of its use.


5.
   * 5.1 For the application to be more fluid, it was decided to load the map in the application and thus minimize the loading time.
   * 5.2 In order for the application to find the user's location faster, the use of mobile data or a Wi-Fi network is recommended.


6. 
   * 6.1 In order to make the application easier to visualize, we chose colors that are easy to see and that do not exert much cognitive load.
   * 6.2 The controls of the application are intuitive and easy to handle, so users should not have problems with them.
   * 6.3 To make it clear to the user that the use of the GPS inside the application is crucial, a message is displayed in case of choosing a station and it does not have the GPS on.
   
   
Return to the [table of contents](#Table-of-contents).
## Appendices
### Elicitation process

On April 25, an interview was held with the public transport operators Vivebus, to talk about the application which will be developed by the team formed by the young César Antonio Cano Reyna. Firstly, the operation of public transport Vivebus was discussed. How is the use of these units, we were told in the same way the location of all existing stations spread throughout the city, since to develop the application is necessary to use these.

First mention was made of the interests of those in charge of the Vivebus, which were, to make an application for mobile devices that would facilitate the use of the units to be transported throughout the city, and how the interface of the app would be described in detail. and the processes that it required for its operation.

It was commented that the use of the application was not mandatory for any user that will address their units, since as mentioned above, the use of this will only be to improve and facilitate the use and travel through the Vivebus, an important data for the Development of the app and requirement for its use, is that the user must have a Smartphone that contains the Android operating system.

There was also talk about giving users the opportunity to send emails to the developers of the app mentioning the existence of a new station, for which, the user must log in with any e-mail to send the mail, it was left It is clear that in order for this to be done, the user must be connected to the network in order to send the email.

Here are some important parts about the development of the mobile application and its processes:

Important points of the interview
The application that will be developed will be available only for Android 4.4.4 devices, this application will contain all available stations with the public transport vivebus, at the time of opening it will show us a map, which must be loaded within the application so that in this way the processes are faster, on the map each station will be marked by a red dot, each of these stations must have a proximity range of 20 meters so that in this way a small alarm to the person telling him that he is about to arrive at a new station, and in case of having to descend, prepare for it, for this alarm to work, the Smartphone should have gps, which should be on all moment, in this way, when moving around the city, it will do so in the same way by the map of the application.
- The app must have an administrator, who can enter within this new points, which will be the new stops of the vivebus, if this happens, the application should be updated.

The app must have two main processes, which are:
- Selection of the station you want to reach using the gps:
  * This process first shows the start screen, which will have all the existing stations so far, so that the user can choose which one to reach.
  * One of the many characteristics of the home screen is that it must be ordered according to the existing stations.
  * No account is required to access the application, so anyone with access to a smartphone with Android higher than 4.4.4 and with gps can use it, except to create a new station on the map, and that for this you need to log in with any existing e-mail.
  * In this process, the GPS of the Smartphone is used to locate its location and show it on the map that is automatically loaded, showing us what part of the city we are in and the stations next to which we can reach.
  * In order for the previous process to be executed, it is necessary to have activated the GPS of the Smartphone, so when the application is started, it will be requested to activate it.
  * The location search through the gps is stable, but to have better control of it, it is recommended to turn on the data and once the location is found they can be turned off again.
  
- Creation of a new vivebus stop:
  * This process will consist of the use of the e-mail to have a better handling of the new stations, which at that moment do not appear in the map of the application.
  * The user must log in with any existing e-mail to send the mail about the new station.
  * Once the email reaches the administrator of the application, it will confirm if the received information is correct.
  * Once the information has been verified, the application will be updated by entering the coordinates of the new station and the new .apk file will be uploaded to the play store.
  
Another of the many important points that need to be mentioned is that:
- The app must contain a section showing all the existent vivebus stations so far, so that the person can see where each city is located.
- It will give importance to the emails sent by the users, in order to be always up to date with all the stations within the application.

Once the interview was over, it was agreed to always be in contact so that the delivery of new information would be simple in this way.

In conclusion:
There will be an application for public transport Vivebus located in Juárez City, which will have a section for the creation of new stops, in addition to showing a map of the city with all locations marked with a red dot of existing stations ordered depending on your location, an alarm will sound 20 meters from the station selected on the home screen to warn the passenger that you are about to arrive at your destination.


Return to the [table of contents](#Table-of-contents).
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
