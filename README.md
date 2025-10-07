# 🚦 Industry Level Project: Traffic Sign Recognition (CNN)

## Overview
This project represents the completion of **Task 8 (Industry Level)** in the Elevvo Machine Learning Internship. The goal was to build a robust model capable of classifying the 43 different types of traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset. This project demonstrates proficiency in **Deep Learning and Computer Vision**.

## Key Outcomes and Techniques
The solution employs a Convolutional Neural Network (CNN) and advanced image processing techniques to achieve high accuracy:

1.  **Image Preprocessing:** Images were loaded, converted to Grayscale (single channel), resized to **(32x32)**, and normalized (0-255 to 0-1) to standardize the input for the CNN.
2.  **CNN Architecture:** A custom Sequential CNN model was designed using multiple `Conv2D` and `MaxPooling2D` layers, followed by `Dropout` layers to prevent overfitting.
3.  **Data Augmentation (Bonus):** Applied an `ImageDataGenerator` with transformations (rotation, zoom, shift) to artificially expand the training dataset, significantly boosting the model's generalization capabilities.
4.  **Model Evaluation:** Performance was measured on a separate test set, confirming the model's robustness.

## Performance Results

| Metric | Result |
| :--- | :--- |
| **Final Test Accuracy** | **[أدخل القيمة النهائية هنا]%** |
| **Model Type** | Convolutional Neural Network (CNN) |
| **Classification Type** | Multi-class Classification (43 classes) |

## Files in Repository
* `Traffic_Sign_Recognition_CNN.ipynb`: The main code file containing the full workflow (Preprocessing, Model Building, Training, and Evaluation).
* `model_weights.h5`: The saved weights of the final trained CNN model, allowing quick loading for inference without retraining.
* `README.md`: This documentation file.
* `requirements.txt`: List of all required Python packages.

## How to Run
1.  **Dependencies:** Install required libraries (see `requirements.txt`).
2.  **Data:** Download the GTSRB dataset from Kaggle and place it in the appropriate input path.
3.  **Execution:** Run the `Traffic_Sign_Recognition_CNN.ipynb` notebook sequentially.

---
