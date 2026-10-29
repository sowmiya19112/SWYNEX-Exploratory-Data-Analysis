# SWYNEX-Exploratory-Data-Analysis
Exploratory Data Analysis of Student Performance Factors using Python, Pandas and Matplotlib.
# SWYNEX – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a cleaned Student Performance Factors dataset containing 6,607 student records and 20 columns.

The objective is to understand the distribution of exam scores and explore relationships between student performance and factors such as attendance, study hours, sleep, motivation, parental involvement, and internet access.

## Objectives
- Understand the structure and quality of the dataset.
- Calculate descriptive statistics for numerical variables.
- Identify trends and patterns in student exam scores.
- Explore relationships between student-related factors and exam performance.
- Present findings through visualizations and evidence-based insights.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Dataset Information
- **Records:** 6,607
- **Columns:** 20
- **Target variable:** `Exam_Score`
- **Data quality checks:** Missing values, duplicate rows, and exam score range validation.

The dataset was cleaned during Task 1 before being used for this analysis.

## Analysis Performed
1. Dataset structure and data types.
2. Missing-value and duplicate checks.
3. Descriptive statistics for numerical variables.
4. Distribution of student exam scores.
5. Attendance and exam score relationship.
6. Study hours and exam score relationship.
7. Sleep hours and average exam scores.
8. Average exam scores by motivation level.
9. Average exam scores by parental involvement.
10. Average exam scores by internet access.

## Key Findings

### 1. Overall Exam Performance
The average exam score is **67.24**, and the median is **67**. Observed exam scores range from 55 to 100.

### 2. Attendance and Exam Scores
Attendance has a positive correlation of approximately **0.581** with exam scores. Average scores increase across the attendance groups analysed.

### 3. Study Hours and Exam Scores
Study hours have a positive correlation of approximately **0.446** with exam scores, indicating a moderate positive linear association in this dataset.

### 4. Sleep Hours and Exam Scores
The correlation between sleep hours and exam scores is approximately **-0.017**, indicating almost no linear relationship in this dataset.

### 5. Motivation Level
Students in the High motivation category have an average exam score of **67.70**, compared with **66.75** for the Low motivation category.

### 6. Parental Involvement
The High parental involvement category has an average exam score of **68.09**, while the Low category has an average of **66.36**.

### 7. Internet Access
Students with internet access have an average exam score of **67.29**, compared with **66.53** for students without internet access.

## Visualizations
The project includes charts for:
- Exam score distribution
- Attendance versus exam score
- Study hours versus exam score
- Average exam score by sleep hours

The chart files are available in the `eda_charts.zip` archive.

## Conclusion
Attendance and study hours show positive associations with exam scores in this dataset. Average exam scores also differ across motivation and parental involvement categories. Sleep hours show almost no linear correlation with exam scores.

These findings describe associations, not proof of causation. Other factors may influence student performance, and further analysis would be required to understand those relationships.

## Project Files
- `SWYNEX_Student_Performance_EDA.ipynb` – EDA notebook
- `cleaned_student_data.csv` – Cleaned dataset
- `eda_charts.zip` – Visualization charts

## Author
Sowmiya B

## Project Context
Created as part of the SWYNEX Technologies Data Analytics Internship – Task 2: Exploratory Data Analysis.
