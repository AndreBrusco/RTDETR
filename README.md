## RT-DETR Models for Real-Time Tree Crown Detection

This repository contains the implementation and analysis of RT-DETR models for detecting tree crowns in high-resolution aerial images. The study explores metrics such as AP50, AP75, and Average Recall, comparing RT-DETR with traditional frameworks like YOLO and Faster R-CNN. Special attention is given to the efficiency of Dynamic Sparse Patterns (DSP) configurations, which balance precision and computational cost.

## Overview

The project is based on the dataset and methodologies introduced by França et al. in their study on tree crown detection using deep learning:
Tree Crown Detection Using Advanced Object Detection Techniques.

We also leverage the RT-DETR repositories and techniques shared by Zhao et al., as introduced in their work on real-time object detection:
DETRs Beat YOLOs on Real-time Object Detection.

## The provided code includes:

Training and evaluation scripts for RT-DETR models.
Dataset preparation following the structure proposed by França et al..
Comparative analysis of model performance, including DSP configurations.
Metrics computation for AP50, AP75, AP50:95, Average Recall, and computational costs.
Key Features
Dataset: The dataset comprises 220 non-overlapping $512 \times 512$ pixel aerial images annotated with 3,382 tree crowns, as described by França et al..
Models Evaluated: Fourteen RT-DETR models with varying backbones, including HGNetV2 and ResNet (18, 34, 50, 101).
Metrics: AP50, AP75, AP50:95, and Average Recall, along with computational efficiency (parameters and training time).
DSP Configurations: Analysis of DSP strategies that optimize precision and computational cost.

## References 📚
França, X. et al. (2021). Tree Crown Detection Using Advanced Object Detection Techniques. Remote Sensing.

Link: [MDPI Remote Sensing Article](https://www.mdpi.com/2072-4292/13/13/2482)
Link: [https://github.com/pedrozamboni/individual_urban_tree_crown_detection](https://github.com/pedrozamboni/individual_urban_tree_crown_detection)

Zhao, Y. et al. (2024). DETRs Beat YOLOs on Real-time Object Detection. CVPR.
Link: [RT-DETR GitHub Repository](https://zhao-yian.github.io/RTDETR/)

## Usage
To run the scripts, ensure that you have the dataset prepared as per the structure described in França et al. and follow the instructions in the setup.md file. The repository is Docker-ready for running MiKTeX or can be integrated with Overleaf for LaTeX report generation.

## Contributions 👍
Feel free to fork and improve the repository! Feedback and pull requests are welcome.
