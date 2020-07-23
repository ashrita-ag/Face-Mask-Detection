# Face Mask Detection
This is a Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in real-time video streams. With a little bit of changes, it may be used for static images as well.

## Overview
* First, we get the VideoStream with the face and run it through a cascade classifier. The classifier will give the region of interest of the face (height and width). 
* Secondly, we will resize the region of interest into a 100x100 and pass it to a pre-trained CNN, it will give us the required output.
> Face mask dataset was created by Prajna Bhandary. This dataset consists of 1,376 images belonging to with mask and without mask 2 classes.
