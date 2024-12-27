# Bicep-Curl-Counter

# Overview <br>
This project is a bicep curl counter application developed using Python. It utilizes OpenCV for video processing and Mediapipe for real-time pose detection, providing an efficient way to track and count bicep curls during workouts. <br> <br>

# Features <br>
* Real-time bicep curl detection.
* Accurate joint tracking using Mediapipe's pose estimation.
* Visual feedback on form and motion.<br>

# Technologies Used
### Python: Core programming language.
###  OpenCV: For video frame capture and processing.
### Mediapipe: For human pose detection and landmark tracking.<br>
## How It Works
* The system captures live video using OpenCV.
* Mediapipe's pose estimation model tracks the arm's position and angle.
* The application calculates the elbow's angle to determine the start and completion of a curl.
* It counts the curls and provides visual feedback to ensure proper form.
<br>
## Usage
* Position yourself within the camera's frame.
* Start performing bicep curls, and the counter will automatically track and display the count.
