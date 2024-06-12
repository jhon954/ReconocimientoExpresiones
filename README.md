# Real-Time Emotion Recognition Using FisherFaces

## Overview

This repository implements a computer vision model for real-time emotion recognition based on images of people's faces. It includes real data and `.py` files for data capture, model training, and saving the trained model.

## Description

The model used in this implementation is FisherFaces, a face recognition technique based on the Linear Discriminant Analysis (LDA) method. FisherFaces was developed to improve face recognition performance by considering not only variability between different individuals but also variability within the same person due to changes in lighting, facial expression, and other factors.

### Key Features

- **Real Data:** The repository includes real data for training and testing the model.
- **Python Scripts:** Scripts for data capture, model training, and using the trained model are provided.
- **FisherFaces Model:** Utilizes the FisherFaces model for robust face and emotion recognition.

### Contents

- **`capturandoRostros.py`:** Script for capturing images and creating the dataset.
- **`entrenando.py`:** Script for training the FisherFaces model.
- **`reconocimientoS.py`:** Script for using the model trained.
- **`data`:** Directory containing real datasets used for model training and testing.

### Usage

1. **Data Capture:** Use `capturandoRostros.py` to capture images and create the dataset.
2. **Train Model:** Run `entrenando.py` to train the FisherFaces model on the captured data.
3. **Save Model:** Use `reconocimientoS.py` to use the trained model.

### About FisherFaces

FisherFaces is a powerful face recognition technique that enhances recognition accuracy by addressing both inter-person and intra-person variability. It leverages Linear Discriminant Analysis (LDA) to maximize class separability while minimizing within-class variance, making it robust against changes in lighting, expressions, and other facial variations.
