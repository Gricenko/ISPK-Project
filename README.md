# ISPK-Project

A Java-based Android application project developed as part of academic study in software engineering and mobile application development.

## Overview

This repository contains a simple Android application built with Java and Gradle. It demonstrates a typical Android project structure, including multiple activities, UI layouts, and app configuration for a basic mobile application prototype.

## Tech Stack

- Java
- Android SDK
- AndroidX
- Gradle
- Material Components

## Features

- Android application structure with a standard Gradle setup
- Multiple activity screens for simple app navigation
- Basic UI implementation using Android components
- App configuration and package structure based on standard Android project conventions

## Project Structure

```text
.
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   ├── androidTest/
│   │   └── test/
│   ├── build.gradle
│   └── proguard-rules.pro
├── build.gradle
├── gradlew
├── gradlew.bat
├── settings.gradle
├── README.md
├── .gitignore
└── gradle/
```

## Setup

Requirements:
- Android Studio
- JDK
- Android SDK

1. Open the project in Android Studio.
2. Let Gradle sync the project.
3. Ensure the Android SDK is installed and configured.

## Run

```bash
./gradlew assembleDebug
```

Then run the application in an emulator or on a connected Android device.

## Notes

- This project is best understood as an academic and learning-oriented Android application.
- It demonstrates fundamentals of Android app structure and Java-based mobile development.
- The project can be expanded with improved architecture, navigation flows, data handling, and cleaner separation of responsibilities.
