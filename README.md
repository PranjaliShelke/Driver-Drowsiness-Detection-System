# Driver-Drowsiness-Detection-System
A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build a system using Python, OpenCV which will alert the driver when he feels sleepy.

# Python version used
Python 3.9 

# Project Prerequisites
1.OpenCV
2.imultils
3.dlib
4.scipy

# Implementation
Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.
It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

![IMG-20211214-WA0005](https://user-images.githubusercontent.com/88675259/146022200-a68c0a50-407c-4b4c-87e1-9cadc08c925b.jpg)

# Relationship
![eye2](https://user-images.githubusercontent.com/88675259/146022428-c96e17f3-bc28-4038-a45a-31f1aa709b9b.png)


# Output

1.When the eyes are opened

![1639494926719](https://user-images.githubusercontent.com/88675259/146026011-4080342f-acd0-46b0-a648-7dccd3e30af5.jpg)

2.When the eyes get closed

![1639494926723](https://user-images.githubusercontent.com/88675259/146026104-9ec9af26-5b5f-4934-bd7f-4ebe6dc535e9.jpg)





