
 
# Kind Words Messaging Application
  This is a web chat application project inspired by the popular game Kind Words. Users can communicate with each other in real-time. It is built using the Spring Boot framework for the backend and React for the frontend. The project utilizes Maven as the build tool for the backend.

  This project was inspired by a previous hackathon project. The main difference is that this app is using the Spring Boot framework written in Java.

  Users are strongly encouraged to use positive, inclusive language in the chat. Make someone else's day brighter by offering words of comfort, sympathy or gentle advice.
  
## Features
-  __User Authentication__: Users are required to log in with a username before they can access the chat application.
- __Real-time Chat__: Once logged in, users are directed to the chat page where they can send messages in the chatroom.
- __User Presence__: Users are notified when new users join the chatroom, allowing them to be aware of other participants.
- __Private Messages__: Users have the ability to send private messages to specific individuals.
- __File Transfer__: The application supports the transfer of multimedia files, such as photos and videos.
- __Logout__: Users can log out from the application, and their username will be removed from the user list displayed to other participants.

## Tech Stack
The application incorporates the following technologies:

- __Spring Boot__: A Java-based framework used for building the backend server and handling business logic.
- __React__: A JavaScript library used for building the user interface and handling frontend functionality.

## Setup Instructions
To run the chat application locally, follow these steps:

1. __Clone the repository__: ``` git clone https://github.com/mguan2020/Kind-Words-Messaging-App.git```
2. __Navigate to the project directory__: ```cd chatroom-backend```
3. __Set up the backend server__:
   - Install the necessary dependencies: ```mvn clean install```
   - Start the Spring Boot server: ```mvn spring-boot:run```
4. __Set up the frontend__:
   - Install the necessary dependencies: ```cd chatroom-ui``` && ```npm install```
   - Start the React development server: ```npm run dev```
5. __Open your web browser__ and visit ```http://localhost:5173``` to access the chat application.

## Screenshots
Here are some screenshots of the chat application:

2. Chat Page
- Chatroom ![](https://github.com/Kshitijk5/Springboot-chatapp/blob/master/img/Chat-2.png)

- Private Text ![](https://github.com/Kshitijk5/Springboot-chatapp/blob/master/img/Chat-1.png)
