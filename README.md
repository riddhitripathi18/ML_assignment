# Breast Cancer Diagnosis Classification

- **What the dataset is about**: Sourced from Kaggle (Breast Cancer Wisconsin Diagnostic dataset), it contains 569 patient records with 30 cell nucleus features computed from digitized fine needle aspirate (FNA) images.
- **What you are predicting**: Predicting whether a breast tumor is **Malignant** (cancerous, encoded as 1) or **Benign** (non-cancerous, encoded as 0).
- **Which model(s) you used**: Trained and evaluated two classification models: **Logistic Regression** (with standard scaling) and a **Random Forest Classifier** (100 estimators).
- **Your result**: Random Forest achieved **97.37% test accuracy** (100.00% precision, 92.86% recall, 96.30% F1-score) with zero false positives, while Logistic Regression achieved **96.49% test accuracy** (97.50% precision, 92.86% recall, 95.12% F1-score).
- **One thing you learned**: In clinical cancer diagnosis, recall is more critical than accuracy because false negatives (missing cancer) are life-threatening, and feature scaling is essential for gradient-based models like Logistic Regression to prevent large-magnitude features from dominating.
