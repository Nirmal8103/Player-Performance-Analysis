**Player-Performance-Analysis**
Python software is integrated into a camera. As the camera records a live feed, the software analyzes player performance based  on the pre-set parameters. The list of parameters that will determine players' performance.

#Core computer-vision & deep learning
#Name of the project: Player Performance Analysis Using Computer-Vision & Deep Learning
#Brief Background: Python software is integrated into a camera. As the camera records live feed, the software will analyze player performance based
#on the pre-set parameters. The project is in the developing phase, therefore there are fewer parameters defined. But in the future, the list will be expanded to #meet the requirements of each game to analyze players. For now, for testing purposes, this project will measure the running speed of the players, the force #applied to kick/throw the ball or other materials like Javellion depending on the game:
#1. Running Speed: calculated using the formula distance/time. The average speed is calculated once the game is over, and the formula to calculate
#average speed: is the sum of instances of speeds in the game/number of instances
#2. Force=mass*acceleration

**#Required installations**
#!pip install opencv-python
#!pip install ultralytics

# For array operations 
#!pip install numpy

# For pose estimation later
#!pip install --user mediapipe

# TO Display real-time charts or logging
#!pip install matplotlib pandas

**#Verify Installation**
#import cv2
#print("OpenCV version:", cv2.__version__) 
#Expected output: OpenCV version: 4.11.0 --> version may not same

#import numpy as np
#print("NumPy version:", np.__version__)
#Expected output: NumPy version: 1.26.4 --> version may not same

#import matplotlib.pyplot as plt
#print("Matplotlib is ready.")
#Expected output: Matplotlib is ready.

#import pandas as pd
#print("Pandas version:", pd.__version__)
#Expected output: Pandas version: 2.2.2 --> version may not same

#import torch
#print(torch.__version__)
#print("torch.load exists:", hasattr(torch, 'load'))
#Expected output: '2.6.0+cpu
#torch.load exists: True'

#from ultralytics import YOLO
#print("Ultralytics (YOLOv8) is installed.")
#Expected output: Ultralytics (YOLOv8) is installed.

#import mediapipe as mp
#print("MediaPipe is now working!")
#Expected output: MediaPipe is now working!
