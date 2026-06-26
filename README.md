# 🎓 Student Placement Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a student will be placed or not based on academic performance, technical skills, soft skills, and extracurricular activities.

The project follows a complete Machine Learning workflow, including data preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and model interpretation.

---

## 🎯 Objectives

- Predict student placement status.
- Compare multiple Machine Learning algorithms.
- Improve model performance using hyperparameter tuning.
- Interpret model predictions using feature importance and coefficients.

---

## 📂 Dataset

The dataset contains information such as:

- Age
- CGPA
- Backlogs
- Attendance
- 10th Percentage
- 12th Percentage
- Branch
- College Tier
- Programming Skills
- ML Skill
- Web Development Skill
- Communication Skill
- Aptitude Score
- Logical Reasoning
- Internships
- Projects
- GitHub Projects
- Hackathons
- Certifications
- Coding Contest Rating
- Leadership
- Teamwork
- Family Income
- Placement Status (Target)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

### 1. Data Preprocessing

- Missing value checking
- Exploratory Data Analysis (EDA)
- Correlation analysis

### 2. Feature Engineering

Created new features such as:

- Technical Skill Score
- Programming Skill Score
- Experience Score
- Soft Skill Score
- Academic Score
- Problem Solving Index

### 3. Data Preparation

- One-Hot Encoding
- Train-Test Split
- Feature Scaling using StandardScaler
- Pipeline implementation

### 4. Model Training

The following models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

### 5. Model Validation

- Cross Validation (5-Fold)

### 6. Hyperparameter Tuning

- GridSearchCV (Logistic Regression)
- RandomizedSearchCV (Random Forest)

### 7. Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- AUC Score

### 8. Model Interpretation

- Logistic Regression Coefficients
- Random Forest Feature Importance

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **67.93%** |
| KNN | 59.38% |
| Decision Tree | 57.45% |
| Random Forest | 66.33% |
| Tuned Logistic Regression | **67.93%** |
| Tuned Random Forest | 67.78% |

---

## 🏆 Best Model

**Logistic Regression**

Test Accuracy:

```
67.93%
```

---

## 📁 Project Structure

```
Student-Placement-Prediction/
│
├── data/
│   └── placement_dataset.csv
│
├── notebooks/
│   └── Student_Placement_Prediction.ipynb
│
├── models/
│   └── placement_prediction_model.pkl
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository.

```
git clone <repository-link>
```

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the notebook.

```
jupyter notebook
```

4. Run all cells.

---

## 📌 Future Improvements

- Improve model accuracy using XGBoost or LightGBM.
- Deploy the model using Flask or Streamlit.
- Perform advanced feature engineering.
- Build an interactive web application.

---

## 👨‍💻 Author

**Mohammad Ismail Nizami**

B.Tech (CSE - AI & ML)

Machine Learning Enthusiast
