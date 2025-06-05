# ColorDetection

This Python project captures live video from your webcam and uses OpenCV to detect the color red in real time. It applies HSV (Hue, Saturation, Value) color space filtering to isolate red regions in the frame and display them separately.

🔧 Features
- Real-time video capture using cv2.VideoCapture

- HSV color space conversion for robust color detection

- Binary masking to filter red pixels in the frame

- Visual output showing both:

- Original video feed

- Isolated red-colored areas

🎯 How It Works
- Convert the webcam frame from BGR to HSV color space.

- Define HSV boundaries for the red color.

- Use cv2.inRange() to create a mask that highlights red areas.

- Apply the mask on the original frame using cv2.bitwise_and().

- Display both the original and red-detected frames in real time.

🛠️ Requirements
- Python 3.x

- OpenCV (pip install opencv-python)

- Numpy (pip install numpy)

🚀 Run the Script

_python red_detection.py_
Press q to exit the application.

