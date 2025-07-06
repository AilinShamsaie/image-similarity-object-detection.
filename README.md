# image-similarity-object-detection.
A Python project for measuring image similarity (SSIM, PSNR, MSE) and detecting objects using selective search and VGG16.
# VGG16 Object Detection with Selective Search

This project demonstrates object detection and image similarity analysis using classical deep learning methods.

## Overview

- **Object Detection**: Uses a pre-trained VGG16 model (from Keras) to detect objects in images by applying Selective Search for region proposals.
- **Image Similarity**: Computes SSIM (Structural Similarity Index), MSE (Mean Squared Error), and PSNR (Peak Signal-to-Noise Ratio) between two images.

##  Features

- Visualizes detected objects with bounding boxes and labels
- Filters overlapping detections using Non-Maximum Suppression (NMS)
- Supports multiple image inputs (e.g., kitchen, street view, zebra)
- Image similarity comparison using grayscale images
