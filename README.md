## Overview

This is a neural network model that can classify images into 10 classes with decent accuracy. I chose VGG models as my starting point, then I experimented with different combinations of regularizing techniques, including dropout, batch normalization, and data augmentation to find the best result with optimal model computing time. Combined with an early stopping callback to prevent training with minimal increasing performance, the result is an image classifier model with around 80% accuracy.

## Dataset

CIFAR10 (60000 32x32 color images in 10 classes) 

![image](CIFAR10.png)
