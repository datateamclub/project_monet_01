# Project_monet_01: I’m Something of a Painter Myself

This beginner-level open competition from Kaggle opened up the doors for our first steps in the _UM - Data Team Club_ to get to work with GAN models.

## Challenges

One of the main challenges was the requirements for installing tensorflow and especially tensorflow-addons. Navigating through the multiple versions of Python, TensorFlow itself, iDisplay, etc., in order for our team to be able to install it was quite an Odyssey. During this proces, we founf this very helpfull [compatibility matrix on github](https://github.com/tensorflow/addons#python-op-compatibility-matrix) that shed a light on the restrictions we should abide to.

## The Model
Our model is heavily inspired on the Link: [Monet CycleGAN Tutorial by Amy Jang](https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial).
This served our purpose on learning and getting to study proficient modeling on the topic.

First we dived on the structure of the model, finding out theres a stablished stucture it should have, as the image shows below, eventhough in between the upsampling and downsampling generator layers more can be added depending on the builder and its preferences.

![Generator and discriminator structures used on GAN models](<image.png>)
