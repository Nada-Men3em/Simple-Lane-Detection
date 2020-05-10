# Simple-Lane-Detection
Lane Finding Project for Self-Driving Car Nano-degree 

## Overview
When we drive, we use our eyes to decide where to go. The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle. Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project you will detect lane lines in images using Python and OpenCV.

## Project Description 

#### My pipeline consisted of 5 steps:
  * 1- The images are converted to grayscale.
  * 2- Appling Gaussian Blur
  * 3- Then Canny Algorthim  
  * 4- Find the Region of Intrest and Maske The Image
  * 5- Finally applying Hough Transforme
  
### Average/Extrapolate:
This part of the project would not be done without the help from this well explained repository [link](https://github.com/gongf05/udacity-self-driving-car-projects/tree/master/Term1-P1-lane-line)

### Dependencies:
Python3 Along with:
  * 1- Numpy
  * 2- Matplotlib
  * 3- OpenCV
Using Jupyter Nootbook


