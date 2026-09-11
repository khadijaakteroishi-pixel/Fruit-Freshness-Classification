# Fruit Freshness Classification using Deep Learning

A deep learning project for classifying fresh and rotten fruits using image preprocessing, augmentation, transfer learning, model comparison, attention experiments, explainability, statistical evaluation, and cross-validation.

## Project Overview

This project focuses on automatic fruit freshness classification from images. The dataset contains six classes covering fresh and rotten versions of apples, bananas, and oranges.

The notebook explores several deep learning approaches, including VGG16, ResNet50, EfficientNetB0, DenseNet121, a VGG16 attention experiment, feature-fusion ensemble learning, Grad-CAM explainability, ShuffleNetV2 with multi-head self-attention, and 5-fold cross-validation.

The work is designed as a comparative deep learning study rather than a single-model experiment.

## Classes

The six classes are:

- Fresh Apples
- Fresh Banana
- Fresh Oranges
- Rotten Apples
- Rotten Banana
- Rotten Oranges

## Dataset

The project uses the **Fruits Fresh and Rotten for Classification** dataset.

The notebook loads the dataset using Kaggle and works with separate training and testing directories.

The Keras directory generators reported:

- Training images: **9,813**
- Validation images: **1,088**
- Test images: **2,698**
- Number of classes: **6**

A separate explicit 80/10/10 split was also created from 10,901 images:

- Training: **8,720**
- Validation: **1,090**
- Testing: **1,091**

## Image Preprocessing

All images are resized to:

```text
224 × 224 pixels
