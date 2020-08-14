# SRGAN
Super Resolution using Generative Adversarial Network (GAN)

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

Following is the result of training the network on 800 images and 30,000 Epochs. The results can be substantially improved using more images (~5000) and increasing number of Epochs (~1,00,000).

![door](https://user-images.githubusercontent.com/60413242/89576630-723ac600-d827-11ea-8dc0-5c2d73dcae1d.png)
![face image](https://user-images.githubusercontent.com/60413242/89576635-736bf300-d827-11ea-854b-18c2e6d6ba47.png)
![floating house](https://user-images.githubusercontent.com/60413242/89576639-74048980-d827-11ea-8aa5-35985648b6e1.png)
![man dessert](https://user-images.githubusercontent.com/60413242/89576642-749d2000-d827-11ea-98bd-51c52ece951f.png)
![marked image](https://user-images.githubusercontent.com/60413242/89576645-7535b680-d827-11ea-9db6-0d330ec6f4b8.jpg)
![pebbles](https://user-images.githubusercontent.com/60413242/89576647-7535b680-d827-11ea-9812-e855c5566a06.png)
![star fish](https://user-images.githubusercontent.com/60413242/89576648-75ce4d00-d827-11ea-8d1f-bb0213c610e6.png)
