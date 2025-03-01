# PoultryScan: Disease Detection in Poultry using Deep Learning Models

This repository contains the implementation of a disease detection system for poultry using five deep learning models: VGG19, Vision Transformer (ViT), Swin Transformer, EfficientNetB7, and MobileNetV3. The system is designed to classify images into four distinct classes: Healthy, Coccidiosis (Cocci), Salmonellosis (Salmo), and Newcastle disease (NCD).

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Training and Testing](#training-and-testing)
- [Experimental Design](#experimental-design)
- [License](#license)

## Introduction
The goal of this project is to detect and classify diseases in poultry using deep learning models. The system uses a combination of convolutional neural networks (CNNs) and transformer-based models to achieve high accuracy in disease detection.

## Dataset
The dataset consists of images labeled into four classes:
- Healthy
- Coccidiosis (Cocci)
- Salmonellosis (Salmo)
- Newcastle disease (NCD)

## Models
The following models are used in this project:
1. **VGG19**: A deep convolutional neural network with 19 layers.
2. **Vision Transformer (ViT)**: A transformer-based model adapted for image classification.
3. **Swin Transformer**: A hierarchical vision transformer using shifted windows.
4. **EfficientNetB7**: A scalable and efficient convolutional neural network.
5. **MobileNetV3**: A lightweight model optimized for mobile devices.

## Training and Testing
The dataset is divided into 80% for training and 20% for testing. Each model is trained on the training set and evaluated on the test set to measure its performance.

## Experimental Design
![image_alt](https://github.com/Reyad02/PoultryScan/blob/2a7eccf69f75a1feef434312be0c8034cec5a467/Experimental_%20Design.png)

## License
This project is licensed under the MIT License. See the LICENSE file for details.



