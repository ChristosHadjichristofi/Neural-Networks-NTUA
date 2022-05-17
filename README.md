# Neural-Networks-NTUA

## Exercise 1- Supervised Learning

This exercise consists of two parts. The former part uses a [Dermatology dataset](http://archive.ics.uci.edu/ml/datasets/Dermatology) from the UCI datasets which has symptoms as attributes and types of Eryhemato-Squamous Diseases as labels. The purpose of this part is to compare multiple Classifiers (dummy, Gaussian Naive Bayes (GNB), K-Neirest Neighbors (KNN) and Logistic Regression (LR)) using metrics such as Accuracy and F1. To manually optimize the classifiers we preprocessed the data, experimented with various hyper-parameter values and added pipelines.

The latter part uses an [Online Poker Games dataset](https://www.kaggle.com/datasets/murilogmamaral/online-poker-games) from [Kaggle](https://www.kaggle.com/) which has details for a hand of poker from the point of view of a single player as attributes and the hand’s outcome as label. The purpose of this part is to optimize Multi-layer Perceptron (MLP) and Support vector machines (SVM) using the F1 metric. To optimize the classifiers we preprocessed the data and used [Optuna](https://optuna.org/), an automated hyper-parameter optimization tool
