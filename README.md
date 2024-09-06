

# Fully Functioning Chat Messenger

## Description
The **Fully Functioning Chat Messenger** is a cross-platform mobile app developed using Flutter, designed for both Android and iOS. It offers real-time messaging, image sharing, robust offline support, and a modern neumorphic UI.

## Key Features

- **Super Fast Messaging:**
  - Real-time message delivery using the MQTT protocol.
  - Messages stored locally in SQLite for quick access and offline functionality.

- **Phone Number Authentication:**
  - Secure sign-in using Firebase authentication.

- **Image Sharing:**
  - Send and receive images with a whatsapp-style UI.
  - Images stored locally in SQLite, not cluttering the device gallery.

- **Contact Integration:**
  - Syncs phone contacts to find other users.
  - Add contacts via usernames and send friend requests.
  - Block/unblock contacts.

- **Push Notifications:**
  - Real-time notifications using OneSignal for new messages, friend requests, and acceptances.

- **Profile Customization:**
  - Change profile photo with image compression for efficient storage.

- **Neumorphic UI and Emoji Support:**
  - Modern, visually appealing design.
  - Enhance interactions with emojis.

- **Offline Access:**
  - Messages accessible offline, stored in the local SQLite database.

- **Invite Friends:**
  - Feature to invite friends to join the messenger app.

## Tech Stack and Integrations

### Mobile App Development
- **Frontend:** Flutter
- **Programming Language:** Dart

### Backend
- **Database:** Firestore for user data, SQLite for local storage of contacts and chats
- **Storage:** Firebase Storage for images
- **Messaging Protocol:** MQTT hosted on AWS EC2
- **Notifications:** OneSignal for push notifications

### Other Integrations
- **Google Maps API:** For real-time order tracking and location services
- **Payment Gateway (e.g., Stripe):** For secure online payments

## Contribution

### Flutter Development
- **App Design & Development:**
  - Created a smooth, responsive mobile app using Flutter for both Android and iOS.
  - Implemented real-time messaging with MQTT, ensuring fast and reliable communication.
  - Developed contact integration for syncing phone contacts and finding friends by username.

- **Local Database Management:**
  - Utilized SQLite for efficient local storage of messages and contacts, enabling offline access and fast loading times.
  - Stored images in SQLite in bytes format, keeping the device gallery uncluttered.

- **Authentication & Security:**
  - Integrated Firebase for secure phone number authentication and protected user data.

- **Real-Time Features & Notifications:**
  - Implemented OneSignal for push notifications, keeping users informed about messages and friend requests.
  - Integrated Google Maps API for real-time location-based services.

- **Profile Customization & Media Handling:**
  - Enabled profile photo changes with image compression for efficient storage.
  - Developed a Snapchat-style UI for sending and receiving images.

- **UI/UX Enhancements:**
  - Applied a modern neumorphic design for a visually appealing user experience.
  - Added emoji support to enhance user interactions.

## Impact

- **Enhanced User Experience:**
  - Delivered an intuitive, responsive app resulting in high user satisfaction.

- **Increased Engagement:**
  - Real-time messaging and push notifications improved user engagement and retention.

- **Robust Offline Capabilities:**
  - Provided reliable access to messages offline, improving user experience.

- **Efficient Performance:**
  - Optimized local storage and media handling for quick load times and minimal storage impact.

- **Positive Market Reception:**
  - Received praise for real-time tracking, secure messaging, and modern design, driving increased adoption.

## Snapshots

![Onboarding](https://github.com/user-attachments/assets/3f0ebaa9-8e03-4648-938d-7d63b43972c2)
![Sign in](https://github.com/user-attachments/assets/d6b4b73a-c0bd-49cd-99d6-533c2e690193)
![Home](https://github.com/user-attachments/assets/868556d4-050a-469b-bcc6-d262c3dc0337)
![User profile](https://github.com/user-attachments/assets/5f1f3271-63bb-4830-92c8-9f9340a9ba59)
![Message](https://github.com/user-attachments/assets/1fcc53e2-10e6-4749-9d2e-ac7ee183caff)
