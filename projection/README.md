## Introduction
In this project, we use neural networks to predict the highest height and the longest range during the projectile. We implement the neural networks with the PyTorch framework.

## Description
The input of the neural network is the initial velocity and angle. The output should be the height and the range. In a nutshell, the model should generate the samples follow the below plots.
<center>
    <img alt="surface plot" src="plot/plot.svg"/>
</center>

## Visualization
Instead of using loss to evaluate the performance, we decide to use R-H plot to provide an alternative. The ground truth R-H plot is shown below:
<center>
    <img alt="R-H plot" src="plot/line.svg"/>
</center>

## Hyperparameters
### a. Hidden features
| hidden_features |          Plot link          |
|:---------------:|:---------------------------:|
|       16        |   [plot](test.pdf)   |


### b. Batch size
| Batch size | Epochs |
|:----------:|:------:|
|    4096    | 10000  |

## TensorFlow
We also tested the model on TensorFlow with **batch size=4096, epoch=100**, and provide the colab notebook.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ojsWMdbVOC7lH_nkeT1VBTkcvLRiB9Zj#scrollTo=5Sl6zYOuAzFG)

[See the plot](plot/tf_bs_4096.pdf)
