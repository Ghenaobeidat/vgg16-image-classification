# Attention-Enhanced VGG16 Image Classification

Deep learning project for multi-class image classification using the **VGG16 convolutional neural network**.  
The model was trained to classify images into five different object categories.

## Technologies
- Python
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)

## Dataset
The dataset contains five image classes:
- Car
- Building
- Person
- Tree
- Lab

Images were preprocessed and augmented to improve model generalization.

## Model
The system uses a **VGG16 backbone with a custom classification head**, including:
- Global Average Pooling
- Dropout for regularization
- Fully connected layers for classification

## Results
The proposed model achieved **93% classification accuracy** on the test dataset.
