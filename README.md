# CIFAR-10-Image-Classification

Welcome to the CIFAR-10 Image Classification repository! This repository contains code and resources for performing image classification using the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The goal of this project is to demonstrate various techniques for image classification, including convolutional neural networks (CNNs), data augmentation, dimensionality reduction, and support vector machine (SVM) classification.

Project Highlights
Data Preprocessing: The CIFAR-10 dataset is loaded and preprocessed to prepare it for training and testing.

Convolutional Neural Network (CNN) Model: A CNN model is built using TensorFlow and Keras, comprising convolutional layers, max-pooling layers, dropout for regularization, and fully connected layers.

Data Augmentation: Augmentation techniques are applied to the training data using TensorFlow's ImageDataGenerator, enhancing the model's robustness.

Model Training and Evaluation: The CNN model is trained on the augmented data and evaluated on the testing dataset to measure its accuracy.

Support Vector Machine (SVM) Classifier: An SVM classifier is trained using the flattened data and tuned using GridSearchCV for optimal hyperparameters.

Principal Component Analysis (PCA): PCA is applied to visualize the data in a reduced-dimensional space using Plotly Express for a 3D scatter plot.

Image Prediction: A trained CNN model is used to predict the class of an example image from a URL.

Visualization: Training accuracy and loss curves are plotted to visualize the model's training progress.

Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine.
Install the required dependencies.
Run the provided code to train and evaluate the CNN model, perform SVM classification, and visualize the results.
Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.
