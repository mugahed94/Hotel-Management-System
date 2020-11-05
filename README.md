# Hotel Management System
Term project of software engineering course, 3rd year computer engineering, Ain-Shams University.

below is the SRS document of the system.  

## Introduction
During this era of time hotels have increased in complexity due to the wider combination of guests and the wider
varaity of services provided.
In this section we provide an easy-to-use tool to manage a series of five star hotels. Putting in mind important qualities for the tourism industry
such as speed, performance, and security. providing the customer company with capabilities of expanding their business without changing the used software.  

## Purpose
The purpose of this web application is to provide comfort and ease for hotel managers managing their provided services  
by providing the user with simple and easy user interface while getting required information and showing all the details to system admins  to ensure best market value.  
and also providing workers by good communication tools to increase the performance of the working team and clarify their day to day work objectives.


## Intended Audience
This web App is intended to be used by:  
- Admins / Manengers : to manage the working staff and serve and provide offers to cutomers while getting  
info and updates about their system to provide insights and marketing info.  

- Guests : who want to book rooms and attain high quality servecies.

- Working Staff : who needs to veiw their tasks and communicate with other workers and guests.


## Contributers
waiting for team names and codes

## Application Type
Web Application accessable via a web browser.

## Programming languages used
Python, HTML, CSS, JavaScript, MySql.

## Intended Use
To be used by Hotels managers and admins, working staff like drivers, cleaning workers, waiter, ..etc
also use by a wide varaity of guests from a wide range of age, cultures and conditions.

## Scope
Used within hotels and tourism environment.

## Definitions
- Housekeeping :  
Cleaning and tiding rooms.  
- Hotel Events :  
events organized by the hotel such as birthday parties.  
- Hotel Services:  
Housekeeping, laundry, food and drinks, car rental, parking, ...etc.  

## Overall Description  



## User Needs

### Admin  
The Admin should be able to:  
- Send messages to Staff.  
- Send messages to Guests.  
- Accept or deny incoming booking requests.  
- Mark rooms and services as available or not.  
- Add a new Service to a hotel.  
- Change and control prices for each hotel separately.  
- Can veiw system's statical information like how many rooms, cars, ..etc and their conditions.  
- Should see revenue progress with time to acquire marketing info.  
- Can veiw guests and staff status and/or cancel requests.  

### Guest  
The guest shoud be able to:  
- Send tips after service is done.  
- Provide rating for the service.  
- Provide their medical status -if special care is needed.-  
- choose the room type.  

### Staff  
The Admin should be able to:  
- Recieve their tasks.  
- Communicate with each other.  
- Get notifications from Admin.  
- Provide apologizes and appeals to the admin.  
- Sent reports to the Admin.  
- Check in and check out guests by providing them with an ID.  
- Provide additional amenities to guests as offers from the worker.  
- Mark the finished tasks as done.  
- Post the fees for the services.  
- Has a wallet to recieve guests tips.  
- See their working history.  
- Can notify other team members if they can't do the required service.  

## Assumptions and Dependencies
The users need to have a web browser and internet connectivity. also its assumed that the users have a machine  
loaded with operating system cabable of running a web browser.

Hotels included within the system are 5-star hotles providing wide varaity of services and events and containing a relativly large number of visitors around 300 users.  

High speed internet connectivity is assumed to ensure small response time.

## System Features and Requirements

### Functional Requirements
Under construction...  
system goals and how will function to deliver user's needs.  
detailed description of the application’s features and the user’s needs.  

- Welcome page asking the client if he/she was a guest or admin/staff.  
- Different page for every type of users.  
- The system should store all needed information about the users.  


For Guests: 
- Guest page.  
- Page asking the guest for the preferred location and suggesting nearby Hotels.  
- Page asking the user for the duration of residence and different prices.  
- The system should suggest and show hotels based on users preferences.  
- Page showing chosen hotel with nearby locations, activities, and events.  
- The system should provide pictures of the hotel and all the details about the offers and events shown
including the place and price.  
- Page for every room with its pros and cons, price, attributes like size, ..etc.  
- payment page.
- Page showing the user time available to check in before the deadline of applying a penality.  
- Page asking the user for about extra information and suggesting related services that may be needed.  
- The system need to show room info and guest services on the account page.  
- Guest page will include box (button) for each of these : room, customer services, complaints, help, 
check in and out, payment, messages.  
- A page for every service.  
- All boxes in guest account will be locked until arrival and checking in, except the check in box.  
- user will check in using provided ID at arrival.  
- A page deticated for every box in the account page.  
- The system will force the guest to check out before leaving.  
- The system will ask the user for payment visa/cash when leaving.  
- The guest will be promoted for rating before leaving.  

For admins:  
- Admin page.  

For the staff:  
- Staff page.  
- Different account type for every staff/worker type.  
- Chat board for the staff. 
- A page for the workers to veiw their working history.  
- Messages box to receive notifications from the Admin.
- Messages box to receive notifications from other workers.  



### External Interface Requirements
This Web Application will need to interface with a database to provide all needed info including but not limited to : userdata, hotel attributes, ..etc.  
The Client-Side interface will be via the web browser showing the pages of the web app.

### System Features and use cases  
- Guest veiw point  
- Admin veiw point  
- Staff veiw point  

### Non-functional Requirements
- Performance:  
The application should update the interface on interaction within 3 seconds.  
The database should be normalized to prevent redundant data and improve performance.  

- Security:  
secure connection to the server should be ensured. Also users passwords should be hashed before stored.  

- Availability:  
This web app need to be compatible with Firefox and Google Chrome - the most popular web browsers.  

- Usability:  
This web app can be accessed via wide range of computer platforms as it works via web browsers making it  
compatible with most operating systems.  
the interface should be basic and easy learn without a tutorial allowing user to acomplish their goals without errors.

