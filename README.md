# Car Detection for Autonomous Driving | YOLOv2, tensorflow 1.x

YOLO ("you only look once") is a popular algoritm because it achieves high accuracy while also being able to run in real-time. Training a YOLO model takes a very long time and requires a fairly large dataset of labelled bounding boxes for a large range of target classes. We are loading an existing pretrained Keras YOLO model stored in "yolo.h5".

## Data
This project was done on Coursera's Deep Learning Specialization. To collect data, they mounted a camera to the hood (meaning the front) of the car, which takes pictures of the road ahead every few seconds while you drive around. They gathered all these images into a folder and labelled them by drawing bounding boxes around every car they found.

## Output
![](/car_bbox.jpg)
