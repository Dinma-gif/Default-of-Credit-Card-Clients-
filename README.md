# Customer Default Payment Prediction

## Overview
This research focuses on analyzing customer default payments in Taiwan and evaluates the predictive accuracy of the probability of default using six different data mining methods. The study aims to determine which method can most accurately estimate the probability of default, a critical factor in risk management.

## Motivation
In risk management, the **probability of default** (PD) is far more valuable than the binary classification of clients as either "credible" or "not credible." Traditional binary classification may offer basic insights, but it does not capture the nuanced likelihood of default, which can be used to make more informed decisions.

Since the real probability of default is unknown, this study introduces a novel method for estimating it: the **Sorting Smoothing Method**. This method allows the estimation of a real probability of default based on predictive probabilities generated from data mining models.

## Methodology

### Predictive Models
The following six data mining techniques were used to predict the probability of default:

1. **Artificial Neural Networks (ANN)**
2. **Decision Trees**
3. **Support Vector Machines (SVM)**
4. **Logistic Regression**
5. **K-Nearest Neighbors (KNN)**
6. **Random Forest**

### Sorting Smoothing Method
To estimate the **real probability of default**, the study proposes the **Sorting Smoothing Method**, which compares the predicted probability (X) against the actual default (Y).


