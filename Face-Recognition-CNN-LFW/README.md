# Face Recognition Using CNN (LFW Dataset)

## Overview

This project implements a Convolutional Neural Network (CNN) for face recognition using the Labeled Faces in the Wild (LFW) dataset. The model learns facial features from grayscale images and classifies faces into multiple person categories.

The project demonstrates the complete deep learning workflow, including data preprocessing, CNN model development, training, evaluation, prediction, and model saving.

---

## Dataset

**Dataset:** Labeled Faces in the Wild (LFW)

The dataset contains face images of different individuals collected under real-world conditions. Images are preprocessed into grayscale and resized for CNN training.

---

## Project Structure

```
Face-Recognition-Using-CNN-LFW/
│
├── data/
├── images/
├── models/
│   └── face_recognition_cnn.keras
├── notebook/
│   └── Face_Recognition_CNN.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Workflow

1. Import required libraries.
2. Load the LFW dataset.
3. Explore and visualize sample face images.
4. Normalize image pixel values.
5. Reshape images for CNN input.
6. Encode class labels.
7. Split the dataset into training and testing sets.
8. Build the CNN model.
9. Compile and train the model.
10. Evaluate model performance.
11. Generate predictions.
12. Display the classification report.
13. Plot the confusion matrix.
14. Visualize training and validation accuracy.
15. Visualize training and validation loss.
16. Save the trained CNN model.

---

## CNN Architecture

- Convolution Layer (32 Filters)
- Max Pooling Layer
- Convolution Layer (64 Filters)
- Max Pooling Layer
- Flatten Layer
- Dense Layer (128 Units)
- Dropout Layer
- Output Layer (Softmax)

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix
- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

---

## Model Output

The trained model is saved as:

```
models/face_recognition_cnn.keras
```

---

## Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Results

The CNN model successfully learns facial features from the LFW dataset and performs multi-class face recognition. Performance is evaluated using classification metrics and visualizations of accuracy, loss, and the confusion matrix.

---

## Future Improvements

- Train for more epochs.
- Apply data augmentation.
- Use transfer learning models such as VGG16, ResNet50, or MobileNetV2.
- Improve recognition accuracy through hyperparameter tuning.
- Build a real-time face recognition application using OpenCV.

---

