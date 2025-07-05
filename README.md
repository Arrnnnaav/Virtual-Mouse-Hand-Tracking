#  Virtual Mouse Using Hand Tracking (OpenCV + MediaPipe + Autopy)

Control your computer mouse cursor using hand gestures via webcam using OpenCV, MediaPipe, and Autopy in Python.

---

##  Features
- Control mouse movement using index finger
- Perform left click by bringing index and middle fingers close
- Smooth and accurate cursor control
- Adjustable frame reduction and smoothing parameters
- Real-time FPS display

---

##  Technologies Used
- [OpenCV](https://opencv.org/) – for video capturing and drawing
- [MediaPipe](https://google.github.io/mediapipe/) – for hand landmark detection
- [Autopy](https://pypi.org/project/autopy/) – for controlling the mouse cursor
- [NumPy](https://numpy.org/) – for interpolation and numerical operations

---

##  How it Works

1. The webcam feed is processed in real-time.
2. Hand landmarks are detected using `HandTrackingModule` built on MediaPipe.
3. If only the index finger is up, the pointer moves according to finger position.
4. If both index and middle fingers are up and close together, a mouse click is triggered.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Virtual-Mouse-Hand-Tracking.git
   cd Virtual-Mouse-Hand-Tracking
