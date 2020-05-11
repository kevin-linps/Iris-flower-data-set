# Iris Flower Data Set

Author: Kevin Ping-Sheng Lin

Date: May 10, 2020

## About this project

In this project, I explored the famous Iris Flower Data Set with classifiers in scikit-learn. First, I started by creating visuals of the data. Then, I trained models using Linear SVM and Decision Tree to classify the three flower species. The desciptions of the files in the respiratory  are as follows:

1. *Iris Flower Data Set 01 - Visualization*: building 2D and 3D scatter plots to visualize the relationships between each varaible
2. *Iris Flower Data Set 02 - Linear SVM*: training classifiers using LinearSVC in scikit-learn and evaluate their precision
3. *Iris Flower Data Set 03 - Decision Tree*: training classifiers using DecisionTreeClassifier in scikit-learn, evaluate their precision and produce a dichotomous key for the three iris species in the data set


## Experiment Results

The summary of the training and testing results are shown below in Table 1. Although both models have the same performance, Decision Tree can produce dichotomous key as an additional product. This is particularly good in this case since it offers humans a way of classifying different species of iris flowers without machines.

Table 1. Accuracy of models built in this project
|               | Linear SVM    | Decision Tree |
| ------------- | ------------- | ------------- |
| Training set  | 97%           | 97%           |
| Testing set   | 100%          | 100%          |

## Technologies used

* Operating System: Windows 10
* Programs: Anaconda, Jupyter Notebook
* Software: Python 3, scikit-learn, numpy, matplotlib

## Acknowledgement

Some parts of the codes written in this project are copied and/or modified from the official scikit-learn tutorial.
