# Road Object Recognition (Self Driving Cars)

Original, Unsplit, Dataset: [Link](https://drive.google.com/file/d/1L1JONuGRwtdeGCYYQjBqL_fgB9l__R8Q/view?usp=sharin://drive.google.com/file/d/1L1JONuGRwtdeGCYYQjBqL_fgB9l__R8Q/view?usp=sharing)

---

Install all dependecies using `pip install -r requirements.txt`

---

## Introduction

Autonomous vehicles rely heavily on cameras as a primary sensor for perceiving the environment
around them. Cameras capture images of the surrounding environment, which are then processed by
the vehicle's computer vision algorithms to identify and track objects, such as other vehicles,
pedestrians, and road markings. They help the vehicles to "see" and interpret their surroundings, which
is essential for making real-time decisions about how to respond to changing road conditions and avoid
collisions.
To make sense of the camera data, the images captured by the cameras are processed by machine
learning algorithms that are trained to recognize various objects and features, such as traffic signs, lane
markings, and obstacles.
Deep learning is a type of machine learning that uses artificial neural networks to learn from large
datasets. In the context of autonomous vehicles, deep learning can be applied to improve the
performance of the computer vision algorithms that process camera data.
One way deep learning is used in autonomous vehicles is through a technique called Convolutional
Neural Networks (CNNs). CNNs are designed to automatically learn and extract features from images. In
the case of autonomous vehicles, CNNs can be trained on large datasets of labeled images to recognize
various objects and features in the environment, such as cars, pedestrians, traffic lights, and road
markings. Once trained, the CNNs can be integrated into the computer vision algorithms used in
autonomous vehicles to help them better detect and identify objects in the environment. For example, a
CNN can be used to detect and track pedestrians in real-time, which can help the vehicle avoid
collisions.

## Tasks

You’re provided with an image dataset (vehicle_classification.zip) that contains 8 different classes of
vehicles:

***Bicycle, Bus, Car, Motorcycle, NonVehicles, Taxi, Truck, Van.***

The goal is to train a CNN that can classify these different types of vehicles.
This can be divided into several steps:

1. Load the data.
2. Divide the dataset into a training set and a testing set with a ratio of 8:2.
3. Build a CNN model that takes an image (or a batch of images) as input and output the class that
the input image(s) are belonging to.
4. Train the model and keep track of the loss and accuracy.
5. Print the final accuracy.
6. (Optional) Plot the loss and accuracy curve during the training.
You’re recommended to use Python programming language and PyTorch library for the implementation.

## Submission & Evaluation

You need to submit your source code and the output when you’re running the code.
The output should contain the final accuracy on the training set and the testing set. Plotting the loss and
accuracy curve are optional. You can put the output in a text file or make a screenshot. If you’re using
Jupyter Notebooks (or Google Colab) you can submit the notebook file (.ipynb)