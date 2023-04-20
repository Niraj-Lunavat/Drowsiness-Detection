# Drowsiness Detection 😴 🚫 🚗

###### Made with ❤️ by [Niraj Lunavat](https://www.linkedin.com/in/nirajlunavat/)

### Description 📌
  We will be making a drowsiness detection system.Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy. The majority of accidents happen due to the drowsiness of the driver. Its computer vision system that can detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy. This code can detect your eyes and alert when the user is drowsy. 
  
#How it works

The system analyzes the video frames to detect facial landmarks and track eye movements and blinks. Based on these features, it estimates the driver's or user's level of drowsiness and triggers an alert if it detects signs of fatigue or inattention.

The system includes two main components:
1) Face detection and landmarks: This component uses a pre-trained Haar cascade classifier to detect the face region in each video frame. Then, it applies a facial landmarks detector to identify the key points in the face, such as the eyes, eyebrows, nose, and mouth.
2) Drowsiness detection: This component tracks the eye aspect ratio (EAR), which is a measure of how open or closed the eyes are. When the eyes close or blink, the EAR drops significantly, indicating drowsiness or fatigue. The system also measures the time between blinks and the duration of closed eyes to estimate the user's level of drowsiness.


  

### Code Requirements 🦄
The example code is in Python ([version 3.5](https://www.python.org/download/releases/3.5/) or higher will work). You can download a trained facial shape predictor from [here](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2). If you face any problem then raise an issue.

### Dependencies

1) OpenCV
2) Scipy
3) Imutils
4) Dlib

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 22 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

<img src="https://github.com/Niraj-Lunavat/Drowsiness-Detection/blob/main/eye1.jpg">


#### Relationship

<img src="https://github.com/Niraj-Lunavat/Drowsiness-Detection/blob/main/eye2.png">

#### Summing up

<img src="https://github.com/Niraj-Lunavat/Drowsiness-Detection/blob/main/eye3.jpg">


### Results 📊

<img src="https://github.com/Niraj-Lunavat/Drowsiness-Detection/blob/main/vid.gif">


### Execution 🐉
To run the code, type `python Drowsiness Detection.py`

## References
 
 - Adrian Rosebrock, [PyImageSearch Blog](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)
 - [Driver Drowsiness Detection System with OpenCV & Keras](https://data-flair.training/blogs/python-project-driver-drowsiness-detection-system/)
 - for Dataset, Checkout [Kaggle](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset)  
