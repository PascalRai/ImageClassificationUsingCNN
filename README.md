# ImageClassificationUsingCNN

## Problem Statement:

WWe need to model a NN that can classify whether a given image is Building, Forest, Glacier, Mountain, Sea, or Street.

## Dataset:

We are using dataset imorted from Kaggle titled (Intel Image Classification - 6 class dataset).
<br>I've only used 3 class dataset here for reducing the compute duration on 1 model.

<br>The other model uses all 6 lables and uses a gpu for modeling.

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

**For 3 label problem: (cpu computation)**

Layers used: 2 Convolution layer and a single dense layer. (L2-Regularization used)
The output layer has softmax activation with 3 neuron.

The NN model has an accuracy of about 86 % on test dataset without any problem of overfitting or underfitting.

**For 6 label problem: (gpu computation)**

Layers used: 10 Convolution layer and 2 dense layer. 
The output layer has softmax activation with 6 neuron.

The NN model has an accuracy of about 78 % on test dataset without any problem of overfitting or underfitting.
