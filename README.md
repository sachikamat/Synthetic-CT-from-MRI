
# Synthetic CT from MRI

The use of synthetic CT images generated from MR image data is increasing because they offer a number of potential advantages over traditional CT scans, including improved safety, greater detail, and the ability to generate 3D models for surgical planning.

This project was done to create a robust deep learning model which is capable of generating synthetic CT images from MR images. It is an implementation of  ["MR‐based synthetic CT generation using a deep convolutional neural network method." Medical physics 2017](https://sci-hub.se/10.1002/mp.12155)


## Requirements

* tensorflow 2.6.4
* numpy 1.21.6
* openCV 4.5.4
* matplotlib 3.5.3
* pandas 1.3.5
* keras 2.6.0


## Dataset

This [dataset](https://drive.google.com/drive/folders/1fQY2MBGqvxS7fx4aDYyxUFDHhxTjxD_y) contains 367 paired CT and MR images which have been randomly divided into training, test and validation set. 

