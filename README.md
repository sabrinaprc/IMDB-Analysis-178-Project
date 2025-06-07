# IMDB Sentiment Classification Project (CS178 Final)

This project was completed for the final assignment in **CS178: Machine Learning and Data Mining** at UC Irvine. The goal was to apply and compare machine learning classification algorithms on the **IMDB movie review dataset** to predict sentiment (positive or negative).

## 📊 Dataset

We used the **IMDB Large Movie Review Dataset**, which contains:
- 25,000 labeled training reviews
- 25,000 labeled test reviews  
Each review is labeled as **positive** or **negative** sentiment.

## 🔍 Objectives

- Explore and preprocess a real-world text classification dataset
- Implement and compare classification algorithms
- Evaluate performance using accuracy, precision, recall, and F1-score
- Generate **learning curves** and conduct **hyperparameter tuning**
- Investigate the effect of regularization and hyperparameters like `k` in kNN

## 🧪 Methods

We applied and evaluated the following classifiers:
- **k-Nearest Neighbors (kNN)**
- **Logistic Regression**
- **Feedforward Neural Network**
- **Support Vector Machine (SVM)**

Text data was preprocessed using:
- Lowercasing
- Stopword removal
- TF-IDF vectorization (`max_features=10,000`)

## 📈 Evaluation

Metrics used:
- Accuracy
- Precision / Recall
- F1-score

We split the data into:
- 60% Training
- 20% Validation (used for hyperparameter tuning)
- 20% Test (used once for final evaluation)

We also analyzed:
- Learning curves for each classifier
- The effect of `k` in kNN
- The effect of `C` (regularization strength) in Logistic Regression

