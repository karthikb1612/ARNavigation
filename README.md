
QR-Based AR Indoor Navigation System
(Third Year Mini Project)

📌 Project Overview
The QR-Based AR Indoor Navigation System is an Augmented Reality application that helps users navigate indoor environments by displaying real-time AR directions over the camera view.
Users scan a QR code placed at their current location, select a destination, and follow AR-based arrows to reach the target.
The system works without GPS, making it suitable for indoor areas such as colleges, hospitals, malls, and offices.

🎯 Objectives
1. To provide accurate indoor navigation without GPS

2. To use QR codes for identifying user starting positions

3. To implement AR-based visual guidance

3. To calculate the shortest path using efficient algorithms

4. To build a user-friendly and intuitive interface

🚀 Key Features

📷 QR code–based location detection

🧭 Real-time AR navigation

📍 Any location can act as a starting point

🗺️ Shortest path calculation using A* algorithm

🎯 Step-by-step AR arrow guidance

📱 Simple camera-based navigation

🛠️ Technologies Used

Game Engine: Unity

AR SDK: Google ARCore

Programming Language: C#

Algorithm: A* (A-Star)

Tracking Method: SLAM (Simultaneous Localization and Mapping)

Platform: Android

🏗️ System Architecture
Camera Input
   ↓
QR Code Scanning
   ↓
User Position Identification
   ↓
Path Calculation (A*)
   ↓
AR Direction Rendering
   ↓
User Navigation

⚙️ Working Principle

1. QR codes are placed at important indoor locations.

2. The user scans a QR code using the mobile app.

3. The system identifies the user’s current position.

4. SLAM tracks the user’s movement in real time.

5. The A* algorithm calculates the shortest path.

6. AR arrows and animations guide the user to the destination.

🧪 Applications

🏫 College and university navigation

🏥 Hospital indoor guidance

🏢 Office buildings

🛍️ Shopping malls

🏛️ Museums and exhibitions

🖥️ Installation & Execution

Clone the repository:

git clone (https://github.com/karthikb1612/ARNavigation)


Open the project in Unity

Install ARCore XR Plugin

Connect an ARCore-supported Android device

Build and run the application

Scan a QR code to start navigation

📱 System Requirements

Android device with ARCore support

Camera permission enabled

Unity (LTS version recommended)

QR codes placed in the environment

🔮 Future Enhancements

Multi-floor indoor navigation

Voice-based guidance

Cloud-based QR management

Emergency evacuation routing

Admin dashboard for map control

🎓 Conclusion

This project successfully demonstrates how QR codes and Augmented Reality can be combined to provide an effective indoor navigation solution.
It eliminates GPS dependency and offers an intuitive navigation experience using real-time AR visualization.
