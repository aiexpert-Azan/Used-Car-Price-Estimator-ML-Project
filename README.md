# Used Car Price Prediction (Classical ML Project)

A comprehensive Machine Learning Lab project focused on predicting used car prices in Pakistan. This project emphasizes **Classical Machine Learning** techniques and **Feature Engineering** over deep learning to ensure model interpretability and efficiency on structured tabular data.

---

## 🎯 Project Objective
The goal was to build a robust predictive system that handles real-world, messy data from the PakWheels platform. This project follows a standard Data Science pipeline without a graphical UI, focusing instead on the technical accuracy and performance of regression algorithms.

## 🛠️ Technical Methodology: Why Classical ML?
For this project, we intentionally chose **Classical Machine Learning** (Tree-based models) over Deep Learning because:
- **Tabular Data Excellence:** Random Forest and XGBoost are state-of-the-art for structured data of this scale.
- **Interpretability:** We can analyze **Feature Importance** to see exactly which factors (Engine CC, Age, etc.) drive price changes.
- **Efficiency:** These models provide high accuracy (~91%) without the need for heavy GPU resources or complex neural network architectures.

---

## 🚀 Key Pipeline Stages

### 1. Data Cleaning & Preprocessing
- Removed currency symbols (PKR) and commas to convert prices into numerical format.
- Handled outliers by filtering realistic price ranges (1 Lac to 6 Crore).
- Managed missing values in categorical features.

### 2. Advanced Feature Engineering
- **Car Age:** Derived from the manufacturing year to capture depreciation logic.
- **Binary Features:** Used text extraction to create features for **ABS**, **Airbags**, and **Navigation Systems** from car descriptions.

### 3. Model Implementation & Tuning
We compared three major algorithms to find the best fit:
- **Linear Regression:** Served as the baseline model (R2: ~55%).
- **Random Forest:** Improved accuracy significantly through ensemble learning.
- **XGBoost:** Fine-tuned to achieve the most stable results (R2: ~91%).

---

## 📈 Final Results Summary
| Model | R2 Score (Accuracy) | Status |
| :--- | :--- | :--- |
| Linear Regression | 0.5528 | Baseline |
| **Random Forest (Tuned)** | **0.9015** | Optimized |
| **XGBoost (Tuned)** | **0.9062** | Best Performer |

---


## 🎓 Acknowledgments
Submitted as a Lab Project to **Mr. Abu Huraira** at the **University of Management and Technology (UMT)**.
