# image-classification
Image classification with Keras and TensorFlow

**Objective:**

The aim of this project is to develop a Convolutional Neural Network model to classify images of Dogs and Cats and especially to demostrate how to : 
* Handle big image datasets using Data Generators to feed CNN on the go trough small batches of images during training without having to load the entire heavy dataset at once in memory 
* Tackle overfitting using techniques like Data Augmentation and Regularization dropouts
* Use Transfer learning with inceptionV3 model that was trained on millions of images with extremely high computing power and finetune it to our usecase to imporve furthermore our prediction performance

**Input data:**

A sample of 3000 images of cats and dogs sampled from the original dataset of 25000 images
