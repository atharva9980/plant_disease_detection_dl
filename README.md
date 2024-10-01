# Plant Disease Prediction Using CNN

This project implements a Convolutional Neural Network (CNN) for classifying plant diseases using the **PlantVillage Dataset**. The model is trained on color images of plant leaves and predicts the type of disease affecting the plant.

## Project Overview

The steps involved in the project include:
- Data curation using Kaggle's **PlantVillage dataset**.
- Data preprocessing and augmentation for better generalization.
- Building and training a CNN model using TensorFlow/Keras.
- Evaluating the model's performance on unseen data.
- Saving the trained model and building a predictive system for real-time image classification.

## Dataset

The dataset used is the **PlantVillage Dataset**, which contains segmented images of healthy and diseased plant leaves. The dataset consists of 38 classes, each representing a unique disease or a healthy plant.

### Dataset Source

The dataset can be downloaded from Kaggle: [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)

## Project Dependencies

Install the necessary packages before running the project:
```bash
pip install numpy pandas matplotlib tensorflow pillow kaggle
