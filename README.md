# servo-motor-control-using-handgesture
Servo Motor Control Using Hand Gestures
Overview
This project enables control of a servo motor using hand gestures detected by a camera. The system uses MediaPipe for hand gesture recognition and PyFirmata to interface with an Arduino to control the servo motor based on detected gestures.

Features
Hand Gesture Detection: Recognizes hand gestures using MediaPipe.
Servo Motor Control: Adjusts the position of a servo motor based on hand gestures.
Real-time Video Processing: Processes video feed in real-time to detect gestures and control the motor.
Visual Feedback: Displays hand landmarks and gesture-based motor control in a video window.
Requirements
Python 3.x
OpenCV
NumPy
MediaPipe
PyFirmata2
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/Rohan3177/servo-motor-control-using-handgesture.git
Navigate to the Project Directory

bash
Copy code
cd servo-motor-control-using-handgesture
Install Required Libraries

Create a virtual environment (optional but recommended) and install the dependencies:

bash
Copy code
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install opencv-python numpy mediapipe pyfirmata2
Setup Arduino

Connect the Arduino board to your computer.
Ensure the pyfirmata2 library is properly configured to communicate with your board.
Update the COM3 port in the code to match the port your Arduino is connected to.
