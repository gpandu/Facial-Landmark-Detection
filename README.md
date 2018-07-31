# Facial-Landmark-Detection

This Repo contains Facial-Landmark-Detection using CNN

In this Project, I have implemented Facial landmarks(key points) detection system using Convolution Neural network and image processing techniques. Facial landmark detection is regression kind of task where output is a set of values representing positions in the image rather than one hot encodings that we use generally for classification task.This project uses Keras with TensorFlow in the backend, opencv and dlib libraries. Once we train the landmarks detection model, it will be used for for testing on real time images. For any task of processing facial features on real-time images, first step will be detecing the faces in the image. Face detection task is achieved by using dlib's implementation. Once faces are detected, we will feed them to the trained model to predict the landmarks. This complete project contains following three parts:

Part1: Includes loading dataset and processing images data to convert them into tensors.
Part2: Training and testing a model trained with the data using Convolution Neural network.
Part3: Preprocessing real-time image to detect faces and feeding it to trained model to predict landmarks.
