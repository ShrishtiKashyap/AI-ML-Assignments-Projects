# Brain MRI Tumor Detection using CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) to classify brain MRI images into two categories:

- Tumor
- No Tumor

The model is trained on MRI images using TensorFlow/Keras and evaluates its performance using accuracy, confusion matrix, and classification report.

---

## Dataset

Dataset: Brain MRI Images for Brain Tumor Detection

Folder Structure:

```
dataset/
├── yes/
└── no/
```

- **yes/** : MRI images containing brain tumors
- **no/** : MRI images without brain tumors

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```
Brain-MRI-Tumor-Detection-CNN/
│
├── dataset/
│   ├── yes/
│   └── no/
│
├── models/
│   └── brain_tumor_cnn.h5
│
├── Cancer_Detection.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Workflow

1. Import required libraries
2. Load MRI images
3. Resize images
4. Normalize pixel values
5. Encode labels
6. Split data into training and testing sets
7. Build a CNN model
8. Train the model
9. Evaluate model performance
10. Generate confusion matrix
11. Generate classification report
12. Save the trained model

---

## CNN Architecture

- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- Output Layer (Softmax)

---

## Model Evaluation

The model is evaluated using:

- Test Accuracy
- Test Loss
- Confusion Matrix
- Classification Report

---

## Output

The project produces:

- Trained CNN model
- Accuracy and Loss graphs
- Confusion Matrix
- Classification Report
- Tumor prediction on MRI images

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Improve accuracy using data augmentation
- Experiment with transfer learning models
- Deploy the model as a web application
- Support multi-class brain tumor classification

---

## Author

Shrishti Kashyap