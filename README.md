# AtoZ-Sign-recognision
Problem Statement:
To develop a hand gesture recognition that facilitates mute people and act as a communication tool between a traditional person and a specially abled person. 
This is the necessity as many people are not aware of sign language and are unable to effectively communicate with these group of people. 

Data Collection:
The data collection  process creates 2 folders test and train which has sub folders starting from  folder A to Z.
Based on the mode ‘test’ or ‘train’ the images captured will be sorted in the respective subfolders of them
This program pops up a webcam frame to capture the images.
As the images are captured , the image count for the respective letters on the frame also increase.

Image Processing:
The images that falls inside the bounding box is converted to a grayscale image .
Further the image is converted to a black and white format  by applying Gaussian Blur and threshold value
Finally the black and white image is saved in the subfolders.

