# Student Performance Data Analysis

## Project Overview

This project focuses on exploring, cleaning, and analyzing a student performance dataset using Python and Pandas. The objective is to understand student score distributions, identify meaningful patterns, and derive actionable insights that can support educational decision-making.

---

## Dataset Information

The dataset contains information about student demographics, educational background, test preparation status, and academic scores.

### Features

* gender
* race_ethnicity
* parental_level_of_education
* lunch
* test_preparation_course
* math_score
* reading_score
* writing_score

### Dataset Size

* Rows: 1000
* Columns: 8

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning Performed

The following preprocessing steps were completed:

* Missing value inspection
* Duplicate record inspection
* Column name standardization
* Data consistency verification

### Column Standardization

Column names were converted to lowercase and special characters/spaces were replaced with underscores for improved readability and consistency.

---

## Exploratory Data Analysis

The following analyses were performed:

1. Dataset Inspection
2. Missing Value Analysis
3. Duplicate Record Analysis
4. Score Distribution Analysis
5. Statistical Summary
6. Correlation Analysis
7. Test Preparation Impact Analysis

---

## Key Findings

### 1. Test Preparation Improves Performance

Students who completed the test preparation course achieved higher average scores across all subjects.

### 2. Strong Relationship Between Reading and Writing

Reading and writing scores showed a very strong positive correlation (0.95).

### 3. Majority of Students Score Within a Moderate Range

Most students scored between 50 and 80 marks across subjects.

### 4. Mathematics Has the Lowest Average Score

Mathematics recorded the lowest average score among the three subjects.

---

## Recommendations

* Encourage participation in test preparation programs.
* Provide additional academic support for mathematics.
* Strengthen reading development initiatives.
* Offer targeted interventions for below-average performers.

---

## Project Structure

ASSIGNMENT_1/

├── data/

│ ├── StudentsPerformance.csv

│ └── cleaned_student_performance.csv

├── notebooks/

│ └── student_analysis.ipynb

├── reports/

│ └── summary_report.md

├── requirements.txt

├── README.md

└── .gitignore

---

## Author

Dhwani Jain
