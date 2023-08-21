# Computer_Vision_Hand_Detection
Using computer vision to detect right hand, left hand or both hands

## Where to find the tutorial - Right and Left Hand Detection Using Python
You can find tutorial for this project on [GeeksForGeeks](https://www.geeksforgeeks.org/right-and-left-hand-detection-using-python/) 
— Note: Please review the file I uploaded because this tutorial gives you an error on line 49.

## Introduction
```
pip install mediapipe  
pip install opencv-python
```
# Importing Libraries
```
import cv2
import mediapipe as mp
from google.protobuf.json_format import MessageToDict
```

— These lines import the necessary libraries for the project.
cv2 is OpenCV, a powerful library for computer vision tasks.
mediapipe is a library that offers various pre-built solutions for media processing tasks.
MessageToDict is a function from google.protobuf.json_format used to convert protobuf messages to dictionaries.

## How It Works
![](images/left_hand.png)
![](images/right_hand.png)
![](images/both_hands.png)

## Notes
Remember to press "q" to close the application.
