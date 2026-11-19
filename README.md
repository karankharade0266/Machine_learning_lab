# Machine Learning Practical Work

## About

This repository contains practical implementations of important Machine Learning algorithms using Python. The experiments were carried out in Jupyter Notebook with the help of the Scikit-learn library.

The main purpose of this repository is to explore different machine learning techniques, understand their working principles, and implement them on datasets.

## Algorithms Covered

The following algorithms are included in this practical work:

| Sr. No. | Algorithm | Category |
|---|---|---|
| 1 | Linear Regression | Supervised Learning – Regression |
| 2 | Decision Tree | Supervised Learning – Classification |
| 3 | K-Nearest Neighbors (KNN) | Supervised Learning – Classification |
| 4 | K-Means | Unsupervised Learning – Clustering |
| 5 | Random Forest | Supervised Learning – Classification |
| 6 | Support Vector Machine (SVM) | Supervised Learning – Classification |
| 7 | Naive Bayes | Supervised Learning – Classification |
| 8 | Perceptron | Supervised Learning – Classification |

## Repository Contents

```text
Machine-Learning-Practicals/
│
├── README.md
│
├── Linear_Regression.ipynb
├── Decision_Tree.ipynb
├── KNN.ipynb
├── K_Means.ipynb
├── Random_Forest.ipynb
├── SVM.ipynb
├── Naive_Bayes.ipynb
├── Perceptron.ipynb
│
└── diabetes_prediction_dataset.csv
```

*The filenames can be modified according to the actual notebook names.*

## Dataset Description

### Diabetes Prediction Dataset

A dataset containing 27,528 observations and 9 attributes is used for implementing classification and clustering algorithms.

The dataset includes the following attributes:

- Gender
- Age
- Hypertension
- Heart Disease
- Smoking History
- BMI
- HbA1c Level
- Blood Glucose Level
- Diabetes

The diabetes column represents the target variable for classification experiments. It is excluded during K-Means clustering.

### Salary Dataset

The Salary dataset is used for the Linear Regression experiment to analyze the relationship between experience and salary.

## Software and Libraries

The following tools and libraries are used:

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

Install the necessary dependencies using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Running the Experiments

1. Download or clone the repository.
2. Install the required Python libraries.
3. Open the project directory in Jupyter Notebook or JupyterLab.
4. Select the experiment you want to execute.
5. Run the cells sequentially.
6. Examine the generated outputs and visualizations.

## Performance Evaluation

For classification experiments, the models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

For the K-Means experiment, clustering performance is examined using the Elbow Method and Silhouette Score.

## Learning Outcomes

Through these practical implementations, the following concepts are explored:

- Understanding supervised and unsupervised learning.
- Performing data cleaning and preprocessing.
- Training machine learning models.
- Making predictions using trained models.
- Evaluating model performance.
- Visualizing results and interpreting outputs.

## Purpose

This repository is maintained as part of academic Machine Learning laboratory work. It demonstrates the practical application of different algorithms and provides hands-on experience with machine learning tools and techniques.

---

**Project Type:** Academic Practical Submission  
**Domain:** Machine Learning  
**Language:** Python
