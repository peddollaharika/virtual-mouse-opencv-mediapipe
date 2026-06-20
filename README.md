# virtual-mouse-opencv-mediapipe
📌 **Project Overview**

AI Virtual Mouse is a Computer Vision project that enables users to control mouse operations using hand gestures detected through a webcam. The system leverages MediaPipe Hand Tracking and OpenCV to recognize finger movements and perform various mouse actions without requiring a physical mouse.

The project also includes a Streamlit dashboard for displaying captured frames, recorded videos, project statistics, and workflow information.

🚀 **Live Demo**

Try the application here:

https://virtual-mouse-opencv-mediapipe-fd5jzqbqtmqf8dz6ydefpx.streamlit.app/

Note: The online demo showcases project information, captured frames, and recorded videos. Full mouse control functionality is available when the project is executed locally.

**🎯 Objectives**
Control mouse operations using hand gestures.
Perform cursor movement without a physical mouse.
Implement gesture-based clicking and scrolling.
Demonstrate real-time hand tracking using Computer Vision.
Create an interactive dashboard for monitoring project outputs.

**🛠️ Technologies Used**
Python
OpenCV
MediaPipe
NumPy
PyAutoGUI
Streamlit

✨ Features

✔ Real-Time Hand Tracking

✔ Cursor Control using Index Finger

✔ Left Click Gesture

✔ Right Click Gesture

✔ Drag and Drop Gesture

✔ Scroll Gesture

✔ Frame Capture and Storage

✔ Video Recording

✔ Interactive Streamlit Dashboard

✔ Modular Project Architecture

👋 Supported Gestures
Gesture	Action
👉 Index Finger	Cursor Movement
👌 Thumb + Index Finger	Left Click
👍 Thumb + Middle Finger	Right Click
🤏 Thumb + Ring Finger	Drag and Drop
✌ Index + Middle Finger	Scroll

🔄 **Project Workflow**
**Step 1:** Capture Webcam Feed

The webcam continuously captures live video frames.

**Step 2:** Frame Preprocessing
Resize Frames
Flip Frames
Noise Reduction

**Step 3:** Hand Detection

MediaPipe detects hand landmarks in real time.

**Step 4:** Gesture Recognition

Finger positions are analyzed to identify gestures.

**Step 5:** Mouse Control

Recognized gestures trigger:
Cursor Movement
Left Click
Right Click
Drag and Drop
Scrolling

**Step 6:** Frame Capture

Important frames are saved automatically.

**Step 7:** Video Recording

User sessions can be recorded and stored.

**Step 8:** Dashboard Visualization

Captured frames, videos, and project statistics are displayed using Streamlit.

📊 **Dashboard Features**

The Streamlit dashboard provides:

Project Overview
Gesture Information
Workflow Explanation
Latest Captured Frame
Recorded Videos
Project Statistics
Feature Summary

🌟 **Applications**
Touchless Computer Interaction
Smart Classrooms
Accessibility Solutions
Public Kiosks
Interactive Presentations
Healthcare Environments
Human-Computer Interaction Research

🔮 **Future Enhancements**
Multi-Hand Support
Custom Gesture Creation
Voice Command Integration
AI-Based Gesture Classification
Cross-Platform Optimization
Cloud-Based Analytics

👩‍💻 **Author**

Peddolla Harika

Aspiring Data Scientist | Machine Learning Enthusiast | Computer Vision Developer

⭐ Support

If you found this project useful, please consider giving it a star ⭐ on GitHub.
