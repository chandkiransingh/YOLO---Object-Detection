# YOLO---Object-Detection
YOLO - Object Detection (YOLO, SSD, Faster R-CNN) with OpenCV and Python

Dependencies
opencv
numpy

$pip3 install numpy opencv-python

Weights file - 
Link - https://pjreddie.com/media/files/yolov3.weights
					
					 OR

$ wget https://pjreddie.com/media/files/yolov3.weights


Execute - 
$ python3 yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt
