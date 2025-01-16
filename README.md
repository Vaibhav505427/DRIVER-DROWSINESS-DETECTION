STEP 1 :
DOWNLOAD the importanat libraries that is :
1. OpenCV (cv2)
OpenCV is used for image processing and handling the webcam feed.
Installation: pip install opencv-python
Optional (for additional features like non-free algorithms): pip install opencv-contrib-python
2. MediaPipe
MediaPipe is used for real-time face landmark detection, which is essential for detecting facial features like eyes and lips.
Installation: pip install mediapipe
3. NumPy
NumPy is used for numerical operations and handling arrays. It's also used to handle the face landmarks as arrays of coordinates.
Installation: pip install numpy
4. SciPy
SciPy's distance module is used to compute Euclidean distances, which are essential for calculating the Eye Aspect Ratio (EAR) and lip distance.
Installation: pip install scipy
5. Pygame
Pygame is used for sound playback (in this case, for yawning and drowsiness detection alerts).
Installation: pip install pygame

Installation Summary:
You can install all the necessary libraries using the following pip commands: pip install opencv-python mediapipe numpy scipy pygame

STEP 2 :
Download the attached sound files and paste them on the desktop

STEP 3 :
Replace the sound file location with the current path of the sound files
