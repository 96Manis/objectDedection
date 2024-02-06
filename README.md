# Object Detection with OpenCV and MobileNet SSD

This repository contains Python code for performing object detection using OpenCV's DNN module and the MobileNet SSD model trained on the COCO dataset. It detects objects in images and draws bounding boxes around them.

## Contents

- `object_detection.py`: Python script for object detection using OpenCV and MobileNet SSD.
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`: Configuration file for the MobileNet SSD model.
- `frozen_inference_graph.pb`: Frozen inference graph for the MobileNet SSD model.
- `labels.txt`: List of class labels for the COCO dataset.

## Requirements

- Python 3.x
- OpenCV (cv2)
- Matplotlib

## Usage

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd object-detection-opencv
    ```

2. Ensure you have the necessary model files (`ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` and `frozen_inference_graph.pb`) in the same directory as the Python script.

3. Run the Python script:

    ```bash
    python object_detection.py
    ```

4. The script will perform object detection on the provided image (`001150.jpg`) and display the image with bounding boxes and class labels.

