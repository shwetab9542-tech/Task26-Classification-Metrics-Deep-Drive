Task26- Classification Metrics Deep Dive

## Project Overview

This project evaluates a classification model using different
classification metrics.

## Objective

The objective is to understand and compare:

- Accuracy
- Precision
- Recall
- F1-Score
- Support

The project also analyzes false positives and false negatives and
explains when each metric is useful.

## Dataset

Breast Cancer Wisconsin Dataset.

The dataset is available through Scikit-learn.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Model Used

Logistic Regression

## Metrics

### Accuracy
Measures the overall percentage of correct predictions.

### Precision
Measures the correctness of positive predictions.

### Recall
Measures how many actual positive cases are correctly identified.

### F1-Score
Provides a balance between precision and recall.

### Support
Shows the number of actual samples in each class.

## Conclusion

The project demonstrates that different classification metrics provide
different perspectives on model performance.

Accuracy alone should not always be used. Precision, recall and F1-score
should also be considered based on the practical cost of classification
errors.

For this medical classification example, recall is an important metric
to monitor because missing an actual positive case can have significant
consequences.