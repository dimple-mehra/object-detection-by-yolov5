# object-detection-by-yolov5


This repository documents my week-by-week progress on a computer vision project focused on **pedestrian detection, object tracking**. It contains concise weekly reports for Weeks 1–4, followed by a **final applied assignment** that integrates detection and tracking into one end-to-end pipeline.


## Project goal

Build a strong practical understanding of **computer vision for detection and tracking**, then apply these techniques to model **normal pedestrian motion** simulating real-world surveillance deployments.


## Repo layout

```
Object-Tracking
├── README.md
├── Week1
│   └── Week1.md
├── Week2
│   └── Week2.md
├── Week3
│   └── Week3.md
├── Week4
│   └── Week4.md
└── Final-Assignment
    ├── object_tracking.ipynb
    └── README.md
```

Each `WeekX.md` contains:

* short overview of the week
* topics covered and why they matter
* key concepts, datasets, and models used

The `Final-Assignment/` folder contains the **complete integrated implementation**.


## What to expect

### Week 1 — Deep Learning Foundations

* Neural Networks and backpropagation
* Convolutional Neural Networks (CNNs)
* PyTorch-based NN and CNN tutorials
* OpenCV basics for image processing


### Week 2 — Object Detection & YOLOv5

* Object detection fundamentals
* YOLO algorithm and single-stage detectors
* YOLOv5 architecture and variants
* Training YOLOv5 on custom datasets


### Week 3 — Training YOLOv5 on MOT17

* Understanding the MOT17 dataset
* Data preprocessing and annotation conversion
* Training YOLOv5s and YOLOv5m models
* Freezing layers and comparing performance


### Week 4 — Object Tracking 

* Object tracking concepts and evaluation
* Tracking-by-detection pipeline
* DeepSORT-based tracking
* Motion trajectory extraction


## Final Assignment 

* Pedestrian detection using trained YOLOv5 models
* Multi-object tracking across video frames
* Learning normal pedestrian motion patterns



## Dependencies (summary)

* numpy, pandas
* matplotlib
* opencv-python
* torch
* yolov5
* deep-sort-realtime
* jupyter / google colab


## How to review the work

* Read `WeekX/WeekX.md` for conceptual understanding.
* Explore `Final-Assignment/` for the complete runnable pipeline.
* Follow the progression from **foundations → detection → tracking**.


## Status

This repository contains the completed work for **Weeks 1–4** and a **final assignment**, submitted as the **final report and implementation**.

