# Getting-Admission-in-College-Prediction


## 📊 Dataset Overview

- **File:** `admission_predict.csv`
- **Source:** Kaggle/UCI Machine Learning Repository
- **Rows:** ~400
- **Columns:**
  - GRE Score
  - TOEFL Score
  - University Rating
  - SOP (Statement of Purpose)
  - LOR (Letter of Recommendation)
  - CGPA
  - Research (0 = No, 1 = Yes)
  - Chance of Admit (target variable)

---

## 🚀 Objective

To build a machine learning model that accurately predicts the probability (`Chance of Admit`) of a student being admitted to a university.

---

## 🧪 Technologies Used

- Python 🐍
- Pandas 🧮
- NumPy
- Matplotlib & Seaborn 📊 (for visualization)
- Scikit-learn 🤖 (for ML algorithms)

---

## 🔍 Steps Performed

1. **Data Cleaning & Exploration**
   - Checked for missing/null values
   - Visualized distributions and correlations

2. **Feature Selection & Engineering**
   - Selected numerical features
   - Normalized data if required

3. **Model Building**
   I used several regression models and optimized them using **GridSearchCV**:

   - ✅ **Linear Regression**
   - ✅ **Lasso Regression**
   - ✅ **Support Vector Regressor (SVR)**
   - ✅ **Decision Tree Regressor**
   - ✅ **Random Forest Regressor**
   - ✅ **K-Nearest Neighbors Regressor (KNN)**
   - Evaluated with metrics: MAE, RMSE, R² Score

5. **Prediction**
   - Used the trained model to predict chances of admission for new inputs

---

## 📈 Results

- The model shows a high correlation between CGPA, GRE, and chance of admission.
- Best performing model: `Linear Regression` (R² ≈ 0.80+)

---

## 📌 Future Improvements

- Add more student data for better generalization
- Include qualitative features like SOP quality, recommendation letters, etc.
- Deploy model as a web app using Flask or Streamlit
