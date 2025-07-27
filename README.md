# pulsar-detection-ml
Pulsar Detection using Machine Learning

This project implements a binary classification model to detect pulsars from radio signal data using logistic regression, built entirely from scratch with NumPy. 
It includes data preprocessing, model training with gradient descent, and evaluation using metrics such as precision, recall, F1 score, and ROC AUC — particularly important for handling imbalanced data.

## Features
- Logistic regression implemented from first principles
- Evaluation with precision, recall, F1 score, ROC AUC, and confusion matrix
- Custom train-test split with stratification for class balance

## Requirements
- Python 3.8+
- NumPy
- scikit-learn (for evaluation metrics)

## Citation

The dataset was taken from the following:

**Paper citation:**
R. J. Lyon, B. W. Stappers, S. Cooper, J. M. Brooke, J. D. Knowles,  
*Fifty Years of Pulsar Candidate Selection: From simple filters to a new principled real-time classification approach*,  
*Monthly Notices of the Royal Astronomical Society*, **459**(1), 1104–1123.  
[DOI: 10.1093/mnras/stw656](https://doi.org/10.1093/mnras/stw656)

**Dataset citation:**
R. J. Lyon, **HTRU2 Dataset**,  
[DOI: 10.6084/m9.figshare.3080389.v1](https://doi.org/10.6084/m9.figshare.3080389.v1)

