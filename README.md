# 🎓 Student Performance Prediction

## 📌 Introduction
This project predicts student performance using machine learning models.  
It explores how study hours, absences, and subject scores influence a student’s **final score** (average marks out of 100).  

The goal is to demonstrate how data science can provide actionable insights in education.

---

## 📊 Dataset
- **Features**: Weekly self-study hours, absence days, extracurricular activities, and subject marks (Math, Physics, Chemistry, Biology, English, History, Geography).  
- **Target**: `final_score` = average of all subject scores (scaled to 100).  

---

## ⚙️ Models Used
- **Linear Regression**  
  - Baseline model with scaled inputs using `StandardScaler`.  
  - Simple regression line visualization.  

- **Random Forest**  
  - Handles non-linear relationships.  
  - Provides feature importance analysis.  

---

## 📈 Evaluation
- **Metrics**:  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

- **Results**:  
  - Random Forest outperformed Linear Regression.  
  - Feature importance revealed study hours and absences as the strongest predictors.  

---

## 📊 Visuals
- Regression line plot (Linear Regression).  
- Scatter plot of actual vs predicted scores.  
- Feature importance bar chart (Random Forest).  

---

## 🎥 Video Walkthrough
Watch the full demo here: https://www.linkedin.com/posts/emmanuel-ntim-baidoo_datascience-machinelearning-internshipproject-activity-7434737449588801537-UCNt?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF7HyO0BSpLETPoiZjRb34eepLpz7r_zz3Y

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/HUMBLE-DEV/student-performance

# Navigate into the project folder
cd student-performance

# Launch Jupyter Notebook
jupyter notebook Student_Performance.ipynb
