# MovieTicketBooking-System

Required Module

1) MYSQL Connection - npm install mysql

2) Uppercase - npm install upper-Case

3) console module - predefined in nodejs

4) Table Interface - npm install table

*********************************************************************************************************************************************************************************

Queries to create database:

1) Creating new database

2) create database if not exists ticketbook;

3) Creating table movie :

4) CREATE TABLE if not exists movie ( movieName varchar(255) DEFAULT NULL, movieTime varchar(255) DEFAULT NULL, movieDate varchar(255) DEFAULT NULL, movieSeats varchar(255) DEFAULT NULL, moviePrice varchar(255) DEFAULT NULL, movieNumber varchar(255) DEFAULT NULL );

5) Create table userinfo

6) CREATE TABLE userinfo ( customerName varchar(255) DEFAULT NULL,customerEmail varchar(255) DEFAULT NULL, customerPhone varchar(255) DEFAULT NULL, movieNumber varchar(255) DEFAULT NULL, movieName varchar(255) DEFAULT NULL, movieTime varchar(255) DEFAULT NULL, movieDate varchar(255) DEFAULT NULL, customerSeats varchar(255) DEFAULT NULL, totalPrice varchar(255) DEFAULT NULL );


*********************************************************************************************************************************************************************************

Logic of the project

1. Switch Case: a. admin b. User
 A. Admin:
            1) Movies - Add name of movies
            2) Ticket - Price & No of Seats
 2. User:
        1) Select Movies - will display No of seats & Price of Ticket 
            - will ask for number of tickets
                - price of single ticket x number of selected seats
                    - display number of seats and total price
                        - message : ticket is booked.


**********************************************************************************

Structure:

******************Title************************
Menu:
 - Select users:
            a. Admin
            b. Customer
            
*****************Admin*****************************

 - Select Menu:
    a. Add Movie - number of seats (Added By default) and price of single unit (1. Name of Movie 2. Time of show 3. Unit price of single ticket) 
    b. Number of seats in hall 
    c. Exit
    
*****************Customer***************************

1. Book a ticket
2. Exit


Required Modules to Install:
1. MYSQL Connection - npm install mysql
2. Uppercase - npm install upper-Case
3. console module - predefined in nodejs
4. Table Interface - npm install table
