# signal-classification-ml
# Signal Classification Using Machine Learning

## Overview
This project explores the classification of synthetic signals into three classes using machine learning. It investigates how feature engineering affects classification accuracy under different noise conditions.

## Objectives
- Generate synthetic signals belonging to three classes.
- Extract time-domain and frequency-domain features.
- Compare Logistic Regression and Random Forest classifiers.
- Evaluate model performance across different signal-to-noise ratios (SNRs).
- Investigate whether engineered features improve robustness to noise.

## Methodology
The workflow includes synthetic signal generation, feature extraction, data splitting, feature scaling where appropriate, model training, and evaluation on noisy test signals.

Two feature-engineering approaches (V1 and V2) are compared with the original feature set.

## Models Evaluated
- Logistic Regression — Original Features
- Random Forest — Original Features
- Logistic Regression — Feature Engineering V1
- Logistic Regression — Feature Engineering V2
- Random Forest — Feature Engineering V2

## Key Results
Random Forest with Feature Engineering V2 achieved 99.76% classification accuracy at 0 dB SNR in the evaluated test setting. A repeated evaluation using five random seeds produced a mean accuracy of 99.95%.

## Limitations
The signals used in this project are synthetic and have predefined frequency characteristics. Therefore, the results do not guarantee equivalent performance on real-world signals.

## Tools
Python, NumPy, Pandas, Matplotlib, scikit-learn, Google Colab, Jupyter Notebook
