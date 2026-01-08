🎯 Project Objective

The goal of this project is to build a user-friendly medication reminder system that ensures users take their medicines on time. The application simplifies medicine management using alerts, structured schedules, and progress tracking while demonstrating strong Android development practices.

✨ Key Features
🔐 User Authentication

Splash screen and welcome page

Login and signup with local validation

Secure user flow to dashboard

💊 Medicine Management

Add medicines with dosage, frequency, and time

View medicines using RecyclerView

Edit or delete medication details

Track daily medication progress

⏰ Smart Reminder System

Uses AlarmManager for scheduling alerts

Sends notifications even when the app is closed

Supports exact alarms and boot persistence

📊 History & Analysis

Stores medication history (taken / missed)

Visual analysis using charts (MPAndroidChart)

Helps users track adherence patterns

🚨 Emergency Call

One-tap emergency call feature

Quick access during critical situations

🛠️ Tech Stack
Category	Technology
Language	Kotlin
Database	SQLite
UI	XML, Material Design
Architecture	Activities + Adapters
Notifications	AlarmManager
Charts	MPAndroidChart
Networking	OkHttp
ML Support	TensorFlow Lite
IDE	Android Studio
Build Tool	Gradle (Kotlin DSL)
📂 Project Structure
SmartRemainder/
│
├── app/
│   ├── src/main/java/
│   │   ├── activities
│   │   ├── adapters
│   │   ├── database
│   │   ├── receivers
│   │   ├── viewmodel
│   │   └── ui
│   ├── res/
│   │   ├── layout
│   │   ├── drawable
│   │   ├── values
│   │   └── xml
│
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── AndroidManifest.xml

🔑 Permissions Used

Internet access

Post notifications

Exact alarm scheduling

Receive boot completed

External storage read

🚀 How to Run the Project

Clone the repository

git clone https://github.com/Laxmanredd/SmartRemainder.git


Open in Android Studio

Sync Gradle files

Run on emulator or physical device (Android 7.0+)

📈 Future Enhancements

Cloud sync using Firebase

Doctor & caregiver notifications

Voice-based reminders

AI-based medicine suggestions

Multi-language support

📜 License

This project is developed for academic purposes.
You are free to use and modify it for learning and non-commercial use.

🙌 Acknowledgements

Android Developers Documentation

MPAndroidChart Library

TensorFlow Lite Team

Faculty, SCSE
