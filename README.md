**Player Performance Analysis Using Computer-Vision & Deep Learning**<br>
Python software is integrated into a camera. As the camera records a live feed, the software analyzes player performance based  on the pre-set parameters. The list of parameters that will determine players' performance.
Python software is integrated into a camera. As the camera records live feed, the software will analyze player performance based
#on the pre-set parameters. The project is in the developing phase, therefore there are fewer parameters defined. But in the future, the list will be expanded to #meet the requirements of each game to analyze players. For now, for testing purposes, this project will measure the running speed of the players, the force #applied to kick/throw the ball or other materials like Javellion depending on the game:
1. Running Speed: calculated using the formula distance/time. The average speed is calculated once the game is over, and the formula to calculate
#average speed: is the sum of instances of speeds in the game/number of instances
2. Force=mass*acceleration

**Required installations** <br>
i. Live camera feed, image/frame processing -->
**!pip install opencv-python**

ii. OLOv8 object detection (players/ball)  -->
**!pip install ultralytics**

iii. Mathematical calculations for speed, distance, etc.  -->
**!pip install numpy**

iv. For pose estimation later  -->
**!pip install --user mediapipe**

v. Plotting visual analytics  -->
**!pip install matplotlib pandas**

**Verify Installation**<br>
**import cv2** <br>
print("OpenCV version:", cv2.__version__) <br>
**Expected output:** OpenCV version: 4.11.0 --> version may be different<br>

**import numpy as np**<br>
print("NumPy version:", np.__version__)<br>
#Expected output: NumPy version: 1.26.4 --> version may not same<br>

**import matplotlib.pyplot as plt**<br>
print("Matplotlib is ready.")<br>
#Expected output: Matplotlib is ready.<br>

**import pandas as pd**<br>
print("Pandas version:", pd.__version__)<br>
#Expected output: Pandas version: 2.2.2 --> version may not same<br>

**import torch**<br>
print(torch.__version__)<br>
print("torch.load exists:", hasattr(torch, 'load'))<br>
#Expected output: '2.6.0+cpu<br>
#torch.load exists: True'<br>

**from ultralytics import YOLO**<br>
print("Ultralytics (YOLOv8) is installed.")<br>
#Expected output: Ultralytics (YOLOv8) is installed.<br>

**import mediapipe as mp**<br>
print("MediaPipe is now working!")<br>
#Expected output: MediaPipe is now working!<br>

Once the environmnet is setup and necessary libraries are installed, go to<a href="https://github.com/Nirmal8103/Player-Performance-Analysis/commit/73fe9484c8d36e5e157591261df1f02601e2ffe0"> Main_Code </a>file to find the pyhton code to analyze player performance.
