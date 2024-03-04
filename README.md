# Machine Learning Exercises

This repository contains the Python programming exercises accompanying the theory from my [machine learning book](https://franziskahorn.de/mlbook/). They are part of the curriculum of the [ML for Data Scientists](https://franziskahorn.de/mlws_scientist.html) and [ML in Practice](https://franziskahorn.de/mlws_practice.html) Workshops.

If you have any questions, please send me an [email](mailto:hey@franziskahorn.de).

Have fun!

### Using Python

The programming exercises are written in Python. If you're unfamiliar with Python, you should work through [this tutorial](https://github.com/cod3licious/python_tutorial) first.

#### Working on your own computer
The [Python tutorial](https://github.com/cod3licious/python_tutorial) includes some notes on how to install Python and Jupyter Notebook on your own computer. <br>
Please make sure you're using Python 3 and all libraries listed in the [`requirements.txt`](/requirements.txt) file are installed and up to date. You can verify this with the [`test_installation.ipynb`](/test_installation.ipynb) notebook. <br>
The dependencies listed in `requirements.txt` are sufficient to execute most notebooks. To run notebook 6 you additionally need to install `torch`, `torchvision`, and `skorch` (or `tensorflow`, depending on the version of the notebook you want to execute).

#### Working in the cloud

If you are unable to install Python on your own computer, you can also run the notebooks in a cloud environment.


##### Using MyBinder

The easiest way to run the notebooks is using MyBinder:
[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cod3licious/ml_exercises/main) <br>
However, please note that MyBinder may take a while to load and some notebooks might be slow or even crash due to insufficient RAM. Furthermore, by default this environment does not include the necessary libraries to run notebook 6, since installing the neural network dependencies takes very long.


##### Using Google Colab

If you have a Google account, you can also run the notebooks in Google Colab, which is faster than MyBinder:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cod3licious/ml_exercises) <br>
While Google Colab already includes most packages that we need, should you require an additional library (e.g., `skorch` for training PyTorch neural networks in notebook 6), you can install a package by executing `!pip install package` in a notebook cell. With Colab, it is also possible to run code on a GPU, but this has to be manually selected. Please note that for some notebooks you need to additionally upload the required data files separately.
