# Object Detection based on YOLOv7
This project is an implementation of object detection using YOLOv7. The YOLO (You Only Look Once) algorithm is a state-of-the-art object detection system, which can detect multiple objects in real-time. This project provides a fast and efficient way to detect various objects in images and videos.

## Installation

* Clone this repository: git clone https://github.com/atpugneSnahsE/ObjectDetection1.git
* Install the required packages: pip install -r requirements.txt
* Download the pre-trained weights from the official YOLO website: https://github.com/WongKinYiu/yolov7/releases/download/v1.0/yolov7.pth
* Place the downloaded weights in the weights directory.

# Usage
## Image Detection
To detect objects in an image, run the following command:

```python()
    python detect.py --source path/to/image.jpg --weights weights/yolov7.pth --conf 0.5
```
The --source argument specifies the path to the input image, --weights specifies the path to the pre-trained weights, and --conf sets the confidence threshold for detection.
## Video Detection
To detect objects in a video, run the following command:
```code()
python detect.py --source path/to/video.mp4 --weights weights/yolov7.pth --conf 0.5 --output output.avi
```
# Model Training
If you want to train your own object detection model, you can use the YOLOv7 architecture provided in the models directory. You can also use your own dataset by modifying the 
```
data/custom.yaml file.
```

# Uses
This project can be used for various applications, such as:
* Surveillance systems
* Autonomous vehicles
* Traffic monitoring
* People tracking
* Object recognition

# Output Samples
<h2>Sample output on video</h2>
<img src = "https://user-images.githubusercontent.com/80143440/229313739-52d60ada-3139-4d46-b616-7e8a3ff450e5.png" height="250" weight="250">&nbsp; &nbsp; &nbsp;
<h2>Sample output on image</h2>
<img src = "https://user-images.githubusercontent.com/80143440/229313764-063eda00-8c52-4bb8-83c2-503b09cb682e.jpg" height="250" weight="250">&nbsp; &nbsp; &nbsp;

#### This implementation of YOLOv7 provides an efficient and accurate way to detect various objects in real-time. It is easily customizable and can be trained on your own dataset.


