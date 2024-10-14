# Decision Tree Classifier Comparison

This project compares the performance of different decision tree algorithms (CART, ID3, and C4.5) on a sample dataset (Iris dataset). The goal is to understand how these algorithms function and evaluate their accuracy and classification performance.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Algorithms Compared](#algorithms-compared)
- [Results](#results)


## Description
This project explores the implementation and comparison of three decision tree algorithms:
- CART (Classification and Regression Trees)
- ID3 (Iterative Dichotomiser 3)
- C4.5 (successor of ID3)

We use the **Iris dataset** to train and test the models and compare their performance using metrics like accuracy, precision, recall, and F1-score.

## Installation

To run this project, you need Python and the required libraries installed. Follow these steps:

1. Clone the repository:
   ```bash
   https://github.com/WALIDAADI/Decision_Tree.git
   

2.Navigate to the project directory:
    ```bash
             
      cd Decision_Tree
## Algorithms Compared
#### 1.CART (Gini Impurity):

Uses the Gini Impurity criterion to split nodes.
Provided by DecisionTreeClassifier with criterion='gini' in Scikit-learn.
#### 2.ID3 (Information Gain):

Uses information gain to choose the best attribute for splitting.
Provided by DecisionTreeClassifier with criterion='entropy'.
#### 3.C4.5 (Improvement of ID3):

An extension of ID3 that handles continuous data and incomplete datasets, and it uses the Gain Ratio to split nodes.
## Results
All three models performed similarly well on the Iris dataset with accuracies around 97%. Here's a summary of their performance:

Model	Accuracy	Precision	Recall	F1-Score
CART	0.97	0.97	0.97	0.97
ID3	0.97	0.97	0.97	0.97
C4.5	0.97	0.97	0.97	0.97

   
