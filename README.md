# Threads Clone
This project is a clone of Threads by Instagram, a social media app built for Android using the following technologies:

* **Kotlin:** A modern, concise, and safe programming language for Android development.
* **Jetpack Compose:** A modern toolkit for building native UI on Android.
* **Firebase:** A suite of tools for app development, including Firebase Authentication, Firestore, and Cloud Messaging.
* **Android Studio:** The official IDE for Android development.

## Features:

### User Authentication:
User registration with email and password.
Email verification for enhanced security.
Secure user login.
### Thread Creation and Viewing:
Create new threads with text and images.
View threads created by other users.
Interact with threads through likes and comments.
### Following and Followers:
Follow other users and view their threads.
Manage your followers list.
### User Profiles:
View and manage user profiles.
Display user information and content.
### User List:
Discover new users to follow.
### Real-time Updates:
Real-time updates for new threads, comments, and followers using Firebase.

## Getting Started

### Clone the repository:

Bash
git clone https://github.com/Rishi2419/Threads-Clone/tree/main

### Set up the development environment:

Install Android Studio: Download and install the latest version of Android Studio.<br>
Install Firebase dependencies: Add the necessary Firebase dependencies to your build.gradle file:

Gradle

dependencies {<br>
    // ... other dependencies<br>
    implementation 'com.google.firebase:firebase-auth-ktx'<br>
    implementation 'com.google.firebase:firebase-firestore-ktx'<br>
    // ... other dependencies<br>
}<br>

### Connect to Firebase:
Create a Firebase project in the Firebase console.<br>
Add your Android app to the Firebase project.<br>
Download the google-services.json file and place it in the app/ directory of your project.<br>


### For a visual walkthrough of Threads functionalities, check out the demo video here:
https://www.linkedin.com/posts/rishikesh-sahu-error_androiddevelopment-kotlin-jetpackcompose-activity-7230920596262420480-q8Ik?utm_source=share&utm_medium=member_desktop


