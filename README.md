## Autonomous Vehicle Engineering Portfolio 

This repository is a portfolio of the projects I created for exploration in the field of autonomous vehicle engineering. 
I hope you enjoy reading this as I enjoyed creating it! 

### Table of Contents

* [Computer Vision](#Computer-Vision) 
  * [Detecting Lane Boundaries](#Detecting-Lane-Boundaries)
  * [Traffic Light Classifier](#Traffic-Light-Classifier)
  * [Finding Lane Lines](#Finding-Lane-Lines)

## Computer Vision 
* #### **Detecting Lane Boundaries**  [[Check out repo]](https://github.com/Arina-W/Detecting-Lane-Boundaries)
> Keywords: OpenCV | 

In this project, I wrote a software pipeline that identifies lane boundaries in a specific video taken from a front facing camera mounted on a vehicle. Frames from the video were  taken and used to extract enough information while creating this pipeline. All details in this pipeline can be seen in [this depository](https://github.com/Arina-W/Detecting-Lane-Boundaries). The entire code of this pipeline can be found in this [Jupyter Notebook.](http://localhost:8889/notebooks/PycharmProjects/P2/CarND-Advanced-Lane-Lines-master/AdvancedLaneFinding.ipynb)

* #### **Traffic Light Classifier**   [[Check out repo]](https://github.com/Arina-W/Traffic_Light_Classifier)
> Keywords: OpenCV | 

In this project, I used computer vision techniques to build a classifier for images of traffic lights.
I used a given dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.
In the [Traffic_Light_Classifier notebook](https://github.com/Arina-W/Traffic_Light_Classifier/blob/master/Traffic_Light_Classifier.ipynb) I did
pre-processing image routine, extract features that will help distinguish types of images, and use the features to classify test images into three 
categories : red, yellow, or green. 

* #### **Finding Lane Lines**   [[Check out repo]](https://github.com/Arina-W/Finding-Lane-Lines)
> Keywords: OpenCV | 

In this project, I developed a pipeline on a series of individual images, and later applied the result to a set of video streams.
Current pipeline might have trouble to perceive the lane lines if the car needs to take a sharp turn
or even a simple curve maneuver. Another concern would be the effect of nightlight from night lamps and reflections of headlamps etc
during nighttime.
