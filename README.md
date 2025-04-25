# Iris-Flower-Species-Classification
This project is a machine learning solution to classify Iris flowers into three species — Setosa, Versicolor, and Virginica — using petal and sepal measurements using the provided `IRIS.csv` dataset. It leverages supervised learning algorithms such as Logistic Regression, Decision Trees, Random Forest, SVM, and KNN to achieve high accuracy in species prediction.

---

## 📌 Project Overview

This project uses a CSV-based Iris dataset to train and evaluate classification models. The goal is to build an accurate and interpretable machine learning model that identifies flower species and highlights the most impactful features.

---

## Dataset Description

The dataset contains **150 samples** of iris flowers with the following features:

| Feature        | Description            |
|----------------|------------------------|
| sepal_length   | in cm                  |
| sepal_width    | in cm                  |
| petal_length   | in cm                  |
| petal_width    | in cm                  |
| species        | Setosa, Versicolor, Virginica (categorical target) |

Dataset Source: `IRIS.csv` file provided for this project.

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

---

## 🧠 Models Trained

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier ✅ *(Best performing)*
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)

---

## 🧪 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Feature Importance (Random Forest)

---

## 🌟 Results Summary

| Model               | Accuracy (example) |
|---------------------|--------------------|
| Logistic Regression | 96.67%             |
| Decision Tree       | 96.67%             |
| Random Forest       | 100.00%            |
| SVM                 | 96.67%             |
| KNN                 | 100.00%            |


🔍 **Most important features**:
- `petal_length`
- `petal_width`

🎯 **Final Outcome**

"Developed a high-accuracy Iris flower classification model using scikit-learn. Implemented and evaluated multiple machine learning algorithms on structured data. Achieved 100% accuracy using Random Forest. Identified key predictive features and built an organized, reproducible ML pipeline in Jupyter Notebook."
