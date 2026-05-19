# OTML Practical 8: Probabilistic Modelling and Inference

## 1. Aim

The aim of this practical is to understand probabilistic modelling and inference using a Gaussian Naive Bayes classifier.

In this practical, students use a simple Music Genre Recommendation System to learn how probability-based machine learning models make predictions under uncertainty and how class probabilities are used for inference.

---

## 2. Course and Module Mapping

**Course:** A8751 – Optimization Techniques in Machine Learning  
**Module:** Module 1 – Model Fitting and Error Measurement  
**Practical Topic:** Probabilistic Modelling and Inference using Gaussian Naive Bayes

This practical is mapped with Module 1 of OTML, where students study model fitting, error measurement, probabilistic modelling, inference, and the role of optimization in machine learning.

---

## 3. Theory Background

Probabilistic modelling is a machine learning approach in which predictions are made using probability values.

In deterministic models, the model may directly predict one output class. In probabilistic models, the model estimates the probability of different possible classes and then selects the most likely class.

For example, a probabilistic model may estimate:

```text
P(HipHop | age, gender)
P(Jazz | age, gender)
P(Classical | age, gender)
