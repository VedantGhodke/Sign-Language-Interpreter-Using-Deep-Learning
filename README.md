# Sign Language Interpreter Using Deep Learning

A sign language interpreter created using live video feed from the camera.

## Table ofCcontents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Demo](#demo)
* [Technologies and Tools](#technologies-and-tools)
* [Setup](#setup)
* [Process](#process)
* [Code Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Contact](#contact)

## General Information

The theme was to use technology to improve accessibility by finding a creative solution to benefit the lives of those with a disability. I wanted to make it easy for 70 million deaf people across the world to be independent of translators for there daily communication needs, so I designed the app to work as a personal translator 24/7 for the deaf people.

## Demonstration

![Example screenshot](./img/demo4.gif)



![Example screenshot](./img/demo2.gif)



![Example screenshot](./img/demo3.gif)



## Screenshots

![Example screenshot](./img/Capture1.PNG)
![Example screenshot](./img/Capture.PNG)


## Technologies and Tools

* Python 
* TensorFlow
* Keras
* OpenCV

## Setup

* Use comand promt to setup environment by using install_packages.txt and install_packages_gpu.txt files. 
 
`pyton -m pip r install_packages.txt`

This will help you in installing all the libraries required for the project.


## Features

My model was able to predict the 44 characters in the ASL with a prediction accuracy >95%.

Features that can be added:

* Deploy the project on cloud and create an API for using it.
* Increase the vocabulary of our model
* Incorporate feedback mechanism to make the model more robust
* Add more sign languages
