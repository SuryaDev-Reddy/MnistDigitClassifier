# MnistDigitClassifier using Keras and TensorFlow

## **Introduction**

In this Assignment, I developed a multilayer perceptron model which uses ADAM Optimizer to acheive good performance on the MNIST handwritten dataset. I'm going to use Keras with TensorFlow.

## **MNIST Dataset**

This dataset was constructed from a number of scanned document datasets availabe from the National Institute of Standards and Technology (NIST). These images were normalized in size and centered. Each image is in a 28x28 square (784 pixels). 60,000 images were used to train a model and 10,000 were used to test it. Excellent results achieve a prediction error of 1%.

## **Baseline Model with Multilayer Perceptrons**

To build a multilayer perceptron model, we flatten our 28 by 28 pixel images into a single 784 length vector for each image. We then change the grayscale values from 0-255 to 0-1 to make things easier on our neural network. (Normalization) Finally, we change the categories 1-9 into a binary matrix. The current neural network structure is as follows:

Visible Layer (784 Inputs) >> Hidden Layer (784 Neurons) >> Output Layer (10 Outputs)
