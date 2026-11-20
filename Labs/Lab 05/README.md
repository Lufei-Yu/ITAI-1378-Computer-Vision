# Lab 05 – Chihuahua or Muffin with CNN

## 1. Problem Statement

The objective of this lab is to build an image classification model using a **Convolutional Neural Network (CNN)** to distinguish between Chihuahua dogs and muffins.

The "Chihuahua or Muffin" challenge is a well-known computer vision problem because these two categories can have surprisingly similar visual characteristics, including shapes, colors, and textures.

The goal is to train a CNN model that can automatically identify and classify images into two categories: Chihuahua or Muffin. This lab demonstrates how deep learning techniques can extract visual features and recognize complex patterns from image data.

## 2. Approach

This lab follows a CNN-based image classification workflow:

- **Data Collection:** Load Chihuahua and muffin images for model training and evaluation.
- **Image Preprocessing:** Resize images into a consistent input size and normalize pixel values.
- **Data Preparation:** Organize images and their corresponding labels into classification categories.
- **CNN Architecture:** Build a Convolutional Neural Network using convolutional and pooling layers to extract important image features.
- **Feature Extraction:** Use convolutional filters to identify patterns such as edges, shapes, textures, and other visual characteristics.
- **Model Training:** Train the CNN using labeled images so the model can learn the differences between Chihuahuas and muffins.
- **Model Evaluation:** Evaluate the trained model using unseen images to measure its classification performance.
- **Prediction:** Use the trained model to predict whether a new image contains a Chihuahua or a muffin.

## 3. Results

The CNN model demonstrates how deep learning can be applied to binary image classification.

Through the training process, the model learns visual patterns and features that help distinguish between Chihuahua and muffin images.

The experiment provides practical experience with:

- Training a CNN for image recognition.
- Monitoring training and validation performance.
- Evaluating image classification predictions.
- Understanding how deep learning models recognize visually similar objects.

The final classification results can be observed through the notebook's training outputs, evaluation metrics, and prediction examples.

## 4. Key Findings

- CNNs are effective for image classification because they automatically learn important visual features.
- Convolutional layers extract patterns such as edges, textures, and shapes from images.
- Pooling layers reduce feature-map dimensions while retaining important information.
- Image preprocessing helps provide consistent input data for model training.
- Training and validation performance help evaluate how well the model learns and generalizes.
- Visually similar objects can create challenges for image classification, making feature extraction especially important.
- Deep learning can identify subtle visual differences that may be difficult to recognize through simple image processing techniques.

## 5. Technologies Used

- **Python** – Main programming language.
- **Jupyter Notebook** – Interactive environment for developing and executing the lab.
- **CNN (Convolutional Neural Network)** – Deep learning architecture for image classification.
- **TensorFlow / Keras or PyTorch** – Deep learning framework, depending on the notebook implementation.
- **NumPy** – Numerical operations and data processing.
- **Matplotlib** – Visualization of images and training results.
- **Image Processing** – Image resizing, normalization, and preprocessing.

## 6. How to Run

Open the notebook in Jupyter or Google Colab.
