# Mouth-Detection-System
A mouth detection system using OpenCV and Python involves using image processing techniques to identify and track the location of a person's mouth in a real-time feed.

# A mouth detection system using OpenCV and Python typically involves the following steps:

 1.Install OpenCV and Python on your system.
 
 2.Load an image or video stream using OpenCV.
 
 3.Convert the image to grayscale using OpenCV's cvtColor function.
 
 4.Use OpenCV's CascadeClassifier to detect the mouth in the grayscale image. This involves training a classifier using a set of positive and negative images and using      it to detect the mouth in new images.
 
 5.Draw a rectangle around the detected mouth using OpenCV's rectangle function.
 
 6.Display the output image with the detected mouth using OpenCV's imshow function.
