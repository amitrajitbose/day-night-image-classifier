### Day Night Image Classifier

###### Problem Statement
Given an outdoor image, classify whether it was captured during day or night, with good level of confidence and accuracy.

###### Dataset
The dataset used for the project is a smaller version of the huge [AMOS dataset](http://cs.uky.edu/~jacobs/datasets/amos/) *(Archive of Many Outdoor Scenes)*.

###### Aim
We'd like to build a classifier that can accurately label these images as day or night, and that relies on finding distinguishing features between the two types of images!

###### Training & Testing Data
The 400 total images are separated into training and testing datasets.

60% of these images are training images, for you to use as you create a classifier.
40% are test images, which will be used to test the accuracy of your classifier.
First, we set some variables to keep track of some where our images are stored:

*image_dir_training*: the directory where our training image data is stored

*image_dir_test*: the directory where our test image data is stored
