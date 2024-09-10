Visual-Tracker-and-Classifier

Visual Tracker and Classifier Using Linear Regression

This project implements a real-time Visual Tracker and Classifier leveraging linear regression techniques. It is designed to identify, track, and classify objects within a video stream based on their visual features. The system is optimized for simplicity and performance, using techniques like grayscale conversion and edge detection to enhance recognition.
Features

    Real-time Object Tracking
    Efficiently tracks objects within video frames using a robust algorithm that ensures smooth tracking even in dynamic environments.

    Object Classification
    Classifies tracked objects into predefined categories using linear regression, enabling simple yet effective categorization based on visual data.

    Grayscale Conversion
    Converts video frames to grayscale to reduce complexity and processing time, while maintaining accuracy.

    Edge Detection
    Enhances object recognition by utilizing edge detection techniques, improving the accuracy of object boundaries and shapes.

Installation

To get started with the project, follow these steps:

Clone the repository:

    bash

    git clone https://github.com/CraigChantre/visual-tracker-classifier.git
    cd visual-tracker-classifier

Install the required dependencies:

Make sure you have Python installed, then run:

    bash

    pip install -r requirements.txt

Usage

To start the visual tracker and classifier, simply run the main script:

    bash

    python main.py

Options:

Webcam Usage: Ensure that your webcam is connected. By default, the system will use your webcam for object tracking.
Using Video File: If you'd prefer to use a pre-recorded video, modify the script by replacing the webcam stream with a video file path.

# Example: Modify the video source in main.py
    video = cv2.VideoCapture("path_to_video.mp4")


Upon running the script, the system will:

    Display video frames in real-time, with tracked objects highlighted.
    Output classified objects with their respective labels on the screen.

Future Enhancements

    Implement more advanced classification models such as SVM or deep learning-based classifiers.
    Support multi-object tracking for enhanced performance in complex scenes.
    Improve performance on resource-limited devices through optimizations.
