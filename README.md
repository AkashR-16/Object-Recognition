# Object Detection with OpenCV and MobileNet SSD

This repository contains a Python script for performing object detection on an input image using OpenCV and the MobileNet SSD (Single Shot MultiBox Detector) model trained on the COCO (Common Objects in Context) dataset. The script detects objects in the image and draws bounding boxes around them, along with labels indicating the detected objects and their confidence scores.

## Prerequisites

Before using this script, ensure you have the following dependencies installed:

- OpenCV (`cv2`)
- Python 3.x

## Installation

1. Clone this repository to your local machine:
   ``` shell
   git clone https://github.com/your-username/object-detection-opencv.git
2. Navigate to the repository's directory:
   ``` shell
   cd object-detection-opencv

3. Download the Necessary Model Files and Class Labels

Before using this script, you need to download the following model files and class labels and place them in the `models/` directory within the repository:

- **Model weights:** [frozen_inference_graph.pb](https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API#use-existing-config-file-for-your-model)
- **Model configuration:** [ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt](https://github.com/opencv/opencv/blob/master/samples/data/ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt)
- **Class labels:** [coco_names.txt](https://github.com/opencv/opencv/blob/master/samples/data/coco_names.txt)

## Usage
1. Run the script:
   ``` shell
   python object_detection.py
2. When prompted, enter the path to the input image you want to analyze. Press Enter to continue.

3. The script will load the image, perform object detection, and display the result in a new window. Detected objects will be outlined with bounding boxes and labeled with their names and confidence scores.

4. To close the image window, press any key.

## Example Image 
![objDet](https://github.com/AkashR-16/Object-Recognition/assets/99939852/8cd90b8a-0c23-4805-b256-f9ab50288a8c)

