# Drowsiness Detection OpenCV 😴 🚫 🚗

###### Made with ❤️ by [Niraj Lunavat](https://www.linkedin.com/in/nirajlunavat/)

### Description 📌

 Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. Its computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy. This code can easily detect your eyes and alert when the user is drowsy. 

### Applications 🎯
This can be used by riders who tend to drive for a longer period of time that may lead to accidents

### Code Requirements 🦄
The example code is in Python ([version 3.5](https://www.python.org/download/releases/3.5/) or higher will work). 

### Dependencies

1) OpenCV
2) Imutils
3) Dlib
4) Scipy

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

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
