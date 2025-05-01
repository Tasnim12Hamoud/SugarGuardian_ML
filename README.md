# 🧠 SugarGuardian_ML

A machine learning project to predict diabetes using various classification algorithms.  
Built using Python, scikit-learn, and real medical data from the Pima Indians Diabetes dataset.

---

## 📌 Project Goal

To develop a reliable machine learning model that can classify whether a person is likely to have diabetes based on several health features.

---

## 📊 Dataset

- Source: Pima Indians Diabetes Dataset
- Features:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib / Seaborn
- Google Colab

---

## 🧪 Models Trained

- Logistic Regression ✅ (Best Performance)
- Support Vector Machine (SVM)
- Random Forest Classifier

---

## 🛠️ Preprocessing & Techniques

- Handled missing and invalid data
- Feature scaling with MinMaxScaler
- Train/test split (80/20)
- Balanced data using **SMOTE**
- Hyperparameter tuning with **GridSearchCV**

---

## ✅ Best Results

| Model                    | Accuracy | Recall (Positive) | Notes                       |
|-------------------------|----------|-------------------|-----------------------------|
| Logistic Regression     | **75.97%** | 62%              | With GridSearchCV          |
| SVM                     | 75.32%   | 56%              | Good baseline performance  |
| Random Forest           | 74.03%   | 65%              | Slightly lower precision   |
| Logistic + SMOTE        | 71.43%   | **73%**          | Higher recall, lower precision |

---

## 📌 Final Notes

The **Logistic Regression model with GridSearchCV** gave the best overall performance and was selected as the final model.

---

## 🚀 Author

**Tasnim Al-Hamoud**  
ML & AI Enthusiast  
[LinkedIn Profile](https://www.linkedin.com/in/tasnim-hamoud-3b76a4344?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
