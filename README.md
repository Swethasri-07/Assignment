# Beyond Accuracy: Probability Calibration in Machine Learning

##  Overview

This project demonstrates how probability calibration improves the reliability of machine learning model predictions. While many models achieve high accuracy, their predicted probabilities are often poorly calibrated. This tutorial explores how calibration techniques can correct this issue.

---

##  Objectives

* Evaluate probability estimates from machine learning models
* Identify overconfidence and underconfidence in predictions
* Apply calibration techniques to improve reliability
* Compare model performance before and after calibration

---

##  Models Used

* Random Forest Classifier
* Logistic Regression

---

##  Techniques

* Probability Calibration
* Platt Scaling (Sigmoid Calibration)
* Isotonic Regression

---

##  Dataset

* Breast Cancer Dataset (from scikit-learn)

---

##  Results

The study shows that:

* Random Forest produces overconfident predictions
* Calibration significantly improves probability reliability
* Brier score decreases after calibration
* Reliability diagrams align closer to ideal predictions

---

##  Visualisations

The following plots are generated:

* Calibration Curve (Before Calibration)
* Calibration Curve (After Calibration)
* Probability Distribution Plot
* Reliability Diagram
* Prediction Error Comparison

