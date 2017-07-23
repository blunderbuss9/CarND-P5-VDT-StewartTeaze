# CarND-P5-VDT-StewartTeaze
Udacity Self-Driving Car Nanodegree - Project 5 - Vehicle Detection and Tracking - Stewart Teaze

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


The overall goal of this project is to write a software pipeline to detect vehicles in a video (project_video.mp4), but the main output or product of the project is the detailed project writeup.  Refer to the file writeup.pdf, found in this repository, for all the details regarding the development and composition of the project.  

The specific goals / steps of this project are:
•	Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
•	Optionally, you can also apply a color transform and append binned color features, as well as histograms of color, to your HOG feature vector.
•	Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
•	Run your pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
•	Estimate a bounding box for vehicles detected.
