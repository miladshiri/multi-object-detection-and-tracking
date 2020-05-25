# Single and Multi object Detection and Tracking
Single and Multi object detection and tracking with OpenCV and C++

## Single object tracking
This program uses OpenCV Tracker API to track a manually selected region. 

usage: 

```
./single_object_tracking.out /home/.../test.mkv
```

## Multi object tracking
This program uses OpenCV MultiTracker API to track manually selected regions. 

usage: 

```
./multi_object_tracking.out /home/.../test.mkv
```

## Object detection with deep learning
This program uses OpenCV deep learning module to detect all the objects in a picture or video.

usage: 

```
./object_detection_with_deep_learning.out --config=/home/milad/workspace/sourcecodes/darknet/cfg/yolov3.cfg --model=/home/milad/workspace/sourcecodes/pretrainednet/yolov3.weights --width=416 --height=416 --scale=0.00392 --input=/home/milad/workspace/code_example/opencv/cpp/helloworld/MOT.mkv
```


## Single object detection and tracking
This program uses OpenCV deep learning and tracking modules to detect and track a single selected region.

usage: 

```
./single_object_detection_and_tracking.out --config=/home/milad/workspace/sourcecodes/darknet/cfg/yolov3.cfg --model=/home/milad/workspace/sourcecodes/pretrainednet/yolov3.weights --width=416 --height=416 --scale=0.00392 --input=/home/milad/workspace/code_example/opencv/cpp/helloworld/MOT.mkv
```


## Multi object detection and tracking
This program uses OpenCV deep learning and tracking modules to detect and track multiple regions.

usage: 

```
./multi_object_detection_and_tracking.out --config=/home/milad/workspace/sourcecodes/darknet/cfg/yolov3.cfg --model=/home/milad/workspace/sourcecodes/pretrainednet/yolov3.weights --width=416 --height=416 --scale=0.00392 --input=/home/milad/workspace/code_example/opencv/cpp/helloworld/MOT.mkv
```






