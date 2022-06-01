# Generative Adversarial Networks GANs-

GANs perform unsupervised learning tasks in machine learning. It consists of 2 models that automatically discover and learn the patterns in input data. 

The two models are known as Generator and Discriminator.

They compete with each other to scrutinize, capture, and replicate the variations within a dataset. GANs can be used to generate new examples that plausibly could have been drawn from the original dataset.

# 1) Discriminator 
It is a supervised approach. It is a simple classifier that predicts data is fake or real. It is trained on real data and provides feedback to a generator.

# 2) Generator 
It is an unsupervised learning approach. It will generate data that is fake data based on original(real) data. It is also a neural network that has hidden layers, activation, loss function. Its aim is to generate the fake image based on feedback and make the discriminator fool that it cannot predict a fake image. And when the discriminator is made a fool by the generator, the training stops and we can say that a generalized GAN model is created.

# Steps to Implement Basic GAN
Importing all libraries

Getting the Dataset

Data Preparation – It includes various steps to accomplish like preprocessing data, scaling, flattening, and reshaping the data.

Define the function Generator and Discriminator.

Create a Random Noise and then create an Image with Random Noise.

Setting Parameters like defining epoch, batch size, and Sample size.

Define the function of generating Sample Images.

Train Discriminator then trains Generator and it will create Images.

Will see what clarity of Images is created by Generator.

