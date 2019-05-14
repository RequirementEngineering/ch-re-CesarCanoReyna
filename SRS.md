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
Facturation system</br>
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
    - [Business Managment Process](#Business-Managment-Process)
    - [Product perspective](#Product-perspective)
       - [Product Functions](#Product-functions) 
    - [User characteristics](#User-characteristics)
    - [Constrains](#Constrains)
3. [Specific requirements](#Specific-requirements) 
    - [Interface](#Interface)
    - [Requirements](#requirements)
       - [Functional requirements by users](#Functional-requirements-by-users)
       - [Non functional requirements](#Non-functional-requirements) 
3. [Appendices](#Appendices) 
   - [Elicitation process](#Elicitation-process)
    










## Introduction
•	Purpose: 
* This document is intended to publicize the general operation
of the ViveBus software in Ciudad Juárez, is aimed at all users of this and every new member who goes on green public transport.

•	Scope: 
* The name of the finish product it will be “ViveBus App”. 
* The application should promote the benefits offered by the ViveBus application and offer a simple way to travel and get to know each of the stations picked up throughout the city.
* The benefits of this application is that those interested have an easier way to find information about the stations, as well as to choose which station they go to, their main objective is to facilitate the way of traveling around the city.

•	Definitions, acronyms, and abbreviations

* ViveBus.- Bus Rapid Transit.
*	App.- Application 
*	UML.- Unified Modeling language 
*	Mercedes Benz.- German company luxury vehicle manufacturer

•	References
* ....

•	Overview 
* Section 1.- Focused on the explanation, objectives, goals and description of the document.
* Section 2.- General description of the system with information oriented to the client or end user
* Section 3.- Specific requirements and specific terms for the development team
* Section 4.- Appendices

## Overall description

* Product perspective 
  * Guide people through an application for smartphones through the different vivebus stations spread throughout Ciudad Juárez, for this it will be necessary to install on the smartphone and enable the GPS to connect to the app, it is important to take into account that only works on Android, to be more accurate from version 4.4.4 onwards.

* Product functions 
  * Check the names of the stations.
  * Alarm to know in which station it is.
  * Show map of the city in real time.
  * Show location on the map of each existing station.
  * Show the name in order of each season.
  * Away from doubts and improvements.
  * Show travel time.

* User characteristics 

User  | Description
----- | -------------
End user | They can only navigate through the application and the map it has. This means that you can only interact and search the interface.
Owner | Does not have to navigate in the application, its function will be to modify and update the stations in the map.
Employee | Can will have access to the data, being able to modify them and confirm that the information is valid, in addition to being in charge of locating the points of the stations on the map.


* Constraints 
  * Have an Android 4.4.4 operating system onwards.
  * Only compatible with Android products
  * It is required to have the screen on at all times.
  * The application requires that the gps is always on.
  
  
* Assumptions and dependencies
  * The gps needs to be on all the time.
  * If you want to make the location calculate faster, you need internet connection.
  * A smartphone is required.
  * You need to find the station to get there.


## Specific requirements 
* Interface
  * Principal screen 
     * In the main window you can see the vivebus logo.
     * It will have a menu that indicates the stations to choose, from independence to the station that is in the centro
   
      * trunk map
       * Presidencia
       * Valderas
       * Vicente Guerrero
       * Monumento
       * Sanders
       * San Antonio
       * Aserraderos
       * Jarudo
       * Minatitlán
       * Sierra madre
       * Ponciano Arriaga
       * Pavo Real
       * Fco. I. Madero
       * La presa
       * Óscar Flores
       * Parral 
       * Tecnológico
       * Camboya
       * Oasis
       * El granjero
       * Piña
       * Toronja Roja
       * Hiedra
       * Las torres 1
       * Las torres 2
       * Babícora
       * Morelos
       * Oaxaca
       * Durango
       * Zapata
       * Los ejidos
       * Ramón Rayón
       * Leona Vicario
       * Indenpendencia

      
* Requirements

 ![GitHub Logo](/Employee.png)


 * Functional requirements
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

  * Non-Functional requirements  
    * The app must always be connected through the gps.
    * Every time a new station is added, an update of the app should be launched.
    * You can not access the app if you do not have Android higher than 4.4.4.
    * The smartphone screen should always be on.
    
