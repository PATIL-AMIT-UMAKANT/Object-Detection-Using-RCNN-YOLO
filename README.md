# Object-Detection-Using-RCNN-YOLO

This project is used for object detection using Yolov3 & RCNN.

YOLO and RCNN are two different types of object detectors.

Yolo is a Single Shot detectors like the name suggest You Looks Only Onces.
RCNN is a Region based detectors like its extarcts only imp regions.

Yolov3 seems to have more accuracy than Rcnn.
Yolov3 execution Frames per second is far better than RCNN.
Yolov3 seems to detect small object precisely than larger object.
yolov3 takes less time compair to RCNN
RCNN works great on high resolution pictures and is more accurate.
For real time usage i think Yolov3 is better to implement in current scenario.

Download the necessary weights and files.

YOLOv3

wget https://pjreddie.com/media/files/yolov3.weights

wget https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg?raw=true -O ./yolov3.cfg
