
# Real-Time Face Detection and Recognition

## Overview

This project showcases a real-time face detection and recognition system using Python with the `face_recognition` and `opencv-python` libraries. The system captures live video from a webcam, detects faces in the video feed, and matches these faces against a set of known individuals. Detected faces are highlighted with rectangles and labeled with names.

## Features

- **Real-Time Face Detection**: Detects faces in live video frames from a webcam.
- **Face Recognition**: Identifies and labels known individuals from the video feed.
- **Dynamic Face Management**: Update known faces and their encodings by modifying image files and updating the script.

## Setup

### Prerequisites

Ensure Python is installed on your system. Install the following libraries:

- `opencv-python` for video capture and image processing.
- `face_recognition` for face detection and recognition.

Install these libraries using pip:
pip install opencv-python face_recognition
### Image Files
Place images of known individuals in a directory and update the file paths in the script. The current images used are:

saif pic.jpg
papa.jpg
sami.jpg
saad.jpg
Update the paths in the script to match your directory structure.

### Usage
Connect Your Webcam: Ensure your webcam is connected to your computer.

Update File Paths: Verify that the paths to the image files in the script are correct.

Run the Script: Execute the following command to start the face detection and recognition:


python face_detection.py
Exit the Program: Press the 'q' key to stop the video feed and close the application.

### Example
Clone the repository to get started:

git clone https://github.com/saifullahkhanjadoon/real-time-face-detection.git
Navigate to the project directory:

cd real-time-face-detection
Run the script:



python face_detection.py
### Future Enhancements
Improved Accuracy: Implement advanced algorithms or deep learning models for better face recognition accuracy.
Database Integration: Connect to a database to manage and update known faces dynamically.
GUI Development: Create a graphical user interface for easier interaction and additional features.
