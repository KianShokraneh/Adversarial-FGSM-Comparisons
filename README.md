# Adversarial-FGSM-Comparisons
This repository contains a Python script that demonstrates the implementation of the Fast Gradient Sign Method (FGSM) for generating adversarial examples using different adversarial attack libraries. FGSM is a widely used adversarial attack technique to test the robustness of machine learning models, particularly in image classification tasks.

## Contents

- **`fgsm_using_different_libraries.py`**: The main script that walks through the implementation of FGSM across various adversarial attack libraries such as Foolbox, CleverHans, Torchattacks, and Adversarial Robustness Toolbox (ART).


## Description

The script provides a step-by-step implementation of the FGSM attack using several adversarial attack libraries. The key sections include:

1. **Fine-tuning ResNet18 on CIFAR-10**:
   - Trains a ResNet18 model on the CIFAR-10 dataset.
   - Saves the trained model for further use in generating adversarial examples.

2. **Preparing Model & Dataset**:
   - Loads the pre-trained ResNet18 model and prepares the CIFAR-10 dataset for evaluation.

3. **General Functions to Compute ASR (Attack Success Rate)**:
   - Defines utility functions to compute the ASR for the given model and attack method.

4. **Attack Implementations**:
   - Provides specific functions for generating adversarial examples using FGSM in:
     - Foolbox
     - CleverHans
     - Torchattacks
     - Adversarial Robustness Toolbox (ART)

5. **Attack Success Rate Calculation**:
   - Computes and prints the ASR for each library using FGSM.

6. **Realizing Attack Success Using A Sample Input**:
   - Demonstrates the success of an adversarial attack on a sample input from the CIFAR-10 dataset.

