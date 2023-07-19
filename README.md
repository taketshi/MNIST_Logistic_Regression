# MNIST_LogReg
Simple implementation of Logistic Regression to the MNIST dataset. Attempted input generation.

## Description
On the jupyter notebook __main.ipynb__ I try a simple implementation of Logistic Regression on the MNIST dataset. It is also tested a slightly more complex NN with regularization. 
<br/>
Finally, it is (unsuccessfuly) attempted to generate an input of a specific number which minimizes the loss function wrt the target number. I believe it failed because the NN is not learning what we consider to be the crucial parts of the numbers shape. Perhaps a sort of dimensionality reduction would be advantageous because it could remedy this.

## Shape
main.ipynb: the main body<br/>
classes: contains the .py files with the classes<br/>
  NN.py: contains the general NN using pytorch. Check taketshi/NN_torch<br/>
  LogisticRegression.py: contains a numpy implementation of a logistic regression with gradient descent

## Dependencies 
- main.ipyn
from classes.NN import NN<br/>
import torch<br/>
import torch.nn as nn<br/>
import torch.nn.functional as F<br/>
import matplotlib.pyplot as plt<br/>
from keras.datasets import mnist<br/>

  
