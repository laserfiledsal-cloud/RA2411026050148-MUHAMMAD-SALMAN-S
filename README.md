# RA2411026050148-MUHAMMAD-SALMAN-S
Text Classification Battle :  A comparative study of Decision Tree, KNN, SVM, and Naive Bayes using TF-IDF on the 20 Newsgroups dataset, evaluating accuracy, precision, recall, F1-score, and computational performance to identify the best classifier.

# Text Classification Battle

## Overview

A comparative study of four machine learning algorithms for multiclass text classification using Python and TF-IDF. The project evaluates Decision Tree, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Naive Bayes to identify the best-performing classifier.

## Dataset

- **Source:** 20 Newsgroups dataset from Scikit-learn.
- **Classes:** 20 different newsgroup topics.
- **Preprocessing:** Removal of headers, footers, and quoted text, followed by TF-IDF feature extraction.
- **Feature Extraction:** Term Frequency–Inverse Document Frequency (TF-IDF).

## Algorithms

- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (LinearSVC)
- Multinomial Naive Bayes

## Methodology

1. Load and preprocess the 20 Newsgroups dataset.
2. Convert text documents into numerical feature vectors using TF-IDF.
3. Split the dataset into training and testing sets.
4. Train all four machine learning classifiers.
5. Evaluate and compare their performance.
6. Experiment with different K values for the KNN classifier.

## Evaluation Metrics

- Accuracy
- Weighted Precision
- Weighted Recall
- Weighted F1-score
- Macro F1-score
- Training Time
- Testing Time

## Results and Analysis

The four classifiers are compared using evaluation metrics, classification reports, confusion matrices, and execution times. The best-performing model is identified based on its weighted F1-score.

A separate KNN experiment compares K values of 3, 5, and 7 to investigate their effect on classification performance.

## Technologies Used

- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- Matplotlib


## Conclusion

This project demonstrates how different machine learning algorithms perform on multiclass text classification using TF-IDF features. The experimental results help identify the most effective classifier by considering predictive performance and computational efficiency.
