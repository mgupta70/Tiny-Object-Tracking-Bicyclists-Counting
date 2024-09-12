![Computer Vision](https://img.shields.io/badge/Computer%20Vision-blue)
![Computer Vision](https://img.shields.io/badge/ViT-green)
![Computer Vision](https://img.shields.io/badge/ResNet-grey)
![Computer Vision](https://img.shields.io/badge/ConvNeXt-yellow)
![Computer Vision](https://img.shields.io/badge/YOLOv8-orange)
![Computer Vision](https://img.shields.io/badge/DETR-purple)
![Computer Vision](https://img.shields.io/badge/Siamese%20networks-indigo)

# Unique Bicyclist Counting in Tempe City using Semi-supervised Re-identification

## Problem
Tracking a bicyclist across multiple images to avoid duplicate counting

<img src="/results/same_bicylist.png">

## Locations where cameras have been deployed in Tempe City
<img src="/results/image.png" width=350 height=260> <img src="/results/images_location.png" width=450 height=260>

## Approach
<img src="/results/approach.png" width=450 height=250> 

## Classification
<img src="/results/classification.png" height=140> 

#### Success and Failure cases of Classification
<img src="/results/classification_success.png" width=300 height=200> <img src="/results/classification_failure.png" width=300 height=200> 

## Detection
<img src="/results/detection.png" height=120> 

#### Success and Failure cases of Detection
<img src="/results/detect_success.png" height=200> <img src="/results/detection_failure.png" height=200> 

Region of Interest(ROI) is too small in second picture, so it's difficult for model to detect.

## Unique Counting of Bicyclist by Siamese Network
<img src="/results/siamese_network.png" width=400 height=275>   <img src="/results/unique_counting.png" width=400 height=275> 

#### Triplet Samples
<img src="/results/Easy_negative.png" width=300 height=200> <img src="/results/hard_positive.png" width=200 height=200> <img src="/results/hard_negative.png" width=320 height=200>








