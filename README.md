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
- Veiw guests complaints.  
- Accept or deny incoming booking requests.  
- Mark rooms and services as available or not.  
- Add a new Service to a hotel.  
- Change and control prices for each hotel separately.  
- Can veiw system's statical information like how many rooms, cars, ..etc and their conditions.  
- Should see revenue progress with time to acquire marketing info.  
- Can veiw guests and staff status and/or cancel requests.  
- Select specific hotel to administrate.  
- Provide marketing information to the system.  
- Organize housekeeping tasks and schedules.  
- Add hotels and post available bookings.  
- Events organization.  

### Guest  
The guest shoud be able to:  
- Send tips after service is done.  
- Provide rating for the service.  
- Provide their medical status -if special care is needed.-  
- Choose the room type.  
- Contact admins.  
- Contact reception.  
- Contact staff.  
- Choose a hotel in his prefered location.  
- Enter required registeration information.  
- See his information and able to edit them if needed.  
- Select a service.  
- Pay fees.  
- get offers and suggestions.  
- book for other friends and family members.  
- provide compliants.  
- Create account.  
- Reserve Hotel services.  
- Chick in and check out.  
- Read reviews and veiw hotel rating.  
- Write reviews and give rating.  

### Staff/manager  
The staff should be able to:  
- Recieve their tasks.  
- Communicate with each other.  
- Get notifications from Admin.  
- Provide apologizes and appeals to the admin.  
- Sent reports to the Admin.  
- Check in and check out guests by providing them with an ID (manager only).  
- Provide additional amenities to guests as offers (manager only).  
- Mark the finished tasks as done.  
- Post the fees for the services (managers only).  
- Has a wallet to recieve guests tips.  
- See their working history.  
- Can notify other team members if they can't do the required service.  
- Receive customers’ housekeeping requests.  
- View their schedules and required tasks.  

## Assumptions and Dependencies
The users need to have a web browser and internet connectivity. also its assumed that the users have a machine  
loaded with operating system cabable of running a web browser.
Hotels included within the system are 5-star hotles providing wide varaity of services and events and containing a relativly large number of visitors around 300 users.  
High speed internet connectivity is assumed to ensure small response time.

## System Features and Requirements

### Functional Requirements
The system should be abl to provide the following :  
- Welcome page asking the client if he/she was a guest or admin/staff.  
- Different page for every type of users.  
- The system should store all needed information about the users.  
- Login page.  

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
- The system will forbid the user from registering at two different hotels at the same time.  
- The guest can book for other friends and family members.  

For admins:  
- Admin page (dashboard).  
- Admin account page (showing account info).  
- a page showing company hotels to choose from with button to add another hotel.  
-  
- A page showing guest complaints.  
- A messages page to send messages to both workers and guests by ID.  
- a page showing message.  
- A mail inbox to receive guests and workers messages.  
- A page showing recent booking requests.  
- a page for every request showing details and ability to accept or deny.  
- A control service page showing current service with their status with the ability to block, allow or control service.  
- a page for each serivce showing its details.  
- The system should be able to add a service with the required attributes by the admin.  
- a page for adding a services and entering its info.  

For the staff:  
- Staff page.  
- Different account type for every staff/worker type.  
- Chat board for the staff. 
- A page for the workers to veiw their working history.  
- Messages box to receive notifications from the Admin.
- Messages box to receive notifications from other workers.  
- A to do list showing recent guests requests.  

### External Interface Requirements
This Web Application will need to interface with a database to provide all needed info including but not limited to : userdata, hotel attributes, ..etc.  
The Client-Side interface will be via the web browser showing the pages of the web app.

### System Features and use cases  
- Guest veiw point :  
The guest will head to the main page (welcoming page) which will ask the client if he/she was a guest or admin/staff.  
If guest the app promotes a page asking for prefered location and suggesting nearby hotels based on that.  
The guest will then determine duration of residence and price.  
Then the chosen hotel will be shown with nearby locations and events with pictures of the hotel,  
location and offers like a safari trip with detailed information like The place and the price.  
Hotel rooms will be shown with their pros and cons and prices. after the room is chosen,   
the guest will be asked for payment and will be shown The time before the check in deadline to avoid penality.  
after that the guest will be asked some extra questions like,  
his information and if the guest had accompanying animals or if car rental was need or if the guest had medical problems ..etc.  
the guest will be asked for any special services like birthday party ..etc.
the room information and guest services will be displayed on the account page.  
If the guest the room its information will be displayed.  
the guest page will have several boxes : box for room, customer services, complaints, help, payments, messages.  
complaints box leads to a page which allow the guest to send a complaint messages to the complaints board which appears to the corresponding admin.  
the customer service box leads to a page where which lists all services of the hotel.  and every entery leads to a page requesting this service. help page provide the user with details on how the system works.  
messages pages provides messaging template and list options like mailing the admins or the staff or reception.  
it also provide contact numbers of every team and service.  
the payment page provide the user with payment and currency options and the required money.

- Admin veiw point :  
The admin will head to the main page and choose login option.  
Another page will open to provide user credentials.  
After that the Admin will be promoted to a page listing all hotels in the group and a button to add a new hotel,  
this button leads to a page to specify hotel info, other hotels icons in the list leads to the contoling dashboard for the corresponding hotel to monitor.  
Then a dashboard for that hotel will appear with the following options:  
Choose hotel : which leads to the previous page showing hotels list to choose from.  
Events: when the admin select events button it leads to a page with two buttons (add event) and (current events),  
add event leads to a page to enter event info.  
current events shows a page with current held events and leads to a page detailing the event when clicked.  
Services: when selected it leads to a page with two buttons.  
add service: leads to a page asking for new service info and details.  
veiw service: leads to a page veiwing current services and when clicked leads to a page detailing the service.  

Guests : which leads to a page listing all guests by names and ID, guest info appears when clicked, asking for offers to be provided or messages to be send.  

staff : leads to a page listing staff by name and ID. worker status appears when clicked with the ability to assign or cancel assigned services.  

guests complaints : a page shows recent guests complaints in the form of posts with date and case.  

incoming requests : shows list recent booking requests, details displayed when entery is clicked and ask for acceptance.  

room/services control :  page listing room and services and when clicked leads to a page with details and boxes and buttons for determining prices and availability of the room/service.  

statical info :  page shows chats of revenue, rooms full, rooms empty, services under usage and without usage ..etc.  

- Staff veiw point :  
The staff worker will head to the main page and choose login option. Another page will open to provide user credentials. After that the staff worker will be promoted to a dashboard with the following options:  

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

