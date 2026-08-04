# 👨‍💻 Face Recognition Attendance System (Java)

## 📌 Overview

The Face Recognition Attendance System is an AI-based Java application that automatically detects faces using a webcam and records attendance with date and time. The project uses OpenCV for face detection and demonstrates the use of computer vision in attendance automation.

## ✨ Features

- 📷 Real-time face detection using webcam
- 🤖 Automated attendance marking
- 🕒 Records date and time of attendance
- 📄 Stores attendance in CSV file
- ⚡ Fast and simple attendance management
- 🖥️ Reduces manual attendance work

## 🛠️ Technologies Used

- Java
- OpenCV
- Haar Cascade Classifier
- Computer Vision
- File Handling

## 📂 Project Structure

```
Face-Recognition-Attendance-System/
│
├── FaceRecognitionAttendance.java
├── haarcascade_frontalface_default.xml
├── attendance.csv
└── README.md
```

## ⚙️ Requirements

- Java JDK 8 or above
- OpenCV Library for Java
- Webcam
- Java IDE:
  - IntelliJ IDEA
  - Eclipse
  - VS Code
  - NetBeans

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/face-recognition-attendance-system.git
```

### 2. Configure OpenCV

- Install OpenCV for Java.
- Add OpenCV dependencies to your project.
- Add the Haar Cascade XML file:

```
haarcascade_frontalface_default.xml
```

### 3. Compile the Program

```bash
javac FaceRecognitionAttendance.java
```

### 4. Run the Application

```bash
java FaceRecognitionAttendance
```

## 📸 Sample Output

```
Face Recognition Attendance Started...

Face Detected!

Attendance Marked Successfully!
```

### Attendance File Example

`attendance.csv`

```
Name,Date-Time
Student,2026-08-04T13:45:20
```

## 🔮 Future Enhancements

- Add face recognition for multiple users
- Store attendance using MySQL database
- Create GUI using Java Swing/JavaFX
- Add admin login system
- Generate attendance reports
- Improve recognition accuracy using deep learning models

## 👨‍💻 Author

Neha

## 📄 License

This project is licensed under the MIT License.
