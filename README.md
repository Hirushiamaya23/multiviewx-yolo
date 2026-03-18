# Multi-Camera Pedestrian Detection and Tracking

## Overview
This project implements a pipeline for detecting and tracking pedestrians using the MultiviewX dataset.

## Pipeline
Dataset → YOLO Detection → ByteTrack Tracking → Multi-camera Analysis

## Tools Used
- YOLO (Ultralytics)
- ByteTrack
- Python

## Results
Tracking was performed on multiple camera views (C1, C2). Each camera produces independent tracking IDs.

## Note
Due to hardware limitations, a lightweight YOLO-based pipeline was used instead of heavier models like MVDet.
