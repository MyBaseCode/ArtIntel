# ArtIntel
## Trees
### Overview
This project implements a decision tree classifier from scratch using an entropy-based Information Gain approach.

The implementation does not use built-in decision tree functions from machine learning libraries (such as `sklearn.tree.DecisionTreeClassifier`). The algorithm is manually implemented using entropy, Information Gain, recursive tree construction, and tree traversal for classification.

The program supports nominal datasets with two possible class labels, as required for the assignment.

### How to Run
1. Open the project folder using **Jupyter Lab**.

2. Open the notebook containing the decision tree implementation.

3. Before running the program, check that all file paths are correct.

The program requires:

- The correct path to the input `.csv` dataset.
- The correct output file path for saving the generated decision tree.

Example input dataset path:

```python
data = pd.read_csv("../Data/rtg_A.csv")
```

Example output file:

```python
with open("outputtree.txt", "w") as f:
    save_tree(tree, f)
```

Make sure these paths match the actual locations of your dataset and output file.

## Algoritm Comparation
### Overview

This project compares the performance of supervised machine learning classification algorithms. The models are evaluated using the Breast Cancer dataset to classify samples into diagnosis categories.

The aim of this project is to investigate how different preprocessing techniques and model configurations affect classification performance. The experiments include feature normalization, Pearson correlation-based feature selection, Principal Component Analysis (PCA) for dimensionality reduction, and 10-fold cross-validation for evaluating model stability and reliability.

The performance of each algorithm is compared based on classification accuracy, consistency across validation folds, and the trade-off between predictive performance and model interpretability.

### How to Run
1. Open the project folder using **Jupyter Lab**.

2. Open the notebook in the AlgComp Folder.

3. Before running the program, check that all file paths are correct.

The program requires:

- The correct path to the input `.csv` dataset.
- The correct output file path for saving the generated decision tree.

Example input dataset path:

```python
data = pd.read_csv("../Data/breast-cancer.csv")
```

Example output file:

```python
median_output = "breast-cancer-median-imput.csv" 
```

Make sure these paths match the actual locations of your dataset and output file.
