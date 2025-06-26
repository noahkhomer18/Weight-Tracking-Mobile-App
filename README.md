# 📱 Weight Tracking Mobile App – CS 360 Portfolio Submission

## 📦 Project Files
This repository contains my final app code design for the mobile application developed in CS 360. Included in the ZIP file is:
- The completed Android Studio project (Java-based)
- The UI screens originally planned in Project Two
- Functional features added during Project Three
- Optional: My app launch plan

This project showcases my ability to design and develop a fully functional mobile app, following user-centered design and best practices in mobile development.

---

## 🧠 Reflection

### What were the requirements and goals of the app?
The goal of this app was to help users track their body weight over time. It lets users enter their weight along with a date and phone number, with the option to receive SMS notifications. The core idea was to make it simple, clean, and easy to monitor progress toward weight goals.

### What user needs was this app designed to address?
This app helps people stay accountable and motivated in their fitness or health journey. It was designed for users who want a lightweight and focused tool to track weight data, set goals, and receive reminders.

### What screens and features were necessary to support those needs?
The app included:
- A **Login/Register screen** to create or access an account
- A **Weight Entry screen** where users can input their weight and date
- A **Display screen** to view previous entries
- SMS permissions and a basic layout focused on readability and accessibility

The UI was kept minimal and straightforward so users wouldn’t feel overwhelmed. Input fields were labeled clearly, and button placements were intuitive for mobile use.

### How did I approach coding the app?
I broke down the app into logical parts: authentication, data input, storage, and display. I used Java with Android Studio, relying on modular methods and frequent testing after every change. I constantly ran the app on an emulator to preview behavior in real-time.

### What strategies helped during development?
Consistent use of layout constraints, separating logic by activity, and reusing UI components kept the project organized. Using simple Toast messages and logcat helped with debugging. These techniques are useful in any future app, especially for maintaining a clean architecture.

### How did I test functionality?
I tested the app after every feature was implemented, checking UI alignment, form validation, and navigation between screens. I also tested invalid inputs and edge cases to prevent crashes. This testing helped me find hidden bugs early and made the final product more stable.

### Where did I have to innovate to overcome a challenge?
Handling the user weight display required me to adjust how data was passed between activities. Initially, the entries weren’t showing up properly until I added better data validation and restructured the way I saved user input. I also had to manage the SMS permission in a way that wouldn’t crash the app if denied.

### What component best reflects my skills and knowledge?
The **user interface design** and **weight entry logic** showcase my skills best. I took the original sketches and implemented them accurately, improving the flow while staying true to a user-first experience. The way I structured the weight entry screen made the app feel both functional and visually balanced.
