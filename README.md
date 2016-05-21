﻿## YOLO in caffe

## Introduction

This is a caffe implementation of the YOLO:Real-Time Object Detection

Note, the caffe models are not trained in caffe, but converted from darknet's (.weight) files (http://pjreddie.com/darknet/yolo/).
 

## Model files

YOLO: https://drive.google.com/file/d/0Bzy9LxvTYIgKMXdqS29HWGNLdGM/view?usp=sharing

YOLO_small: https://drive.google.com/file/d/0Bzy9LxvTYIgKa3ZHbnZPLUo0eWs/view?usp=sharing

YOLO_tiny: https://drive.google.com/file/d/0Bzy9LxvTYIgKNFEzOEdaZ3U0Nms/view?usp=sharing

## Usage

python yolo_main.py -m model_filename -w weight_filename -i image_filename

replace model_filename with /your/path/to/yolo_small_deploy.prototxt or yolo_tiny_deploy.prototxt, 
weight_filename with /your/path/to/yolo_tiny.caffemodel or yolo_small.caffemodel and image_filename with the target image file

## Requirements

   a) Caffe, pycaffe

   b) Opencv2

## Copyrights
 
According to the LICENSE file of the original code,

   a) Me and original author hold no liability for any damages

   b) Do not use this on commercial!

