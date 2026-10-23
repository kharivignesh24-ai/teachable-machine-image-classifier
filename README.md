# Mobile vs Laptop Image Classifier

## Project Overview

This project is an image-classification model trained using Google Teachable Machine. It classifies input images into two categories: mobile phones and laptops.

## Objectives

- Build an image classifier using supervised machine learning.
- Train the model using labeled images.
- Recognize whether an input image belongs to the mobile or laptop category.
- Explore practical image-classification techniques.

## Tools and Technologies

- Google Teachable Machine
- TensorFlow.js model export format

## Dataset

| Class | Training Images |
|---|---:|
| Mobile | 152 |
| Laptop | 153 |
| **Total** | **305** |

## Model Files

- `model.json` — model architecture
- `metadata.json` — class labels and model metadata
- `weights.bin` — trained model weights

## Model Output

The model produces predictions for the `mobile` and `laptop` classes, along with confidence scores.

## How to Use

The repository contains the exported trained model. A compatible application is required to load the model and classify new images.

## Limitations

Model predictions depend on the training images, image quality, background, lighting, and camera angle. The displayed confidence score is not a guarantee of correctness.

## Training Platform

[Google Teachable Machine](https://teachablemachine.withgoogle.com/train/image)

## Author

Hari Vignesh
