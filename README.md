# BNN-inference-with-ReRAM-bridges-and-capacitive-neurons
Repository to reproduce the neural network inference results of the article "Implementation of Binarized Neural Networks Immune to Device Variation and IR Drop Employing Resistive RAM Bridges and Capacitive Neurons."

# Requirements
To set the environment run in your conda main environment:

```
conda config --add channels conda-forge
conda create --name environment_name
conda activate environment_name  
conda install python=3.7 pytorch=1.4 torchvision cudatoolkit
```
The data folder would store the dataset for the MNIST and CIFAR-10 datasets, and the error_all stores the error probability values calculated for each layer of both networks using the notebook "Error_prob_calculation."

The fully connected (MLP) and Convolutional neural network (ConvNet) implementations are on two separate notebooks.
