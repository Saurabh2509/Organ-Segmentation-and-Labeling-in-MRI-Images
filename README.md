# Organ-Segmentation-and-Labeling-in-MRI-Images

The objective of the project is to determine class of a galaxy from its image or video. Galaxy shapes forms the basis of classification of  galaxies.

## Name
Convoloutional Cosmos- Classification of galaxies.

## Description
The objective of the project is to determine class of a galaxy from its image or video. Galaxy shapes forms the basis of classification of Galaxies. Three major shapes of galaxies are noticed by scientists: elliptical, spiral and irregular. As we know  orbit of planets are elliptical due to gravitational force. Similarly galaxies which are group of stars also form shape similar to symmetric curves due to mutual gravitation between stars. Stars are in constant motion with respect to each other due to gravitational pull which cause galaxies to rotate. Irregular galaxies are exception from above circular shapes and do not have any symmetric shape. This is due to lot of elemental Hydrogen or dust in these galaxies. As we also see on earth dust particles do not form any regular shape thus the reason behind shape of irregular galaxies.

## Background
The Galaxy classification was given initially by Edwin P Hubble in 1926 and later extended by scientist: Gerard de Vaucouleurs.
* Elliptical Galaxies: The spherical form in 3D appears to us as circular shape in 2D. These are classified into E0 which are perfectly circular to E7 which are most flattened. These are brightest at center and brightness diminishes moving away from center.
* Spiral Galaxies: These have three major components: bulge, disk and halo. Bulge is central portion which consists of old stars. Arm is the linear portion of stars which are in circular motion around bulge and is made of dust and younger stars. Halo is the spherical part around bulge and covers some part of disk. Arms emerge directly from bulge (ordinary spiral) or from a bar of material around bulge (barred spiral). They are also further classified into lower case letters: ‘a’, ‘b’,‘c’.. on how tightly the arms are bound to bulge. The category ‘a’ have most tightly bound arms.
* Irregular Galaxies: These are classified into Irregular I or Irregular II. First category has lot of elemental Hydrogen and young stars. Irregular II has lot of dust that makes the distinct stars not clearly visible.

## Methodology
* Step 1: Collection of photos of several galaxies.
* Step 2: Manually classifying photos in one of three major classes.
* Step 3: Simulating the prediction by a CNN image classification. Training data consists of images of galaxies in 3 types into 3 folders which will be read by CNN as 3 types of images.
* Step 4: On giving a test image the CNN will automatically tell the type of galaxy as which training class it is matching to.
#### Architectural diagram for workflow of CNN
![Proj1](/uploads/bd05333623b0dcd903dc8761d236dcf0/Proj1.jpg)
#### Types of galaxies
![Proj2](/uploads/d84d75a6de2cac11e9bd00d129bb16ad/Proj2.jpg)

## Experimental Design
#### Dataset:
* Step 1: The galaxy photos are collected from url: http://hubblesite.org/images/gallery and https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data
* Step 2: CNN is trained using python keras and tensor flow to create a weights files from training dataset.
* Step 3: Testing image is given to trained CNN and checked which class it is predicting the image to be.
## Evaluation Measures: 
The test validation set is prepared before testing on a new image and when CNN predicts the class images belong to we count the number of images correctly classified and divide by total number of images to get the accuracy value.
## Software and Hardware Requirements:
Anaconda with spyder is used for CNN which uses python libraries of keras and tensorflow. The hardware needed will be of multi core fast processor or a GPU machine to train on large dataset with epochs more than 40. This will take training time nearly equal to 1 hour. After saving these weights we get a trained model and this is used to predict new image class. 
The CNN can be multi layer with 3-4 hidden layers and 3 classes or categories with Relu (Rectified Linear Unit) activation function. The loss function used will be adams optimizer and categorial cross entropy.

## Usage
Can be implemeted in Space research work for studying of galaxies directly from model which will save a lot of time.
## Support
In case of any discussion or any suggestion reach us @
* discord- https://discord.gg/BxAu9qunMz
* mail- aarushkumar100616@gmail.com
## Roadmap
After successfully implementation of the project we will deploy it and too have a plan to deploy it on a separate webpage.
## Contributing
We are open to contributions.
If you wanna contribute you must have a knowldege of CNN and basic EDA part of Machine Learning and your suggestions are welcomed heartly.

## Author:
Aarush Kumar

## Acknowledgement:
I would like to thank my friends for supporting me with my project and hope we will do it great.
* Aakash Kumar Sahoo
* Abhijeet Kumar Ghosh 
* Saurabh Kumar
* Vansham Rastogi

## License
Will be released under Apache Community LICENSE.

## Project status
We are under the working, up and running state of the project hope we will come out with facinating result soon.

# Thankyou!!!
