# CabShare App
## Overview
CabShare is a mobile application designed to help college students coordinate and share cabs to the airport during vacation periods. The app simplifies the process of finding and connecting with peers traveling to the same destination, enabling users to save costs, reduce environmental impact, and improve travel convenience. The app features a streamlined interface, real-time chat, and scheduling functionalities to ensure seamless coordination.

## Key Features
### 1. User Authentication:
Secure user sign-up and login using email/password authentication.
Integration with JWT (JSON Web Tokens) for session management.
### 2. Travel Schedule Sharing:
Users can share their travel schedules, including departure time and location.
A list of available schedules is visible for easy matching.
### 3. Real-Time Chat:
Built-in messaging system to discuss and finalize cab-sharing plans.
Typing indicators and read receipts for better communication.
### 4. Push Notifications:
Alerts for new chat messages or schedule match updates.
### 5. Scalable Backend:
Node.js backend with RESTful APIs for handling user authentication, schedule management, and chat.
MongoDB database for storing user and travel schedule data.
### 6. AWS Hosting:
The backend is hosted on AWS EC2 for high availability and scalability.
MongoDB Atlas for a managed database solution.
Technology Stack

## Frontend
### Language: 
Swift (SwiftUI framework).
### Libraries:
Combine for data binding.
URLSession for API communication.

## Backend
### Framework:
Node.js (Express.js).
### Database:
MongoDB (MongoDB Atlas for hosting).
### Authentication:
JWT for secure user authentication.
### APIs:
RESTful API design.
## Hosting
### Backend:
AWS EC2 (Ubuntu instance).
### Database:
MongoDB Atlas.

## System Architecture
### Frontend:
SwiftUI app that interacts with the backend using REST APIs.
Securely handles user data and real-time updates for chat and schedules.
## Backend:
Node.js server handles user requests, manages data, and processes messages.
MongoDB database stores user profiles, schedules, and chat messages.
