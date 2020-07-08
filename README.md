# deep-learning-gan-face-generation (pytorch, aws gpu, cuda, python, GAN)

Define and train a DCGAN on a dataset of faces. The goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project is broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

Get the Data
You'll be using the CelebFaces Attributes Dataset (CelebA) to train your adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) you've been working with, and so, you should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training.
