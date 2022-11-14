# ImageClassificationUsingCNN

## Problem Statement:

We need to model a NN that can classify whether a given image is Building, Forest or Glacier.

## Dataset:

We are using dataset imorted from Kaggle titled (Intel Image Classification - 6 class dataset).
<br>I've only used 3 class dataset here for reducing the compute duration.

## Libraries used:

os
<br>random
<br>numpy
<br>matplotlib.pyplot
<br>seaborn
<br>sklearn
<br>opencv
<br>tensorflow

## Model:

**For NN model:**

Layers used: 2 Convolution layer and a single gidden layer. (L2-Regularization used)
The output layer has softmax activation with 3 neuron.

The NN model has a good acuracy of about 88 % on test dataset without any problem of overfitting or underfitting.
