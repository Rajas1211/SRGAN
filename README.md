# SRGAN
Super Resolution using Generative Adversarial Network

## Method

The objective is to develop a deep learning model which processes a low-resolution image to output a high-resolution image, or otherwise known as Super Resolution. For this an image dataset with large number of high-resolution images is used for training. These high-resolution images are converted into low-resolution images. These low-resolution images act as input to the model while its high-resolution version is used as label. The model learns the principle behind super-resolution. Using this principle the trained model thereby outputs high-resolution image of new low-resolution image.

It is an implementation of the paper: https://arxiv.org/abs/1609.04802

## How to run the project?
1. Mount your Google Drive
2. Create the following folders in Google Drive. Edit the folder paths in the code:
    a. training: Folder containing images for training. For this project 800 images from DIV2K dataset were used
    b. testing: FOlder containing images to be tested/used for super resolution
    c. logs: Folder to save log
    d. results
    e: models: to save weights
3. Training can be avoided by using the pretrained weights. Download the pretrained weights from repository and make a copy in Google drive. Update the path in Testing path.
