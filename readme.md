# Drowsiness Detection 😴 🚫 🚗

###### Made with ❤️ by [Niraj Lunavat](https://www.linkedin.com/in/nirajlunavat/)

### Description 📌
  We will be making a drowsiness detection system.Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy. The majority of accidents happen due to the drowsiness of the driver. Its computer vision system that can detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy. This code can detect your eyes and alert when the user is drowsy. 

### Code Requirements 🦄
The example code is in Python ([version 3.5](https://www.python.org/download/releases/3.5/) or higher will work). 

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


For more information, [see this blog](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/) and [this blog](https://data-flair.training/blogs/python-project-driver-drowsiness-detection-system/)

### Results 📊

<img src="">


### Execution 🐉
To run the code, type `python Drowsiness Detection.py`

```
python Drowsiness Detection.py
```


## References 🔱
 
 -   Adrian Rosebrock, [PyImageSearch Blog](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)
 -  [Driver Drowsiness Detection System with OpenCV & Keras](https://data-flair.training/blogs/python-project-driver-drowsiness-detection-system/)

 - for Dataset, Checkout [Kaggle] (https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset)  
