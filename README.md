Random Forest Classification – Model Interpretation Lab

This project demonstrates how a Random Forest classifier works, how it reduces overfitting compared to a single decision tree, and how to interpret feature importance for explainable machine learning, a critical requirement in finance, fraud detection, and regulated industries.


 
 
 1. Model Overview

Random Forest is an ensemble learning method that trains many decision trees using:

Bagging (bootstrap sampling): each tree sees a slightly different subset of the data.

Random feature selection: each split considers only a subset of features.

Majority voting: the final prediction comes from the aggregated decisions of all trees.

This makes the model:

more stable

less prone to overfitting

highly accurate

interpretable




 2. Dataset

Breast Cancer Wisconsin dataset loaded from scikit-learn.
Binary classification: malignant vs benign tumors.


 
 
 3. Results

Training Accuracy: 100%
Test Accuracy: 96.49%

This shows strong generalisation without severe overfitting.


 
 
 4. Feature Importance

Random Forest identifies the most predictive features:

worst concave points

worst area

mean concave points

worst perimeter

worst radius

These correspond to known medical characteristics of malignant tumors, confirming that the model is not only accurate but meaningful.


 
 
 5. Visuals
* Feature Importance Bar Chart

(image here)

* Probability Outputs

The model provides class probabilities, useful for fraud detection threshold tuning.

 
 
 6. Technologies

Python

NumPy

Pandas

scikit-learn

Matplotlib


 
 7. Key Takeaways

✔ Random Forest is robust and stable

✔ Bagging greatly reduces overfitting

✔ Feature importance provides explainability

✔ Highly relevant for finance and fraud models


*Visual Outputs

The following model evaluation visuals are included in the images/ directory:

-Feature Importance Chart – Top predictors identified by the Random Forest model

-Confusion Matrix – Classification performance on test data

-ROC Curve & AUC Score – Probability-based performance evaluation

These visualizations are essential for interpretability and are widely used in financial risk modelling, fraud detection, and regulated ML environments.


Author: Emine Ceran
