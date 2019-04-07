## SRS ViveBus application.
## 1.	Introduction
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
Employee | You will have access to the data, being able to modify them and confirm that the information is valid, in addition to being in charge of locating the points of the stations on the map.


* Constraints 
  * The system requires a server with the system running.
  * El sistema requiere un servidor con el sistema se ejecuta.
  
* Assumptions and dependencies
  * The server need to be always running
  * Specific changes provided by Hacienda or SAT need to be realized by the developer
  * The system it does not work until the Sat modification is made
  * The owner needs approve the the invoices before they are made


## Specific requirements 
In this section we have more detailed information about the specific requirements of the system
develop.
The interface must be simple and with few elements to show, so that you can navigate quickly through it.
It should not contain too many colors.


* Interface

  * First screen
    * The first screen should show a welcome message and with its fields to login.
    * The window will have a small size of 500 x 500 pixels.

  * Principal screen 
    * The principal screen will have a size that occupy the full window.
    * Must have a menu at the top that shows the following characteristics and functions: 
   
      * Invoice
        * Invoice a previous quote
        * Check invoice issued
        * Cancel invoice
        * See all invoices (Owner only)
    
      * Quotation
        * Generate new quote
        * Search quote by number
      
      * Modify (New, Delete, edit)
        * Client
        * Provider
        * Product

  * Administrator screen
    * This screen should available only for the system administrator(Owner) so in this screen the administrator can: 
      * Add a new user
      * Change privileges for each user
      * Delete user
      * See user movements
      * Check quotes and invoices issued by each user
      
* Requirements



  * Functional requirements by users
  ![GitHub Logo](/administrator.png)
    * Owner (administrator)
      * The administrator can make user registrations
      * Can unsubscribe a user or edit their privileges
      * Must approve the invoices issued by the users.
      * Will be able to see each invoice and quotation of the users
      * Can see the gains according to the desired period
      * Can add and modify clients, as well as suppliers
      * The administrator can also generate invoices and quotes
  ![GitHub Logo](/Invoice.png)
    * Employee  
      * The employee may generate invoices that will be approved by the administrator
      * The employee can generate quotes and can export them in PDF format
      * The employee has access to edit quotes and also be able to bill them
      * The employee has his own user

  * Non-Functional requirements  
    * The system must be connected to the server by means of a modem / router
    * It will have a database that will be stored on the server, it will keep all the information about customers, suppliers and users
    * Each quote and invoice must be stored both on the client computer and on the server
    * The system can not be accessed if it is not accessed through a user account
    * The system must request the respective characteristics to be able to invoice, both the key and the .xml files provided to the company by the SAT


