# FashionMNIST-Explainable-CNN
This project implements a high-performance Convolutional Neural Network (CNN) for classifying images from the FashionMNIST dataset using PyTorch. Beyond standard training, it incorporates advanced deep learning engineering practices for accuracy, interpretability, and professional project structure.

⚡ Features

Early Stopping – Stops training when validation loss plateaus to prevent overfitting

Model Checkpointing – Saves the best-performing model automatically

Mixed Precision Training – Accelerates training with reduced memory usage

Confusion Matrix Visualization – Evaluate model predictions across classes

📊 Dataset

FashionMNIST

70,000 grayscale images

10 clothing categories (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)

28×28 resolution

Downloaded automatically via torchvision

🏗 Model Architecture

The model is a custom CNN designed for both performance and interpretability:

Multiple Convolutional layers with ReLU activations

Batch Normalization to stabilize learning

MaxPooling layers to reduce spatial dimensions

Fully Connected (Dense) layers for classification

Dropout for regularization and preventing overfitting
