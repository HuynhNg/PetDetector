Dog and Cat Detection using R-CNN

Overview

This project implements an object detection model to identify dogs and cats using R-CNN. The model utilizes:

Selective Search to propose bounding box regions.

ResNet50 as the feature extractor.

Non-Maximum Suppression (NMS) to filter overlapping bounding boxes.

Features

Selective Search: Generates candidate object regions.

ResNet50: Pretrained deep learning model used for classification.

Bounding Box Filtering: NMS is applied to remove redundant detections.

Visualization: Draws bounding boxes around detected objects with confidence scores.
