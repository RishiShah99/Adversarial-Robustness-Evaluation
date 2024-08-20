# Adversarial Robustness Evaluation

This repository contains a comprehensive evaluation of three models under adversarial attacks: **ImageNet100**, **MNIST**, and **CORNet-S**. The primary focus is to assess the robustness of these models against two widely recognized adversarial attacks: **Projected Gradient Descent (PGD)** and **Carlini & Wagner (CW)**.

## Contents

- **ImageNet100 Model**
  - Top-1 and Top-5 Accuracy
  - PGD Attack Accuracy
  - CW Attack Accuracy

- **MNIST Model**
  - Top-1 and Top-5 Accuracy
  - PGD Attack Accuracy
  - CW Attack Accuracy

- **CORNet-S Model**
  - Top-1 and Top-5 Accuracy
  - PGD Attack Accuracy
  - CW Attack Accuracy

## Model Descriptions

### 1. ImageNet100 Model
This model is trained on a subset of the ImageNet dataset, containing 100 classes. The evaluation focuses on:
- **Top-1 Accuracy:** 73%
- **Top-5 Accuracy:** 94%
- **PGD Attack Accuracy:** 10%
- **CW Attack Accuracy:** 15%

### 2. MNIST Model
This model is trained on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits. The evaluation focuses on:
- **Top-1 Accuracy:** 99%
- **Top-5 Accuracy:** 99.43%
- **PGD Attack Accuracy:** 35%
- **CW Attack Accuracy:** 70%

### 3. CORNet-S Model
The CORNet-S model is a specialized neural network designed for robust object recognition. The evaluation focuses on:
- **Top-1 Accuracy:** 70%
- **Top-5 Accuracy:** 89%
- **PGD Attack Accuracy:** 40%
- **CW Attack Accuracy:** 50%

## Adversarial Attacks

### Projected Gradient Descent (PGD)
PGD is one of the most effective adversarial attacks. It iteratively perturbs the input images with small, adversarially chosen noise, aiming to maximize the model's loss.

### Carlini & Wagner (CW) Attack
CW attack is a more sophisticated adversarial attack designed to minimize the perturbation while still fooling the model, often resulting in adversarial examples that are nearly indistinguishable from the original inputs.

## How to Run the Models

Each model is provided in a separate directory within this repository. The models can be evaluated using the provided scripts. Below are the instructions for running the evaluation:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RishiShah99/Adversarial-Robustness-Evaluation.git
   ```
2. Navigate to the desired model's directory:
   ```bash
   cd Adversarial-Robustness-Evaluation/ImageNet100
   ```
3. Run any of the scripts.

## Conclusion: 
This repository aims to provide insights into the adversarial robustness of various models. The results from the evaluations can be used as a benchmark for future improvements in model robustness.
