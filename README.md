# Food Vision Ultra

## Overview

Food Vision Ultra is an advanced Convolutional Neural Network (CNN) model designed to classify food images from the popular "Food 101" dataset. This project aims to surpass the performance of two prestigious models from ETH Zurich and the University of Massachusetts, while using less data and fewer iterations.

## Objectives

1. **Outperform ETH Zurich's model using only 10% of the training data**
   - Target: Beat 50.76% top-1 accuracy
   - Dataset: Food 101 (10% subset)

2. **Surpass University of Massachusetts' model with fewer iterations**
   - Target: Exceed 77.4% top-1 accuracy
   - Constraint: Use less than 250,000 iterations
   - Dataset: Full Food 101

## Model Architecture

Food Vision Ultra is based on the EfficientNetB0 architecture, known for its balance of accuracy and computational efficiency.

## Dataset

The [Food 101 dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) consists of 101 food categories, with 101,000 images. For each class, 250 manually reviewed test images are provided as well as 750 training images.

## Benchmarks

| Model                     | Top-1 Accuracy | Training Data | Iterations |
|---------------------------|----------------|---------------|------------|
| ETH Zurich                | 50.76%         | 100%          | N/A        |
| UMass                     | 77.4%          | 100%          | 250,000    |
| Food Vision Ultra (Ours)  | 77.91%         | 10% / 100%    | 130,625    |

## Usage

The model was created on Google Colab. Please note that if run locally, the model will download about 5gb of food images to your environment. If run in Colab, access to gpu will be required


