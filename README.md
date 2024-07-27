# ImageNet100 ResNet18 PGD Attacks

This repository contains the implementation of a ResNet18 model to classify images in the ImageNet100 dataset and an analysis of its robustness using Projected Gradient Descent (PGD) attacks.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Adversarial Attacks](#adversarial-attacks)
- [Results](#results)
- [Modules](#modules)
- [Usage](#usage)
  
## Project Description

The goal of this project is to develop a ResNet18 model to classify images from the ImageNet100 dataset and evaluate its robustness against adversarial attacks using PGD. 

## Dataset

The ImageNet100 dataset is a subset of the larger ImageNet dataset, containing images from 100 different classes. It is commonly used for benchmarking image classification models due to its manageable size and diverse classes. In total, it has about 127 000 images inside of the dataset with 100 different classes. 

## Model Architecture

The model used in this project is a ResNet18, a well-known convolutional neural network architecture designed for image classification tasks. ResNet18 utilizes residual connections to allow for deeper networks and improved performance.

## Adversarial Attacks

This project includes the implementation of Projected Gradient Descent (PGD) attacks to test the robustness of the ResNet18 model. PGD is a widely used adversarial attack method that iteratively perturbs the input images to maximize the model's prediction error.

## Results

The model had a 95% top-5 accuracy and a 82% top-1 accuracy. 

## Modules

To run the code, you need the following modules:

```bash
# Install the required modules using pip
pip install json
pip install matplotlib
pip install random
pip install cv2
pip install torch
pip install torchvision
pip install PIL
pip install tqdm
pip install torchattacks
```

## Usage
Clone the repository and navigate to the project directory: 
```bash
git clone https://github.com/RishiShah99/imagenet100-resnet18-pgd-attacks.git
cd imagenet100-resnet18-pgd-attacks
```
