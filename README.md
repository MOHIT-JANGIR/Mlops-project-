# Mlops-project
# HELMET DETECTION 
## to ensure and implement safety of people and to know how many people are following traffic rules

# Deploying a Flask Container for Helmet Detection by using Jenkins

Machine Learning

Open in app

Get started

Responses

To respond to this story,

get the free Medium app.

Open in app

There are currently no responses for this story.

Be the first to respond.

You have 2 free stories left this month. Sign up and get an extra one for free.

Image for post

Deploying a Flask Container for Helmet Detection by using Jenkins

B.V.Rohan Bharadwaj

B.V.Rohan Bharadwaj

Jul 24 · 8 min read

Head injuries are a major cause of death, injury and disability among users of motorized two wheel vehicles.The lack or inappropriate use of helmets has been shown to increase the risk of fatalities and injuries resulting from road crashes.Use of helmets has been shown to reduce fatal and serious head injuries by between 20% and 45% among motorized two-wheelers users.

We have developed a web application which gives a count of people wearing and not wearing helmets.Internally the web app uses YOLO Object Detection Algorithm.

Overview of the YOLO Algorithm:

Image for post

YOLO (You Only Look Once) is a real-time object detection algorithm, which is one of the most effective object detection algorithms.Object detection is a problems in computer vision where we have to recognize what and where i.e. what objects are inside a given image and also where they are in the image.

This algorithm works by performing only one forward pass, a single CNN simultaneously predicts multiple bounding boxes and class probabilities for those boxes. YOLO trains on full images and directly optimizes detection performance.

Darknet is a framework to train neural networks, it is open source and written in C/CUDA and serves as the basis for YOLO.
https://github.com/AlexeyAB/darknet



