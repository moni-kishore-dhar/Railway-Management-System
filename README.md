# Railway-Management-System

<b>Description:</b>
This “Railway Management System” project introduces a simple console application, built without the use of any graphics. This project is done using C++ language; implementing object-oriented programming and other C++ features. The perspective of this project is able to get more familiar with solving real life problems.
This project has password protection mode and file handling operations to add and display train inquiry and reservation records. The purpose of this particular project is to create digital reservation system so that manual workload could be reduced.

<b>Features:</b>
1. <b>Administrator mode:</b>
Administrator needs to log in with id and password. <b>(Id: admin; Password: 123)</b> After log in administrator can add train as well as he will be able to schedule the train. In this mode, administrator can create detail database, add details of train, display train and passenger details. All the information is saved in auto generated files to further use.
2. <b>User mode:</b>
User can sign up and login on their own. This information is saved in auto generated files to further use. After having user id and password, one can get the detail reservation information such as train information & ticket information, can buy & cancel ticket.
3. <b>Train and Reservation details:</b>
In this project, users can get both train and reservation details. The details to be provided for train are: Train No, Train Name, From, To, Departure time, Arrival Time and Off day. For the reservations there is Buy Ticket. Here is the information of   which train to choose, which date to choose, which compartment to choose, which seat to choose and seat fare.
4. <b>Cancel Reservation:</b>
In this project one can cancel their reservation through Cancel Ticket. Here the reservation information of the particular user is shown for trains such: Train No, Train Name, From, To, Departure time, Arrival Time. This feature requires the selection of Ticket No. Upon selecting the number, the reservation gets canceled.
5. <b>Password:</b>
This railway management system project requires the administration password to access the administration mode. <b>Username is ”admin” and the password is ”123”</b>. If we enter the wrong password, it displays the massage – “Wrong Password”.

<b>Header Files Used: </b>
To make the project simple, graphics.h header file has not been used in this project. List below are the header files required to run this project:<br>
#include <bits/stdc++.h><br>
#include <fstream.h>

<b>To implement this simple case study, some features have been made, which are as follows:</b>
1.	A user can buy only next day or above tickets; present day reservation is not allowed.
2.	Bookings are only open for seven days from local time. In that case, it can handle variations in number of days in different months. (Like: January: 31 Days, February: 28 Days, April: 30 Days, In Leap Year February: 29 Days.)
3.	A single user cannot buy more than 4 tickets.
4.	A user can select the preferred compartment and seat (if available).

