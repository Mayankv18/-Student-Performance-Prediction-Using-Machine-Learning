# 🎓 Student Performance Prediction Using Machine Learning

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MAYANK VIJAYVARGIYA

**INTERN ID**: CITS256

**DOMAIN**: DATA ANALYTICS

**DURATION**: 6 WEEKS

**MENTOR**: NEELA SANTOSH KUMAR

## 📌 Project Overview

This project focuses on predicting student math scores using Machine Learning techniques. The objective is to analyze student performance data and build predictive models that can estimate math scores based on demographic and academic factors.

The project demonstrates the complete Machine Learning workflow, including:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Feature Importance Analysis
- Model Comparison

---

## 🎯 Problem Statement

Educational institutions often need to understand the factors that influence student performance.

The goal of this project is to build a predictive analytics model that can estimate a student's math score using information such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

## 📊 Dataset Information

**Dataset:** Students Performance Dataset

### Features

| Feature | Description |
|----------|-------------|
| gender | Student gender |
| race/ethnicity | Ethnic group |
| parental level of education | Parent education level |
| lunch | Lunch category |
| test preparation course | Course completion status |
| math score | Math marks |
| reading score | Reading marks |
| writing score | Writing marks |

### Dataset Size

- Rows: 1000
- Columns: 8

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🔄 Project Workflow

### 1. Data Loading

- Loaded dataset using Pandas
- Checked dataset structure

### 2. Data Cleaning

- Checked missing values
- Checked duplicate records
- Verified data types

### 3. Exploratory Data Analysis (EDA)

Performed:

- Histogram Analysis
- Boxplot Analysis
- Scatter Plot Analysis
- Correlation Analysis
- Bar Chart Analysis

### Key Findings

- Most students scored between 60–80 in math.
- Reading and writing scores strongly influence math performance.
- Students who completed test preparation performed slightly better.
- Strong positive relationship exists between reading and math scores.

---

### 4. Feature Engineering

Converted categorical variables into numerical format using:

```python
pd.get_dummies()
```

Applied One-Hot Encoding to make the data suitable for Machine Learning models.

---

### 5. Train-Test Split

Dataset split:

- Training Data: 80%
- Testing Data: 20%

```python
train_test_split(
    test_size=0.2,
    random_state=42
)
```

---

### 6. Machine Learning Models

The following regression models were trained and evaluated:

#### Linear Regression

- Simple and interpretable model
- Performed best on this dataset

#### Decision Tree Regressor

- Rule-based model
- Lower performance than Linear Regression

#### Random Forest Regressor

- Ensemble learning method
- Better than Decision Tree but lower than Linear Regression

---

## 📈 Model Performance

### Linear Regression

| Metric | Value |
|----------|----------|
| MAE | 4.21 |
| MSE | 29.09 |
| RMSE | 5.39 |
| R² Score | 0.88 |

### Model Comparison

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.88 |
| Random Forest Regressor | 0.84 |
| Decision Tree Regressor | 0.71 |

### Best Model

✅ Linear Regression

Reason:

The dataset contains strong linear relationships between reading score, writing score, and math score. Therefore, Linear Regression achieved the highest predictive performance.

---

## 🔍 Feature Importance

The most influential features for predicting math scores were:

- Reading Score
- Writing Score
- Gender
- Lunch Type
- Test Preparation Course

### Business Insight

Students with stronger reading and writing performance generally achieved higher math scores.

---

## 📊 Visualizations Included

- Distribution of Math Scores
- Boxplot of Math Scores
- Reading Score vs Math Score Scatter Plot
- Test Preparation vs Math Score Analysis
- Correlation Heatmap
- Feature Importance Chart

---

## 💡 Business Insights

1. Most students scored between 60–80 marks.
2. Reading and writing performance strongly influence math scores.
3. Test preparation courses positively impact performance.
4. Academic consistency across subjects improves prediction accuracy.
5. Predictive analytics can help identify performance trends in educational institutions.

---

## 🚀 Future Improvements

Future enhancements may include:

- Classification Models (Pass/Fail Prediction)
- Hyperparameter Tuning
- Cross Validation
- Streamlit Deployment
- Power BI Dashboard Integration
- Larger Educational Datasets

---

## 📚 Learning Outcomes

Through this project, I learned:

- Predictive Analytics
- Regression Modeling
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- One-Hot Encoding
- Train-Test Split
- Model Evaluation
- Feature Importance
- Model Comparison
- Business Insight Generation

---

## 🏆 Conclusion

This project successfully demonstrated the use of Machine Learning and Predictive Analytics to predict student math scores.

Among all models tested, Linear Regression achieved the best performance with an **R² Score of 0.88**, indicating strong predictive capability.

The project highlights how data-driven approaches can support educational performance analysis and decision-making.

---

## 👨‍💻 Author

**Mayank Vijayvargiya**

Data Analytics Intern

Skills:
- Excel
- SQL
- Power BI
- Python
- Machine Learning
- Predictive Analytics
