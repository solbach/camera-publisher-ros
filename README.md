# ROS Camera Publisher

The purpose of this program is to publish camera images and infos (such as the camera matrix) as a ROS topic.

## what it does
It publishes the images as
> image:=/image_raw 

and 

> camera_info:=/camera_info

## usage
    $ roslaunch camera_publisher cameraLaunch.launch

## requires
* ROS
* cmake 2.8
* openCV
* gcc

## tested on
* Ubuntu 14.04
* ROS Indigo
* gcc 4.8.2
* cmake 2.8.12.2
* openCV 2.4.8

## example output

## To Do
* example output

