# <center> KIT Praktikum Neuronale Netze </center> 

The tutorials and exerises are best used with the Praktikum lectures and for someone took the summer-semester KIT Neuronale Netze course. 
For more information, please visit https://ilias.studium.kit.edu/ or http://isl.anthropomatik.kit.edu/english/2667_2747.php

This guideline is for the ones who choose the third option (the own environment and lab machines, eventually you all would need this), 
for the help on Google Colab and/or Kaggle Kernel (at the beginning phase and free GPUs), please visit [the ILIAS  of the PNN WS18/19](https://ilias.studium.kit.edu/ilias.php?ref_id=857604&cmdClass=ilrepositorygui&cmdNode=5r&baseClass=ilRepositoryGUI).

## Installing Prerequisites

I highly recommend installing [Anaconda](https://www.anaconda.com/downloads) (a python scientific package bundle) and use its environment managing feature.

### Anaconda

* Anaconda with python 3.5 (or 3.6)
* CUDA drivers & toolkit 8.0 (if your workstation is Nvidia GPU-enabled or you use our lab machines)

If you are not sure what you are doing, please refer to the steps 1-5 from https://towardsdatascience.com/setup-an-environment-for-machine-learning-and-deep-learning-with-anaconda-in-windows-5d7134a3db10

### Jupyter Notebooks

The tutorials and exerises have been published as Jupyter Notebooks.
If you haven't used Jupyter Notebooks before, here is a good tutorial for beginners: https://www.dataquest.io/blog/jupyter-notebook-tutorial/

### Prerequisites

Install inside the environment those python packages which are needed thoughout the class:
* matplotlib
* seaborn
* scikit-learn 
* other stuffs that you need..

### Install Pytorch 0.4 and torchvision (using Anaconda)

<span style="color:red">We use **Pytorch 0.4**, not 1.0 or other versions.</span> 

* Create an Anaconda environment
* Activate it
* Install [pytorch](http://pytorch.org/) in a suitable way (conda, python version, GPU or not)

### Tensorflow and Keras

If you want to run the sample codes written in Tensorflow and Keras, you need to at first install them. 
Take a look on Step 7 from [the link above](https://towardsdatascience.com/setup-an-environment-for-machine-learning-and-deep-learning-with-anaconda-in-windows-5d7134a3db10).

We use Tensorflow 1.11 and Keras with Tensorflow backend. 

### Courtesy
Many ideas and examples in this course, especially the exercises are inspired from:
* Deep Learning Specialization, Andrew Ng et al., Coursera
	(https://www.coursera.org/specializations/deep-learning)
* Neural Networks for Machine Learning Course, Geoffrey Hinton et al., Coursera
	(https://www.coursera.org/learn/neural-networks)
* CS231N Convolutional Neural Networks for Visual Recognition, Fei-Fei Li et al., Stanford University.
	(http://cs231n.stanford.edu/)
* CSC 321 Intro to Neural Networks and Machine Learning, Roger Grosse et al., University of Toronto.
	(http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/)

### Questions and Helps
If you have any question, please visit [the ILIAS  of the PNN WS18/19](https://ilias.studium.kit.edu/ilias.php?ref_id=857604&cmdClass=ilrepositorygui&cmdNode=5r&baseClass=ilRepositoryGUI) or write an email to [thanh-le.ha@kit.edu](mailto:thanh-le.ha@kit.edu)
	

