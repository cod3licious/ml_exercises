# Machine Learning Exercises

This repository contains the exercises accompanying the theory from my [machine learning book](https://franziskahorn.de/mlbook/).

You might also want to have a look at the [cheat sheet](/cheatsheet.pdf), which includes a summary of the most important steps when developing a machine learning solution, incl. code snippets.

The programming exercises are written in Python. If you're unfamiliar with Python, please have a look at [this tutorial](https://github.com/cod3licious/python_tutorial) before working on the exercises, which also includes some notes on how to install Python and Jupyter Notebook on your own computer (please make sure you're using Python 3 and all libraries listed in the [`requirements.txt`](/requirements.txt) file are installed and up to date; you can verify this with the [`test_installation.ipynb`](/test_installation.ipynb) notebook). <br>
If you have a Google account, you can also run the code in the cloud using **Google Colab**:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cod3licious/ml_exercises) <br>
While Google Colab already includes most packages that we need, should you require an additional library (e.g., `skorch` for training PyTorch neural networks in notebook 5), you can install it by executing `!pip install package` in a notebook cell. With Colab, it is also possible to run code on a GPU, but this has to be manually selected.

If you have any questions, please send me an [email](mailto:hey@franziskahorn.de).

Have fun!


## Course Overview

For an optimal learning experience, the chapters from the [machine learning book](https://franziskahorn.de/mlbook/) should be interleaved with quizzes and programming exercises as shown below.
(You can also find the course syllabus on the last page of the [course description](/course_description.pdf), which explicitly lists all the sections of the book for each block.)

---

### Part 1: Getting started: What is ML?

##### Block 1.1:
- [ ] Read the whole chapter: ["Introduction: Solving Problems with ML"](https://franziskahorn.de/mlbook/_introduction_solving_problems_with_ml.html)
- [ ] Answer [Quiz 1](https://forms.gle/uzdzytpsYf9sFG946)

##### Block 1.2:
- [ ] Read the whole chapter: ["ML with Python"](https://franziskahorn.de/mlbook/_ml_with_python.html)
- [ ] Install Python on your computer and complete the [Python tutorial](https://github.com/cod3licious/python_tutorial) (if you haven't done this already)

##### Block 1.3:
- [ ] Read the whole chapter: ["Data & Preprocessing"](https://franziskahorn.de/mlbook/_data_preprocessing.html)
- [ ] Answer [Quiz 2](https://forms.gle/Pqr6EKHNxzrWb7MF9)
- [ ] Read the introductory part of the chapter ["ML Algorithms: Unsupervised & Supervised Learning"](https://franziskahorn.de/mlbook/_ml_algorithms_unsupervised_supervised_learning.html)

---

### Part 2: Your first algorithms

##### Block 2.1:
- [ ] Read the section: ["UL: Dimensionality Reduction"](https://franziskahorn.de/mlbook/_ul_dimensionality_reduction.html)
- [ ] Work through [Notebook 1: visualize text](/exercises/1_visualize_text.ipynb)

##### Block 2.2:
- [ ] Read the section: ["UL: Outlier / Anomaly Detection"](https://franziskahorn.de/mlbook/_ul_outlier_anomaly_detection.html)
- [ ] Read the section: ["UL: Clustering"](https://franziskahorn.de/mlbook/_ul_clustering.html)
- [ ] Work through [Notebook 2: image quantization](/exercises/2_image_quantization.ipynb)

##### Block 2.3:
- [ ] Read the section: ["Supervised Learning: Overview"](https://franziskahorn.de/mlbook/_supervised_learning_overview.html)
- [ ] Answer [Quiz 3](https://forms.gle/M2dDevwzicjcHLtc9)

---

### Part 3: Advanced models

##### Block 3.1:
- [ ] Read the sections: ["SL: Linear Models"](https://franziskahorn.de/mlbook/_sl_linear_models.html) up to and including ["SL: Kernel Methods"](https://franziskahorn.de/mlbook/_sl_kernel_methods.html)
- [ ] **In parallel**, work through the respective sections of [Notebook 3: supervised comparison](/exercises/3_supervised_comparison.ipynb)

##### Block 3.2:
- [ ] Read the section: ["Information Retrieval (Similarity Search)"](https://franziskahorn.de/mlbook/_information_retrieval_similarity_search.html) and review the sections on [TF-IDF feature vectors](https://franziskahorn.de/mlbook/_feature_extraction.html) and [cosine similarity](https://franziskahorn.de/mlbook/_computing_similarities.html)
- [ ] Work through [Notebook 4: information retrieval](/exercises/4_information_retrieval.ipynb)

##### Block 3.3:
- [ ] Read the section: ["SL: Neural Networks"](https://franziskahorn.de/mlbook/_sl_neural_networks.html)
- [ ] Work through [Notebook 5: MNIST with torch](/exercises/5_mnist_torch.ipynb) (recommended) **_or_** [MNIST with keras](/exercises/5_mnist_keras.ipynb) (in case others in your organization are already working with TensorFlow)
- [ ] Read the sections: ["Time Series Forecasting"](https://franziskahorn.de/mlbook/_time_series_forecasting.html) and ["Recommender Systems (Pairwise Data)"](https://franziskahorn.de/mlbook/_recommender_systems_pairwise_data.html)

---

### Part 4: Avoiding common pitfalls

##### Block 4.1:
- [ ] Read the whole chapter: ["Avoiding Common Pitfalls"](https://franziskahorn.de/mlbook/_avoiding_common_pitfalls.html)

##### Block 4.2:
- [ ] Answer [Quiz 4](https://forms.gle/uZGj54YQHKwckmL46)
- [ ] Work through [Notebook 6: analyze toy dataset](/exercises/6_analyze_toydata.ipynb)

##### Block 4.3:
- [ ] _Case Study!_ [Notebook 7: predicting hard drive failures](/exercises/7_hard_drive_failures.ipynb) (plan at least 5 hours for this!)

---

### Part 5: RL & Conclusion

##### Block 5.1:
- [ ] Read the whole chapter: ["ML Algorithms: Reinforcement Learning"](https://franziskahorn.de/mlbook/_ml_algorithms_reinforcement_learning.html)
- [ ] Work through [Notebook 8: RL gridmove](/exercises/8_rl_gridmove.ipynb)

##### Block 5.2:
- [ ] Answer [Quiz 5](https://forms.gle/fr7PYmP9Exx4Vvrc8)
- [ ] Read the whole chapter: ["Conclusion: Using ML in Practice"](https://franziskahorn.de/mlbook/_conclusion_using_ml_in_practice.html)
- [ ] Complete the exercise: ["Your next ML Project"](/exercise_your_ml_project.pdf)

---
