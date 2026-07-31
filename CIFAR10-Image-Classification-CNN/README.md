# CIFAR-10 Image Classification using CNN

## Overview

This project implements an image classification model using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. The model is trained to classify images into one of ten different object categories. The project demonstrates the complete deep learning workflow, including data preprocessing, CNN model development, training, evaluation, visualization of results, and model saving.

---

## Dataset

**Dataset:** CIFAR-10

The CIFAR-10 dataset consists of 60,000 color images of size **32 × 32 pixels** divided into 10 classes.

### Classes

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

### Dataset Split

- Training Images: 50,000
- Testing Images: 10,000

---

## Project Workflow

1. Import required libraries.
2. Load the CIFAR-10 dataset.
3. Visualize sample images.
4. Normalize image pixel values.
5. Build a Convolutional Neural Network (CNN).
6. Compile the model.
7. Train the CNN.
8. Evaluate model performance.
9. Generate predictions.
10. Display the classification report and confusion matrix.
11. Save the trained model.

---

## CNN Architecture

The implemented CNN consists of:

- Convolutional Layer (32 Filters)
- Max Pooling Layer
- Convolutional Layer (64 Filters)
- Max Pooling Layer
- Convolutional Layer (64 Filters)
- Flatten Layer
- Dense Layer (64 Neurons)
- Output Layer (10 Neurons with Softmax Activation)

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## Results

The trained CNN model successfully classifies images from the CIFAR-10 dataset.

Performance was evaluated using:

- Test Accuracy
- Classification Report
- Confusion Matrix

The trained model was saved for future inference and deployment.

---
---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/CIFAR10-Image-Classification-CNN.git
```

Navigate to the project folder:

```bash
cd CIFAR10-Image-Classification-CNN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook to train and evaluate the model.

---

## Future Improvements

- Increase the number of training epochs.
- Apply data augmentation.
- Add dropout layers to reduce overfitting.
- Experiment with deeper CNN architectures.
- Use transfer learning with pretrained models such as ResNet or VGG.

---

