# Object-Detection-using-Yolo

## Dataset 
Images comprises cars and some other objects too.

## Model

I am using already pretrained model of yolo, so In this i have  used pretrained weights downloaded from <b>Darknet</b> 
website for yolo detection.

## About folders and files

###model_data subfolder
coco_classes.txt contains the 80 classes.
###yolo.h5
It is the h5 file generated to load the weights of the pretrained model without training.
anchor_classes.txt -> the anchor boxes(5) with their coordinates.
3. yad2k subfolder -> It contains the files for the basic yolo model.
4. car_detection.ipynb -> It is the main file for detecting the objects.
5. location.txt -> It will contain the values of coordinates of the detected objects.
6. out subfolder -> It contains the image with the detected object
