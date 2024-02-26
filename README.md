# Flutter Messenger Application


## Description
Welcome to our innovative Flutter chat application! This feature-rich messaging platform allows users to connect and communicate seamlessly through text and images. The app is built using Flutter for the frontend and integrates with Firebase for backend services, including authentication, real-time database, and storage.

## Features
- User-friendly interface for an intuitive chatting experience.
- Firebase authentication with OTP verification for secure sign-ins.
- Real-time messaging using Firebase Realtime Database for instant message delivery.
- Firebase Storage integration for sharing images.
- Supports both Android and iOS platforms.



## Setup Instructions
To use this project, follow these steps:

1. Clone the repository to your local machine:
Replace `https://github.com/Hamad-Anwar/Messenger-App-Backend-Firebase` with the URL of this GitHub repository.

2. Set up Firebase:
- Create a new Firebase project in the [Firebase Console](https://console.firebase.google.com/).
- Enable Firebase Authentication with OTP verification, Firebase Realtime Database, and Firebase Storage for your project.
- Download the `google-services.json` file from Firebase and place it in the `android/app/` directory of this Flutter project.

3. Install Flutter:
Ensure you have Flutter installed on your machine. If not, follow the instructions on the [official Flutter website](https://flutter.dev/docs/get-started/install) to set it up.

4. Get Dependencies:
Run the following command in the project directory to fetch all the required dependencies:

5. Connect to Firebase:
Open the `android/app/build.gradle` file and ensure that the Firebase dependencies and configuration are correctly set up.

6. Run the App:
Connect a physical device or use an emulator, then run the app using the following command:

7. Test the App:
Verify that Firebase authentication, OTP verification, real-time database, and image storage are working as intended. Test the app's functionalities by sending and receiving messages and images.

