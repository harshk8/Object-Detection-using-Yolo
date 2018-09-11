# Object-Detection-using-Yolo

## Dataset 
Images comprises cars and some other objects too.

## Model

I am using already pretrained model of yolo, so In this i have  used pretrained weights downloaded from <b>Darknet</b> 
website for yolo detection.

## About folders and files

### model_data subfolder
coco_classes.txt -> It contains the 80 classes.
yolo.h5 -> It is the h5 file generated to load the weights of the pretrained model without training.
anchor_classes.txt -> the anchor boxes(5) with their coordinates.
### yad2k subfolder 
It contains the files for the basic yolo model.
### car_detection.ipynb 
It is the main file for detecting the objects.
### location.txt 
It will contain the values of coordinates of the detected objects.
### out subfolder 
It contains the image with the detected object
