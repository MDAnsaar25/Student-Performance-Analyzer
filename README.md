# 🎓 Student Performance Prediction using Machine Learning

This project uses **Python and Machine Learning** to analyze and predict student performance based on study habits, demographics, and background data. It also visualizes the results using insightful charts.

---

## 📌 Objective

To predict a student’s average performance score using features such as:
- Hours of study
- Attendance
- Parental education
- Test preparation status
- Lunch type

---

## 🧰 Tools & Libraries Used

| Tool/Library      | Purpose                                      |
|------------------|----------------------------------------------|
| Python            | Programming language                         |
| Pandas            | Data loading and manipulation                |
| Matplotlib        | Plotting graphs and charts                   |
| Seaborn           | Enhanced visualizations                      |
| Scikit-learn      | Machine learning model & preprocessing       |
| CSV File (`Original_data_with_more_rows.csv`) | Dataset containing student scores and background info |

---

## 📁 Dataset Overview

The dataset contains:
- **Demographic info**: Gender, Ethnic Group, Parental Education
- **Support indicators**: Lunch Type, Test Preparation
- **Scores**: Math, Reading, Writing

---

## 🧠 ML Model Used

- **Model**: Linear Regression
- **Target Variable**: Average of Math, Reading, and Writing scores
- **Features**:
  - Gender
  - Ethnic Group
  - Parental Education
  - Lunch Type
  - Test Preparation

---

## 📊 Visualizations Included

- ✅ Distribution of Average Scores
- ✅ Boxplot: Test Prep vs Performance
- ✅ Scatter Plot: Math vs Reading Score
- ✅ Heatmap of Feature Correlation
- ✅ Bar Chart: Parental Education vs Average Score
- ✅ Pie Chart: Distribution of Lunch Types
- ✅ Bar Chart: Gender-wise Average Score
- ✅ Bar Chart: Test Preparation-wise Average Score

---

## 📈 Sample Insight (in Layman's Terms)

- 📚 Students who completed test prep scored **~15 points higher** on average.
- 👨‍🎓 Students whose parents had higher education levels tended to perform better.
- 🍱 Standard lunch correlated with better performance.
- 🧠 The model can predict performance with an average error of **~12.7 points**.

---

## 🛠 Installation

Install required packages using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn
