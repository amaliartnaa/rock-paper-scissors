# Rock Paper Scissors Image Classifier

This project is a Convolutional Neural Network (CNN) model that classifies hand gesture images into three categories: rock, paper, or scissors. It was developed as the **final project** for the Dicoding certification course titled **"Belajar Machine Learning untuk Pemula"** as part of the Machine Learning Engineer training path.

The dataset was divided into training and validation sets, with real-time data augmentation applied (rotation, flipping, zooming, etc.) to improve the model's generalization. The model was built using TensorFlow and Keras Sequential API with multiple convolutional and pooling layers, followed by dense and dropout layers.

Training achieved over **96% accuracy**, with **100% validation accuracy**, and the final model was used to classify uploaded hand gesture images.

## Key Features

* CNN model with three Conv2D layers and dropout regularization
* Image augmentation using `ImageDataGenerator`
* Custom training and validation data pipeline
* Real-time image upload and prediction
* High model accuracy and generalization

## Tools

* Python
* TensorFlow & Keras
* Google Colab
* Matplotlib
* NumPy

## Result

* Training Accuracy: \~96.88%
* Validation Accuracy: 100.00%
* Saved model in `.keras` format

This project demonstrates fundamental skills in computer vision and deep learning using Python and TensorFlow.
