# Headtracking
This is a python based headtracking system, and I am not giving a demo because I have to use my face so you download you test!(Change in plan I am providing a demo, but I am still keeping the html and css file in the repo )
# Head and Eye Tracking with OpenCV and Mediapipe

This project demonstrates real-time head and eye tracking using OpenCV and Mediapipe's Face Mesh module. The program captures video from the webcam, detects facial landmarks, and overlays mesh connections on the detected face and eyes.

## Features
- Detects and tracks facial landmarks in real time.
- Highlights the tessellation of the face and landmarks around the left and right eyes.
- Displays frames per second (FPS) on the video feed.
- User-friendly interface with live video feed.

## Requirements
The following dependencies are required to run the program:

- Python 3.7 or above
- OpenCV
- Mediapipe

You can install the required libraries using the following command:
```bash
pip install opencv-python mediapipe
```

## How to Run
1. Clone this repository or copy the script to your local machine.
2. Install the dependencies listed above.
3. Run the script using the following command:
```bash
python main.py
```

## Key Bindings
- **Press 'q'**: Quit the application.

## Code Overview
1. **Initialization**: The program initializes Mediapipe's Face Mesh and OpenCV's video capture.
2. **Real-Time Processing**: Captures frames from the webcam and processes them to detect facial landmarks.
3. **Drawing Landmarks**: Uses Mediapipe's drawing utilities to overlay the facial tessellation and eye landmarks.
4. **FPS Calculation**: Calculates and displays the frame rate for real-time performance monitoring.
5. **Quit**: Allows the user to quit the program by pressing 'q'.

## Sample Output
When running the program, you will see a live video feed with:
- A face mesh overlay on the detected face.
- Highlighted areas around the left and right eyes.
- FPS displayed on the top-left corner of the feed.

## Troubleshooting
- If the webcam feed does not appear, ensure that your webcam is properly connected and accessible.
- Ensure all dependencies are installed correctly.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute it as long as the original copyright is included.

---

Feel free to modify and expand this project to add additional features such as:
- Facial expression recognition
- Eye gaze estimation
- Integration with other vision-based applications

Enjoy exploring the possibilities of real-time face and eye tracking!

