# Project_monet_01: I’m Something of a Painter Myself

This beginner-level open competition from Kaggle opened up the doors for our first steps in the **UM - Data Team Club** to get to work with GAN models.

## Challenges
One of the main challenges was the requirements for installing tensorflow and especially tensorflow-addons. Navigating through the multiple versions of Python, TensorFlow itself, iDisplay, etc., in order for our team to be able to install it was quite an Odyssey. During this process, we found this very helpfull [compatibility matrix on github](https://github.com/tensorflow/addons#python-op-compatibility-matrix) that shed a light on the restrictions we should abide to.

Another challenge was getting to wrap our heads arround the algebra that supports this model layers and transformations. We relied on explanations on the internet like [Kaggle on Convolution and Relu](https://www.kaggle.com/code/ryanholbrook/convolution-and-relu) or videos such as [Transposed Convolutions Explained by Johannes Frey](https://www.youtube.com/watch?v=xoAv6D05j7g)

## The Model
Our model is heavily inspired on the [Monet CycleGAN Tutorial by Amy Jang](https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial).
This served our purpose on learning and getting to study proficient modeling on the topic.

First we dived on the structure of the model, finding out theres a stablished stucture it should have, as the image shows below, eventhough in between the upsampling and downsampling generator layers more can be added depending on the modeling agent and its preferences.

![Generator and discriminator structures used on GAN models](<structure_model.png>)


## Future steps
Definetely having ended this simple proyect paves the way for more complex modellings to be done the **Team**, mainly when thinking about creating our own adaptations on a GAN or even the whole model by ourselves.
