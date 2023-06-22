# Event Tracking App

This is an Android application developed for tracking dates and times of upcoming events. The Event Tracking App allows users to manage their events efficiently and receive notifications for scheduled events.

## Features

- **Database**: The application utilizes a database with two tables: one for storing event details and another for user logins and passwords.
- **User Authentication**: Users can log in to the app using their credentials. If it's their first time, they can create a new account.
- **Upcoming Events**: A grid-based screen displays all upcoming events, providing an organized view of scheduled events.
- **Event Management**: Users can add and remove events from the database, ensuring easy management and customization of their event list.
- **Event Creation**: The app allows users to enter the time and general information of a specific event, ensuring accurate event tracking.
- **Notification System**: The application notifies users on the day of a scheduled event, ensuring they don't miss any important occasions.

## Technologies Used

- Java
- Android Studio
- SQLite Database

## Installation

**Clone the repository using the following command:**    
git clone https://github.com/christopherkelley89/eventtrackingapp.git


## Usage

1. Launch the Event Tracking App on your Android device.
2. Log in using your credentials or create a new account if it's your first time.
3. Explore the upcoming events screen to view all scheduled events.
4. Add new events by using the event creation mechanism.
5. Remove events that are no longer required.
6. Receive notifications on the day of scheduled events to stay updated.
7. SMS Permissions are set once. Currently testing but to test functionality you can uninstall the app in the Android emulator and rerun the code or try toggling off the settings from the Android emulator under settings
8. Long press Events in the main activity screen will highlight them and then you can choose to delete event
9. Log out will log you out of the app. 


## Screenshots
![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/d8453954-106f-43d3-9c1a-3fe28c8ca470)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/4190c8bd-7605-4bc2-8b5a-ab8e6e056362)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/163b2aeb-6765-436d-a246-22506d71b89f)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/fe4a341e-926f-4c61-af93-8b9e74cc58d4)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/9c374aa8-fd05-44a9-b498-f16cb1d76ad6)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/e58a1bdb-661f-4c1f-9af3-5885f2f968f4)

![image](https://github.com/christopherkelley89/EventTrackingApp/assets/60987011/7175cfdb-c90d-4fe9-ac68-0973d208e01b)

# 8-3 Journal 
-**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**
 
 The goal of this app is related to event tracking and management functionality to the potential users of the app. 
 The user needs I addressed included creating, viewing, and deleting events as well as receiving SMS notifications for events happening today. 
 
 # What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
 The screens and features necessary to support users would be:
 **login screen** - Allows users to log in and edit/view/delete events <br>
 **registration screen** - that enabled new users to create an account to start using the app <br> 
 **Main Screen** - MainActivity screen that displays a grid of events and provides options to add and delete events <br> 
 **Add Event Screen** - This screen was unfortunately unfinished but Ultimately it allows users to create a new event by adding a title, date, time, and description of the event. In future revisions, I would add the ability to go back to the main screen! This current iteration forces you to create an event <br>
 **SMS Permission screen** - Prompts the users to grant permissions for sending SMS notifications. I want to improve upon this functionality as I learn more! <br>
 **SMS Permission Dialog** - Asks users to ALLOW or DENY SMS Permission <br> 
 
# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
Object Oriented programming utilizes various Java classes and objects to structure the code of the application. <br>
Implement separate classes for database operations, adapters, and activities. <br>
I also wanted to follow best practices and improve readability and maintainability so anyone could see how everything flows and functions. <br> 
In the future I could further develop my understanding of following design patters that fit the app architecture, continue trying to modularize the code into smaller but more focused components and conducting some sort of code reviews with my peers. <br>

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?
Functional testing by simulating user interactions and verifying the behavior of each feature and the behavior expected. For example, I would like to find a different way to test SMS permissions, in the current state of the app it prompts once only, The only workaround I discovered for testing this was by uninstalling the app from the emulator and then proceeding to restart the emulator. My emulated Pixel 6 did not allow me to forget or delete the permissions from the Android settings.

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?


# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

