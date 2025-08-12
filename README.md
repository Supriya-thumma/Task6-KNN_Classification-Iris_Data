# 🤝 Task 6 - K-Nearest Neighbors (KNN) Classification

This project is part of my AI & ML Internship Task 6 by Elevate Labs. It implements the **K-Nearest Neighbors (KNN)** algorithm to classify flowers from the famous **Iris dataset** 🌸.  
We explore different values of **K**, evaluate model accuracy, visualize decision boundaries, and understand why **normalization** is crucial for KNN.

---

## 📌 Project Overview
- **Dataset**: Iris Dataset (`Iris.csv`)
- **Objective**: Understand instance-based learning & implement KNN for classification
- **Tools Used**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Key Learnings**:
  - How KNN works & the role of distance metrics
  - Importance of feature scaling
  - Selecting the optimal K value
  - Visualizing decision boundaries

---

## 📊 Results
| K Value Range | Accuracy |
|---------------|----------|
| 1 to 10       | 100%     |

- **Best K**: 1 (but all K values performed equally due to dataset separability)
- **Final Accuracy**: 100%
- **Confusion Matrix**: Perfect classification — no misclassifications 🚀
- **Observation**: The Iris dataset is perfectly separable in the feature space after scaling.

---

## 📦 Requirements
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

