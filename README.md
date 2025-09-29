# CIFAR10-Image-Classifier


This project implements an image classifier for the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) using Convolutional Neural Networks in PyTorch.  
CIFAR-10 contains 60,000 32×32 color images across 10 classes:
`airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck`.

The goal is to train a CNN to classifies each image into one of the 10 categories.


## Project Features
- Custom CIFAR-10 loader from Python batch files
- Train/validation/test split
- Data visualization
- CNN implementation in PyTorch
- Evaluation using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

Model achieved ~89% accuracy
