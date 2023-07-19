# FaceRecognition
This project implements a face recognition system using OpenCV and face_recognition libraries. It allows you to encode and recognize faces from a set of images using a webcam or video feed.

# Prerequisites

Before running the project, make sure you have the following prerequisites:

1. Python 3.x
2. OpenCV library (pip install opencv-python)
3. face_recognition library (pip install face_recognition)


# Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies by running pip install -r requirements.txt in your project directory.
3. Prepare a folder containing images of faces that you want to recognize. Ensure that each image contains only one face.
4. Update the main.py file with the correct camera index and the path to the images folder.
5. Run the project by executing python main.py in the project directory.
6. The webcam feed will open, and the program will attempt to recognize faces based on the provided images.

# Project Structure

The project consists of the following files:

main.py: The main script that captures frames from the camera, detects and recognizes faces.
simple_facerec.py: A helper module that provides face encoding, loading of encoding images, and face detection functions.
images/: A folder containing the images used for face encoding and recognition.

# Customization

You can customize the resizing factor used in the face recognition process by adjusting the frame_resizing variable in simple_facerec.py.
To recognize more faces, simply add images of the additional faces to the images/ folder and run the project again.
Feel free to modify and extend the code to suit your specific requirements.

# Troubleshooting

If you encounter issues with the camera not being found or frames not being read properly, make sure the camera is connected, the correct camera index is used, and the camera drivers are up to date.

# Acknowledgments

This project utilizes the following libraries:

OpenCV: https://opencv.org/
face_recognition: https://github.com/ageitgey/face_recognition

# Contributing
Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests.

# Contact
Feel free to contact for any inquiries or feedback