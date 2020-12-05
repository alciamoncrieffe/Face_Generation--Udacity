# Face_Generation--Udacity

Deep learning Course Project 4 : In this project,I used generative adversarial networks to train a DCGAN to generate new images of faces.

### Introduction
The goal is to get a generator network to generate *new* images of faces that look as realistic as possible!

The project is broken down into a series of tasks from **loading in data to defining and training adversarial networks**. At the end of the notebook, you'll be able to visualize the results of the trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

### Get the Data

The training dataset is sourced from the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

This dataset is more complex than the number datasets (like MNIST or SVHN) you've been working with, and so deeper networks and longer training is required them to get good results. GPU is suggested for training.

### Pre-processed Data

The recommendation is to crop and resize the CelebA images to remove parts of the image that don't include a face, then resize down to 64x64x3 NumPy images. Some sample data is show below.

<img src='processed_face_data.png' width=60% />

> If you are working locally, you can download this data [by clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)


