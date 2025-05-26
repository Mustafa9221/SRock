# S.Rocks.Music - Music Services

This Flutter project is a mini music services module as part of the Flutter Developer Intern assignment for S.Rocks.Music.

---

## Project Overview

This app recreates the **Home Screen** of the S.Rocks.Music app, showcasing multiple music service cards. Each card dynamically loads its data (title, description, and icon) from Firebase Firestore and navigates to a detail screen on tap.

The project demonstrates:

- Responsive UI design in Flutter based on the provided Figma design
- Integration with Firebase Firestore to fetch and display service data dynamically
- State management using Provider
- Implementation of MVVM architecture to separate UI, business logic, and data access
- Flutter navigation for screen transitions

---

## Features

- Responsive service cards with icon, title, and description
- Data fetched asynchronously from Firebase Firestore (read-only)
- Clean code structure following MVVM pattern
- State management with Provider package
- Simple navigation to detail screens showing tapped service title

---


---

## How to Run

1. Clone the repository  
2. Run `flutter pub get` to install dependencies  
3. Set up your Firebase project and add the configuration files (google-services.json / GoogleService-Info.plist)  
4. Run `flutter run` to launch the app

---

## Dependencies

- Flutter SDK  
- provider (for state management)  
- cloud_firestore (for Firebase Firestore integration)  
- firebase_core (Firebase initialization)

---

## Learning Outcomes

Throughout this assignment, I have gained valuable experience in:

- Building responsive Flutter UIs matching design specs  
- Integrating Firebase Firestore and handling asynchronous data  
- Structuring Flutter apps using MVVM architecture  
- Managing app state efficiently with Provider  
- Implementing navigation and user interaction  

---

## Additional Notes

- This project strictly uses read-only Firestore access to fetch service data.  
- The navigation targets simple screens displaying the tapped service name to demonstrate basic navigation skills.  
- Optional bonus features like dependency injection were not implemented in this version.

---

Thank you for reviewing my submission!

---

*Link to the GitHub repository:*  
https://github.com/Mustafa9221/SRock

*Link to screen recording of the final output:*  
https://drive.google.com/file/d/16mxyXa7y8ASburO67mRA-B6uCv1cyC88/view?usp=drivesdk


