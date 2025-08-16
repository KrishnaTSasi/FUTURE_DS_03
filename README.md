# FUTURE_DS_03


# 🎓 Student Feedback Analysis

This project analyzes student feedback data collected from Kaggle website. The aim is to extract insights from ratings and comments to improve teaching methods, course structuring and overall student satisfaction.


## 📂 Dataset Description

The dataset contains feedback from students with the following features:

| Column                                                 | Description                                     |
| ------------------------------------------------------ | ----------------------------------------------- |
| `Unnamed: 0`                                           | Index column (can be dropped)                   |
| `Student ID`                                           | Unique identifier for each student              |
| `Well versed with the subject`                         | Rating (1–10) on faculty subject expertise      |
| `Explains concepts in an understandable way`           | Rating (1–10) on teaching clarity               |
| `Use of presentations`                                 | Rating (1–10) on effectiveness of presentations |
| `Degree of difficulty of assignments`                  | Rating (1–10)                                   |
| `Solves doubts willingly`                              | Rating (1–10)                                   |
| `Structuring of the course`                            | Rating (1–10)                                   |
| `Provides support for students going above and beyond` | Rating (1–10)                                   |
| `Course recommendation based on relevance`             | Rating (1–10)                                   |
| `Comments`                                             | Open-ended text feedback from students          |


## 🎯 Project Tasks

1. **Data Cleaning & Preprocessing**

   * Handled missing values
   * Drop unnecessary columns (`Unnamed: 0`)
   * Convert ratings to numeric format

2. **Exploratory Data Analysis (EDA)**

   * Distribution of student satisfaction
   * Trends in ratings across aspects
   * Identify weak/strong areas

3. **Sentiment Analysis (Text Feedback)**

   * Used **TextBlob / VADER** to calculate polarity & subjectivity
   * Generated word cloud of common feedback

4. **Correlation & PCA Analysis**

   * Heatmap of relationships between feedback aspects
   * PCA to find hidden patterns in student satisfaction

5. **Visualization**

   * Charts for distribution, heatmaps, sentiment analysis
   


## 🪜 Steps Followed

1. **Load Dataset** → Import CSV from Google Drive.
2. **Clean Data** → Remove empty values, normalize rating scales.
3. **EDA** → Plot histograms & bar charts for ratings.
4. **Sentiment Analysis** → Analyze comments to capture emotions.
5. **Correlation Analysis** → Identify overlaps in rating categories.
6. **PCA/Clustering** → Group feedback into meaningful clusters.
7. **Export Outputs** → Save cleaned dataset and charts.


##  Conclusion

* Students are **generally satisfied** but want **simpler assignments** and **better clarity in explanations**.
* Faculty are **well-versed in subjects** but should improve **student support mechanisms**.
* Recommendations can guide course improvements and faculty training.



