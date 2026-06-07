# K-Means Image Segmentation with Unsupervised Learning

This project applies unsupervised machine learning to perform image segmentation using the K-Means clustering algorithm.

## Project Overview

The project uses K-Means clustering to group similar image pixels based on their RGB color values. By replacing each pixel with the color of its assigned cluster center, the image can be segmented and compressed while preserving the main visual structure.

## Objective

The objective of this project is to demonstrate how unsupervised learning can be applied to image processing tasks, especially image segmentation and color reduction.

## Key Features

- Image loading and preprocessing
- RGB pixel matrix transformation
- Image flattening and reconstruction
- K-Means clustering from scratch
- Pixel-level clustering
- Segmented image generation
- Image color compression

## Dataset

The project uses an image file as input:

- `images/lily.png`

The image is processed as a pixel matrix, where each pixel is represented by RGB values.

## Repository Structure

```text
kmeans-image-segmentation-unsupervised-learning/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── kmeans_image_segmentation.ipynb
│
├── src/
│   └── kmeans_image_segmentation.py
│
├── images/
│   └── lily.png
│
├── reports/
│   └── unsupervised_learning_kmeans_report.pdf
│
└── results/
    └── README.md
