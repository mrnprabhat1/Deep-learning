Cocoa Flower and Cocoa Pod Detection using Deep Learning
Project Overview
This repository presents a deep learning based object detection pipeline for identifying cocoa flowers and cocoa pods in natural field images. The primary objective of the project is to demonstrate the feasibility of applying modern object detection techniques to agricultural monitoring tasks under limited data conditions.

The project focuses on two key aspects. First, a label consistent data augmentation strategy is used to address the challenge of small annotated datasets. Second, a two stage deep learning detector is trained and evaluated to localize cocoa flowers and pods using bounding boxes.
Key Contributions

Design of a label consistent data augmentation pipeline for object detection

Handling of Pascal VOC XML annotations with bounding box validation

Training of a Faster R CNN based object detection model

IoU based quantitative evaluation using precision, recall, and F1 score

Visualization of ground truth and predicted bounding boxes

Dataset Description

Data type. RGB field images

Original dataset size. 14 images

Augmented dataset size. 56 images

Object classes

Flower

Cocoa pod

Annotation format. Pascal VOC XML

The images were collected under real field conditions and annotated manually. Due to the limited dataset size, data augmentation plays a critical role in model training.
