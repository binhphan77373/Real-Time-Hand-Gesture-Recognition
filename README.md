# Real-Time Hand Gesture Recognition

This project implements a real-time hand gesture recognition system using OpenCV and MediaPipe. The system can detect and classify various hand gestures including "Thumbs Up", "Thumbs Down", "Open Hand", "Fist", "Index Finger Up", "Peace Sign", "Rock Sign", and "OK Sign".

## Features

- Real-time hand tracking using a webcam.
- Gesture recognition with MediaPipe's Hand Landmark model.
- Display recognized gestures directly on the video feed.

## Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/binhphan77373/Real-Time-Hand-Gesture-Recognition.git
   cd Real-Time-Hand-Gesture-Recognition
   ```

2. Create a conda environment with Python 3.11:  
   ```bash
   conda create -n Real-Time-Hand-Gesture-Recognition python=3.11
   conda activate Real-Time-Hand-Gesture-Recognition
   ```

3. Install the required libraries:  
   ```bash
   pip install mediapipe opencv-python numpy
   ```

## Usage

1. Run the program:  
   ```bash
   python Real-Time-Hand-Gesture-Recognition.py
   ```

2. Allow access to your webcam.  
3. The video feed will display recognized hand gestures.  
4. Press the `q` key to exit the application.  

## Hand Gestures Recognized

- 👍 Thumbs Up
- 👎 Thumbs Down
- ✋ Open Hand
- ✊ Fist
- ☝️ Index Finger Up
- ✌️ Peace Sign
- 🤘 Rock Sign
- 👌 OK Sign

## Example

When the camera detects a "Thumbs Up" gesture, the screen will display "Thumbs Up" with a green label.
