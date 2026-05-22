# Data Poisoning Attacks on ML Models in e-Health

Study based on the paper:
> *Prevention of Data Poisonous Threats on Machine Learning Models in e-Health*
> Alruwaili & Moulahi — ACM Transactions on Computing for Healthcare, 2025

---

## What is this about?

Machine learning models used in healthcare are vulnerable to a silent attack called **data poisoning** — where an attacker manipulates training data before the model learns, causing it to make systematically wrong predictions.

This notebook simulates **Label-Flipping attacks** at different rates (5%, 25%, 50%, 75%) on real medical datasets and evaluates how well ML models resist and detect the poisoning.

---

## Datasets

- **Breast Cancer Wisconsin** — 569 samples, 32 features
- **Pima Indians Diabetes** — 768 samples, 9 features

## Models tested

`Logistic Regression` `SVM` `Random Forest` `Gradient Boosting` `MLP`

---

## Original paper

DOI: https://doi.org/10.1145/3728369
