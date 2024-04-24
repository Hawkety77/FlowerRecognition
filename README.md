# Flower Recognition
This repository contains code that uses a convolutional neural network and transfer learning to classify flowers into 5 classes. The current model achieves a 93% accuracy on the test set. The architecture is based on the DenseNet201 model and it's pre-trained weights on the imagenet dataset.

## Files
- CNN.py: Main script that trains the CNN and predicts on the test images.
- training_labels.csv: Labels for the training set.

## Directories
- testing/: Contains flower images without labels.
- training/: Contains flower images with labels.
- ScrapeFloweres/: Contains code to use Pexel's API to download additional flower images to use in training.
