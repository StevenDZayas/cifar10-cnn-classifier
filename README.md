# cifar10-cnn-classifier

This project is a CIFAR-10 image classifier, using a Convolutional Neural Network. The project is written in Python, with utilization of both the Pytorch and Numpy libraries, and implemented in Jupyter Notebooks. The project is a modified version of an exercise from the Udacity course, "Intro to Deep Learning with Pytorch", with the relevant section (Lesson 5) on Convolutional Neural Networks taught, and the pre-existing code written by, Cezanne Camacho.

This project was undertaken as one of my first machine learning projects, buttressed by pre-existing tutorial code in order to familiarize myself with both the specific implementation of a machine learning model, and the overall structure and sequence of its parts. With my next goal being to build a MRI anomaly classifer, and possibly other projects existing within the intersection of artificial intelligence and medicine, this basic CIFAR-10 classifier served as a robust introduction to the general concepts and implentation of a machine learning model, in a way that I hope to apply to other upcoming projects.

What follows are some important details as to the data sizes, chosen hyperparameters, and more.
<ul>
<li>The CIFAR-10 dataset consists of 60,000 original 3x32x32 images (3 RGB color channels each, with pixel dimensions of 32x32), with 50,000 training images, and 10,000 test images.</li>
<li>Size of validation set: 20% (of 50,000 original training examples); 50,000 x 0.2 = 10,000 validation examples</li>
<li>Weight-training set: 40,000 (remainder after reservation of validation set)</li>
<li>Batch size: 20</li>
<li>Batches/iterations: 2000 (2000 batches of 20 examples each = 40,000 training examples)</li>
</ul>

Important links:
Intro to Deep Learning with Pytorch: https://classroom.udacity.com/courses/ud188
Pytorch: https://pytorch.org/
https://numpy.org/
