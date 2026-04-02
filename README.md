# 📊 Student Performance Analysis using Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a student performance dataset to uncover patterns, relationships, and key factors influencing academic outcomes. The analysis focuses on understanding how behavioral, academic, and external factors contribute to overall student success.

The entire analysis is performed using Python with libraries such as NumPy, Pandas, Matplotlib, and Seaborn, with a strong emphasis on visual storytelling and data-driven insights.

---

## 🎯 Objectives

* Perform detailed exploratory analysis on student performance data
* Identify key factors affecting academic success
* Analyze relationships between study habits, attendance, and scores
* Compare performance across different categories such as gender and resources
* Extract meaningful insights for decision-making and future modeling

---

## 📂 Dataset Description

The dataset consists of academic and behavioral attributes of students:

| Feature               | Description                             |
| --------------------- | --------------------------------------- |
| gender                | Gender of the student                   |
| study_hours_per_day   | Average daily study hours               |
| attendance_percentage | Student attendance percentage           |
| sleep_hours           | Average hours of sleep                  |
| assignment_score      | Marks obtained in assignments           |
| midterm_score         | Marks obtained in midterm exams         |
| final_exam_score      | Marks obtained in final exams           |
| overall_score         | Overall performance score               |
| grade                 | Final grade obtained                    |
| internet_access       | Availability of internet (Yes/No)       |
| extra_classes         | Participation in extra classes (Yes/No) |

---

## 🧹 Data Preprocessing

* Removed irrelevant columns (e.g., `student_id`)
* Checked for missing values (dataset found to be clean)
* Verified data types and ensured consistency
* No feature engineering performed — analysis is based solely on original features

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Examined the distribution of key variables such as:

  * Study hours
  * Attendance
  * Scores
* Identified trends, spread, and skewness using histograms and KDE plots

---

### 🔹 Bivariate Analysis

* Study hours vs overall score → strong positive relationship
* Attendance vs performance → significant correlation
* Sleep vs performance → moderate influence
* Gender vs performance → minimal variation

---

### 🔹 Multivariate Analysis

* Correlation heatmap revealed strong relationships between:

  * Final exam score and overall score
  * Midterm and assignment scores with overall performance

* Pairplots provided a holistic view of relationships between multiple variables

---

### 🔹 Categorical Analysis

* Grade-wise comparisons showed:

  * Higher grades associated with higher study hours and attendance
* Internet access and extra classes:

  * Slight improvement in performance observed

---

### 🔹 Aggregation-Based Analysis

* Grouped analysis using `groupby()`:

  * Compared average scores across gender
  * Evaluated impact of internet access and extra classes
* Pivot tables and heatmaps used for compact insights

---

## 📈 Visualizations Used

This project includes a diverse range of visualizations:

* **Distribution Plots:** Histogram, KDE
* **Comparison Plots:** Bar plot, Box plot, Violin plot
* **Relationship Plots:** Scatter plot, Pairplot
* **Aggregation Plots:** Grouped bar charts
* **Correlation Analysis:** Heatmaps
* **Advanced Visuals:** Pivot-based heatmaps

---

## 🔑 Key Insights

1. **Study Hours as a Primary Driver**
   Students who dedicate more time to studying consistently achieve higher scores.

2. **Attendance is Crucial**
   Attendance shows a strong and consistent relationship with academic performance.

3. **Final Exams Have Maximum Impact**
   Final exam scores contribute the most to overall performance.

4. **Balanced Sleep Matters**
   Moderate sleep duration is associated with better academic outcomes.

5. **Minimal Gender-Based Differences**
   Academic performance is largely independent of gender.

6. **External Support Factors**
   Internet access and extra classes provide a slight performance advantage.

7. **Consistency in High Performers**
   Top students perform well across all evaluation components, indicating balanced academic strength.

---

## 🧠 Key Takeaways

* Academic success is driven more by **behavioral consistency** than demographic factors
* Regular study habits and attendance outweigh external influences
* Performance improvements should focus on discipline and engagement

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
