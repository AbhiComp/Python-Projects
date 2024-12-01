Yoga Steps Detection and Prediction System

This project involves a computer vision-based application that identifies yoga poses in real-time using a webcam. Built with Python, Machine Learning, and SQLite DB3, the system is designed to help yoga practitioners monitor their poses and improve their practice while allowing instructors to provide personalized feedback.

Abstract
Yoga is a widely practiced discipline combining body postures and breathing exercises for physical and mental well-being. This system detects and predicts eight yoga poses—Bhadrasan, Shavasan, Gomukhasan, Vajrasan, Sarvangasan, Shirsansan, Chakrasan, and Dhanurasan—in real-time.

Key Features:
Dataset Preparation: Collected and annotated 501 virtual body and face coordinates for each pose. Data was normalized and split into training and testing sets.
Model Development: Used OpenCV and MediaPipe to extract features and train the model, achieving an average accuracy of 95%.
Real-Time Detection: Captures live webcam video, extracts coordinates, and predicts yoga poses with real-time feedback on the screen.
User Management: Integrated a user registration and login system using tkinter and SQLite for secure access.
Applications:
- Practitioners can monitor and enhance their poses.
- Instructors can provide personalized guidance and feedback.
- Future enhancements include expanding the dataset to include additional yoga poses and integrating advanced feedback mechanisms to further improve accuracy.

Table of Contents
Technologies Used
Features
Future Enhancements

Technologies Used
The system was developed using:
Python
Machine Learning (Logistic Regression)
OpenCV and MediaPipe (for computer vision)
SQLite DB3 (for user management)
tkinter (for the GUI)

Features
Real-Time Pose Detection:
Detects and identifies eight yoga poses with 95% accuracy.
Displays pose name and prediction accuracy on the screen.

User Authentication:
Secure registration and login system with SQLite integration.
Stores user data for personalized access.

Easy-to-Use Interface:
Simple GUI for interacting with the system.
Real-time webcam feed for instant feedback.

Future Enhancements
Expand the dataset to include more yoga poses.
Implement advanced feedback mechanisms for posture correction.
Explore integration with wearable devices for additional data points.

Keywords
Deep Learning, Yoga Steps, Logistic Regression, Computer Vision, Pose Detection.
