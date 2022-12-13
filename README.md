# COM576
The final project of COM576- Scene Classification and Grad-CAM Visualization

## Proposal:
During the class, we have learned about convolutional neural networks. In this project, we will build and train a Deep Convolutional Neural Network (CNN) to detect the type of scenery in an image. We will use a technique known as Gradient-Weighted Class Activation Mapping (Grad-CAM) to visualize the regions of the inputs and help us explain how our CNN models think and make decision.

## Problem definition
Create a machine learning model that will classify the different imagery, with a Grad-Cam.

## Motivation
Want to build powerful Neural network that can classify these images with more accuracy. During the class, we have learned about convolutional neural networks. Therefore, we think if we could use CNN to solve this problem.

## Related works
The estimated steps will be:
1.	Understand the theory and intuition behind Deep Neural Networks, Residual Nets, and Convolutional Neural Networks (CNNs).
2.	Apply Python libraries to import, pre-process and visualize images.
3.	Perform data augmentation to improve model generalization capability.
4.	Build a deep learning model based on Convolutional Neural Network and Residual blocks using Keras with Tensorflow 2.0 as a backend.
5.	Compile and fit Deep Learning model to training data.
6.	Assess the performance of trained CNN and ensure its generalization using various KPIs such as accuracy, precision and recall.
7.	Visualize the Activation Maps used by CNN to make predictions using Grad-CAM.
8.	Deploy the model using Tensorflow Serving

## Proposed algorithm
Convolutional Neural Networks (CNNs)
Grad-Cam

## Experiments
we will look at classifying scenes into one of 6 categories- buildings, forest, glacier, mountain, sea, and street. The objective is to use a technique called GradCam to visualize the portions of the image that enable the model to classify.

## Datasets of interest
•	This dataset contains about ~25k images from a wide range of natural scenes from all around the world. The task is to identify which kind of scene can the image be categorized into.
•	It is a 6-class problem - Buildings, Forests, Mountains, Glacier, Street, Sea

