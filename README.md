# GRAD-CAM-Visual-Explanations

This project helps to identify the misclassified images (from pre-trained ResNet18 Model trained on CIFAR10) and using GRAD CAM visualize how the network focuses on important parts of the images to predict the final results. It help you to see through the computer's eyes.

## Steps Involved:

### 1) Setup the pre-trained ResNet18 Model trained on CIFAR10
### 2) Identify 50 misclassified images from the validation set
### 3) Visualize the gallery of these 50 misclassified images
### 4) Run GRAD-CAM on these misclassified images
### 5) Visualize the gallery of these 50 misclassified images along with the GRAD CAM results

## Gallery of 50 misclassified images:
![my_image](/50%20Misclassified%20Images.JPG)

## Gallery of 50 misclassified images with GRAD-CAM:
![my_image](/50%20Misclassified%20Images%20with%20GRAD-CAM.JPG)


References:
http://www.hackevolve.com/where-cnn-is-looking-grad-cam/
