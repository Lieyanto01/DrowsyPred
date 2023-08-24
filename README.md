# Driver Drowsiness Prediction based on Percentage of Eye Closure using Ceep Learning
This project is a driver drowsiness prediction based on percentage of eye closure (PERCLOS) using deep learning (CNN). This project is built as final project for my study.

This project is built using Python programming language and could be run in >18 FPS using Single Board Computer (SBC) Jetson Nano

Process included in this project are:
* Image acquisition from camera
* Face detection using Yunet Face Detection model
* Eye Landmark Prediction using Dlib Landmark Predictor
* Eye Aspect Ratio (EAR) and Percentage of Eye Closure (PERCLOS) calculation
* Drowsy Classification using CNN model
* Drowsy Prediction using CNN model

When this program is running, there will be 2 windows showing up, i.e. image acquisition with landmark predicted, and EAR graph with other information.
![alt text](https://github.com/Lieyanto01/DrowsyPred/blob/main/Screenshot%20(2839).png)
![alt text](https://github.com/Lieyanto01/DrowsyPred/blob/main/Screenshot%20(2881).png)
