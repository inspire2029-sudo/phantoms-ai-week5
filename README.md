# PHANTOMS AI — Week 5

## Neural Network Foundations with PyTorch

This repository contains my Week 5 work on building and evaluating a fully connected neural network with PyTorch.

## What I built

A feed-forward neural network for handwritten-digit classification using the MNIST dataset.

Architecture:

`784 → 128 → 64 → 10`

- `784` input values from a flattened 28×28 image
- ReLU activation between hidden layers
- `10` output classes for digits 0–9
- Cross-entropy loss
- Adam optimizer

## Workflow

1. Load the MNIST training and test datasets
2. Convert images to tensors
3. Batch data with DataLoader
4. Build the neural network
5. Train with forward pass + backpropagation
6. Evaluate on the held-out test set
7. Track loss and test accuracy
8. Save the trained model as `mnist_model.pth`

## Recorded run

- Training samples: **60,000**
- Test samples: **10,000**
- Epochs: **5**
- Batch size: **64**
- Learning rate: **0.001**
- Random seed: **42**
- Device: CPU in the recorded run
- Final recorded test accuracy: **97.50%**

Test accuracy across the five epochs:

`94.82% → 96.55% → 96.98% → 97.21% → 97.50%`

## Notebook

`W5D1_First_Neural_Network_py.ipynb`

The notebook contains the complete training and evaluation workflow, including loss and accuracy plots.

## Tools

Python · PyTorch · torchvision · Matplotlib

## Learning direction

This work builds the neural-network fundamentals needed to understand modern AI systems before moving deeper into **AI Security and LLM Red Teaming**.

> Build it. Break it. Understand it. Document it.

**Author:** Aya — inspire2029-sudo
