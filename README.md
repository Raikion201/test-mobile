Collecting workspace information# TO-DO Notes - Testing Codelab

## Overview
A task management Android application that showcases testing best practices. This app allows users to create, organize, and track tasks with a clean, material design interface, demonstrating various Android architecture components and testing techniques.

## Features
- Create, edit and delete tasks
- Mark tasks as complete or active
- Filter tasks by their status (all, active, completed)
- View task statistics
- View detailed information about specific tasks
- Data persistence through Room database
- Clean architecture with separation of concerns


## Technologies Used
- Kotlin
- Android Architecture Components
- MVVM Design Pattern
- LiveData and ViewModel
- Navigation Component
- Data Binding
- Room Database
- Coroutines for asynchronous operations
- JUnit and Espresso for testing

## Prerequisites
- Android Studio Hedgehog (2023.1.1) or newer
- Android SDK version 21+
- Gradle 8.2+
- JDK 17+ (with Java 21 tools support)
- AndroidX libraries

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/googlecodelabs/android-testing.git
cd android-testing
```

### Open and Build in Android Studio
1. Open Android Studio
2. Select "Open an existing Android Studio project"
3. Navigate to the cloned repository and click "Open"
4. Wait for the project to sync and build
5. Connect an Android device or use the emulator

### Run the Application
- Click the "Run" button in Android Studio
- Select a deployment target
- The app will install and launch automatically

## Project Structure
```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/android/architecture/blueprints/todoapp/
│   │   │   ├── data/                  # Data models and source classes
│   │   │   ├── tasks/                 # Task list screen
│   │   │   ├── taskdetail/            # Task detail screen
│   │   │   ├── addedittask/           # Add/edit task screen
│   │   │   ├── statistics/            # Statistics screen
│   │   │   └── util/                  # Utility classes
│   │   ├── res/                       # App resources
│   │   └── AndroidManifest.xml        # App configuration
│   ├── test/                          # Local unit tests
│   └── androidTest/                   # Instrumented tests
├── build.gradle                       # Project build configuration
└── gradle.properties                  # Gradle configuration properties
```

## Testing Approach
This project demonstrates different testing techniques:
- **Unit tests**: Test individual components in isolation
- **Integration tests**: Test interactions between components
- **UI tests**: Test the app's user interface with Espresso

The codelabs in this series are:
* [Testing Basics](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-basics)
* [Introduction to Test Doubles and Dependency Injection](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-test-doubles)
* [Survey of Testing Topics](https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-testing-survey)


## Contributing
Please read CONTRIBUTING.md for details on how to contribute to this project.

---
*This app is part of the Android Developers Codelabs and demonstrates modern Android development techniques with a focus on testable architecture.*

Similar code found with 1 license type
