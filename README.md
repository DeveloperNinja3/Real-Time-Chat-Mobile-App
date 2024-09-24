# Fully Functioning Chat Messenger

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-00A5E0?style=flat&logo=internetofthings&logoColor=white)
![OneSignal](https://img.shields.io/badge/OneSignal-FF5C00?style=flat&logo=onesignal&logoColor=white)

### Industry:
Mobile Communication

### Technologies Used:
- **Frontend**: Flutter
- **Programming Language**: Dart
- **Backend**: Firebase Firestore, SQLite
- **Storage**: Firebase Storage
- **Messaging Protocol**: MQTT hosted on AWS EC2
- **Notifications**: OneSignal
- **Other Integrations**: Google Maps API, Payment Gateway (e.g., Stripe)

## Project Overview
The **Fully Functioning Chat Messenger** is a cross-platform mobile application developed using Flutter, providing users with a seamless messaging experience on both Android and iOS devices. The app supports real-time messaging, image sharing, robust offline access, and features a modern neumorphic user interface.

### Key Features:
- **Super Fast Messaging**: 
  - Real-time message delivery using the MQTT protocol.
  - Local storage of messages in SQLite for quick access and offline functionality.
  
- **Phone Number Authentication**: 
  - Secure sign-in using Firebase authentication.
  
- **Image Sharing**: 
  - Send and receive images with a WhatsApp-style UI.
  - Images stored locally in SQLite to keep the device gallery uncluttered.
  
- **Contact Integration**: 
  - Syncs phone contacts to find other users.
  - Add contacts via usernames and send friend requests.
  - Block/unblock contacts.
  
- **Push Notifications**: 
  - Real-time notifications using OneSignal for new messages, friend requests, and acceptances.
  
- **Profile Customization**: 
  - Change profile photo with image compression for efficient storage.
  
- **Neumorphic UI and Emoji Support**: 
  - Modern, visually appealing design that enhances user interactions with emojis.
  
- **Offline Access**: 
  - Messages accessible offline, stored in the local SQLite database.
  
- **Invite Friends**: 
  - Feature to invite friends to join the messenger app.

## Business Challenge
The development of the Fully Functioning Chat Messenger faced several challenges:
- **Integration Complexity**: Managing various packages for functionalities such as messaging, image sharing, and user authentication posed compatibility and performance issues.
- **Real-Time Messaging**: Ensuring reliable real-time message delivery while maintaining app performance and user experience.

## Solution Delivered
To overcome these challenges, the following solutions were implemented:
- **Modular Development**: Leveraged Flutter’s plugin system to facilitate the integration of essential packages efficiently.
- **Robust Messaging Protocol**: Utilized the MQTT protocol for fast and reliable message delivery.
- **Centralized Database Management**: Employed SQLite for efficient local storage, ensuring quick access to messages and contacts.

## Implementation Highlights
- **Flutter Development**: Designed and developed a smooth, responsive mobile application for both Android and iOS.
- **Local Database Management**: Utilized SQLite for local storage of messages and contacts, enabling offline access and enhancing loading times.
- **Authentication & Security**: Integrated Firebase for secure phone number authentication and user data protection.
- **Real-Time Features & Notifications**: Implemented OneSignal for push notifications, keeping users informed about messages and friend requests.
- **User Interface**: Developed a modern neumorphic design and added emoji support to enrich user interactions.
- **Image Handling**: Enabled image sharing with efficient local storage management to prevent clutter in the device gallery.

## Outcomes
- **Enhanced User Experience**: Delivered an intuitive and responsive app, resulting in high user satisfaction.
- **Increased Engagement**: Real-time messaging and push notifications led to improved user engagement and retention.
- **Robust Offline Capabilities**: Provided reliable access to messages offline, enhancing overall user experience.
- **Efficient Performance**: Optimized local storage and media handling for quick load times and minimal storage impact.
- **Positive Market Reception**: The app received praise for its real-time tracking, secure messaging, and modern design, contributing to increased adoption among users.

The Fully Functioning Chat Messenger stands out as a comprehensive solution in mobile communication, combining security, speed, and user-friendly design to meet the needs of modern users.


## Snapshots

![Onboarding](https://github.com/user-attachments/assets/3f0ebaa9-8e03-4648-938d-7d63b43972c2)
![Sign in](https://github.com/user-attachments/assets/d6b4b73a-c0bd-49cd-99d6-533c2e690193)
![Home](https://github.com/user-attachments/assets/868556d4-050a-469b-bcc6-d262c3dc0337)
![User profile](https://github.com/user-attachments/assets/5f1f3271-63bb-4830-92c8-9f9340a9ba59)
![Message](https://github.com/user-attachments/assets/1fcc53e2-10e6-4749-9d2e-ac7ee183caff)
