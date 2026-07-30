# 📘 **Student Performance Predictor — README (Day 1)**

## 📌 **Project Overview**
The **Student Performance Predictor** is a machine learning project designed to analyze how various academic, personal, social, and economic factors influence a student's final exam score.  
The goal is to build a predictive model that can estimate a student's performance and identify the most impactful factors contributing to academic outcomes.

This project follows a structured, multi‑day workflow:
- Day 1: Dataset setup + Exploratory Data Analysis (EDA)  
- Day 2: Data preprocessing  
- Day 3: Model training  
- Day 4: Feature importance + insights  
- Day 5: API + deployment  

---

## 📂 **Folder Structure**
```
student-performance-predictor/
│
├── data/
│   └── StudentPerformanceFactors.csv
│
├── notebooks/
│   ├── eda.ipynb
│   └── model_training.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│
├── model/
│   └── (will contain trained ML models)
│
├── api/
│   └── main.py
│
└── README.md
```

---

## 📊 **Dataset Description**
The dataset contains **20 attributes** representing academic, behavioral, social, and economic factors influencing student performance.

| Attribute | Description |
|----------|-------------|
| Hours_Studied | Weekly study hours |
| Attendance | Class attendance percentage |
| Parental_Involvement | Low / Medium / High |
| Access_to_Resources | Low / Medium / High |
| Extracurricular_Activities | Yes / No |
| Sleep_Hours | Average sleep hours per night |
| Previous_Scores | Scores from previous exams |
| Motivation_Level | Low / Medium / High |
| Internet_Access | Yes / No |
| Tutoring_Sessions | Monthly tutoring sessions |
| Family_Income | Low / Medium / High |
| Teacher_Quality | Low / Medium / High |
| School_Type | Public / Private |
| Peer_Influence | Positive / Neutral / Negative |
| Physical_Activity | Weekly physical activity hours |
| Learning_Disabilities | Yes / No |
| Parental_Education_Level | High School / College / Postgraduate |
| Distance_from_Home | Near / Moderate / Far |
| Gender | Male / Female |
| Exam_Score | Final exam score (target variable) |

---

## 🔍 **Day 1 — Exploratory Data Analysis (Completed)**

### ✔️ **1. Basic Dataset Inspection**
- Loaded dataset  
- Checked shape, data types, missing values  
- Identified numerical and categorical columns  

### ✔️ **2. Score Distribution**
- Plotted histogram of `Exam_Score`  
- Observed overall performance trends  
- Identified score spread and outliers  

### ✔️ **3. Univariate Analysis**
- Visualized distributions of numerical features  
- Countplots for categorical features  

### ✔️ **4. Feature vs Score Analysis**
- Scatterplots for numerical features vs `Exam_Score`  
- Boxplots for categorical features vs `Exam_Score`  

### ✔️ **5. Correlation Heatmap**
- Generated correlation matrix for numerical features  
- Identified strong predictors (e.g., Hours_Studied, Previous_Scores, Attendance)

---

## 🧠 **Key Insights from Day 1**
- **Hours_Studied**, **Previous_Scores**, and **Attendance** show strong positive correlation with exam performance.  
- **Motivation_Level**, **Teacher_Quality**, and **Parental_Involvement** significantly influence score distributions.  
- Students with **Internet_Access** and **Access_to_Resources** tend to perform better.  
- **Sleep_Hours** and **Physical_Activity** show moderate impact — balanced lifestyle matters.  
- Social factors like **Peer_Influence** also show noticeable score differences.

These insights will guide feature engineering and model selection in the next steps.

---

## 🚀 **Next Steps (Day 2 Plan)**
- Handle missing values (if any)  
- Encode categorical variables  
- Scale numerical features  
- Train/test split  
- Prepare data for model training  

---

## 📅 **Project Status**
**Day 1 — Completed**  

---