# 📘 **Student Performance Predictor**

A machine learning project designed to analyze how academic, personal, social, and economic factors influence a student's final exam score.  
The goal is to build a predictive model that estimates performance and identifies the most impactful factors contributing to academic outcomes.

This project follows a structured, multi‑day workflow:

- **Day 1:** Exploratory Data Analysis (EDA)  
- **Day 2:** Data Preprocessing  
- **Day 3:** Model Training  
- **Day 4:** Feature Importance & Insights  
- **Day 5:** API + Deployment  

---

## 📂 **Folder Structure**

```
student-performance-predictor/
│
├── data/
│   ├── StudentPerformanceFactors.csv
│   ├── train_processed.csv
│   └── test_processed.csv
│
├── notebooks/
│   ├── eda.ipynb
│   └── model_training.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── predict.py
│
├── model/
│   └── (trained ML models will be saved here)
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

# 📅 **Day 1 — Exploratory Data Analysis (Completed)**

### ✔️ Basic Dataset Inspection
- Loaded dataset  
- Checked shape, data types, missing values  
- Identified numerical and categorical columns  

### ✔️ Score Distribution
- Plotted histogram of `Exam_Score`  
- Observed performance trends and outliers  

### ✔️ Univariate Analysis
- Histograms for numerical features  
- Countplots for categorical features  

### ✔️ Feature vs Score Analysis
- Scatterplots for numerical features vs `Exam_Score`  
- Boxplots for categorical features vs `Exam_Score`  

### ✔️ Correlation Heatmap
- Identified strong predictors (Hours_Studied, Previous_Scores, Attendance)

---

## 🧠 **Key Insights from Day 1**
- **Hours_Studied**, **Previous_Scores**, and **Attendance** strongly correlate with exam performance.  
- **Motivation_Level**, **Teacher_Quality**, and **Parental_Involvement** significantly influence scores.  
- Students with **Internet_Access** and **Access_to_Resources** perform better.  
- Balanced lifestyle factors (Sleep_Hours, Physical_Activity) show moderate impact.  
- Social factors like **Peer_Influence** affect performance.

---

# 📅 **Day 2 — Data Preprocessing (Completed)**

### ✔️ Identified Numerical & Categorical Columns
Separated features into numerical and categorical groups for encoding and scaling.

### ✔️ Handled Missing Values
- Numerical → filled with mean  
- Categorical → filled with mode  

### ✔️ One‑Hot Encoding
Converted all categorical variables into numeric dummy variables using one‑hot encoding.

### ✔️ Scaled Numerical Features
Applied **StandardScaler** to normalize numerical columns.

### ✔️ Train/Test Split
Split dataset into:
- **80% training data**  
- **20% testing data**

### ✔️ Saved Preprocessed Data
Stored processed training and testing datasets for model training.

---

## 🧠 **Key Outcomes of Day 2**
- Dataset fully cleaned  
- All features numeric  
- Numerical features scaled  
- Train/test sets ready  
- Project prepared for model training (Day 3)

---

# 🚀 **Next Steps (Day 3 Plan)**
- Train multiple ML models  
- Compare performance (MAE, RMSE, R²)  
- Select best model  
- Save trained model  
- Begin feature importance analysis  

---

# 📅 **Project Status**
- **Day 1 — Completed**  
- **Day 2 — Completed**  
- Day 3 begins next.