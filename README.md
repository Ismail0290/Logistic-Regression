# Logistic Regression – Breast Cancer Classification

**📌 Objective**

Build a binary classifier using Logistic Regression to predict whether a breast tumor is malignant (1) or benign (0) using the Breast Cancer Wisconsin dataset.

**📊 Dataset**

Features: 30 numeric measurements of tumor cell nuclei

Target: diagnosis → M = 1 (malignant), B = 0 (benign)

Records: 569 samples

Dropped: id, Unnamed: 32 (irrelevant/empty)

**🛠 Tools Used**

Python, Pandas, NumPy, Matplotlib, Scikit-learn

**🚀 Steps**

Load & clean dataset

Encode target (M → 1, B → 0)

Train-test split (80/20)

Standardize features

Train Logistic Regression model

Evaluate using confusion matrix, classification report, accuracy, ROC-AUC

Plot ROC curve & tune threshold

Demonstrate sigmoid function

**📈 Results**

Accuracy: ~95–98%

ROC-AUC: ~0.99

High precision & recall for both classes

**📌 Key Concepts**

Logistic Regression maps features to probabilities using the sigmoid function.

ROC Curve & AUC measure classification performance.

Threshold tuning changes the precision/recall trade-off.

