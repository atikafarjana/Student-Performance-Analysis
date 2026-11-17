# Student Performance Analysis and Visualization Using Python

**A Beginner-Level Data Analysis Project**

**Prepared by:** Atika Farjana  
**Course:** AI Programming with Python

---

## 1. Introduction

This project applies foundational Python programming and data analysis techniques to a generated student dataset. It uses NumPy for numerical operations, Pandas for data handling, and Matplotlib and Seaborn for visualization. The work is based on the ten tasks in the course assignment.

## 2. Project Objectives

- Create and inspect numerical arrays for student scores and attendance.
- Calculate descriptive statistics and identify students scoring above the average.
- Load, inspect, filter, and sort student records using Pandas.
- Apply department-based score adjustments while capping scores at 100.
- Create visualizations to explore score distributions, department summaries, grades, and attendance.

## 3. Dataset Description

The dataset contains 50 generated student records, with student IDs from 201 to 250. It includes six fields:

- `student_id`
- `student_age`
- `score`
- `attendance`
- `department`
- `grade`

The starter code uses NumPy's random seed 42 to make dataset generation reproducible.

### Dataset Summary

| Metric | Value | Meaning |
|---|---:|---|
| Number of records | 50 | Generated student entries |
| Average original score | 67.30 | Mean of original scores |
| Minimum original score | 41 | Lowest original score |
| Maximum original score | 99 | Highest original score |
| Average attendance | 79.58% | Mean attendance percentage |

## 4. Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## 5. Methodology and Tasks

The project consists of ten analysis tasks.

### Q1 – NumPy Arrays
Extracted score and attendance arrays and inspected their data type, dimensions, shape, and number of elements.

### Q2 – Numerical Statistics
Calculated maximum, minimum, average score, and average attendance, then selected scores above the average.

### Q3 – Pandas Operations
Loaded the CSV, displayed initial records and descriptive information, selected specified columns, filtered ages from 16 to 20, sorted by student ID, and displayed the final three rows.

### Q4 – Score Adjustment
Increased scores by 10% for Computer Science and Mathematics and by 5% for all other departments, with a maximum score of 100.

### Q5 – Department Average Chart
Created a Matplotlib bar chart of average department scores using the adjusted scores from Q4.

### Q6 – Score Histogram
Created a 10-bin histogram of the original score distribution.

### Q7 – Attendance and Score
Created a scatter plot comparing attendance percentage with original score.

### Q8 – Grade Comparison
Used a Seaborn bar plot to compare average scores across grade categories.

### Q9 – Department Count
Created a Seaborn count plot showing the number of records in each department.

### Q10 – Department-Colored Scatter Plot
Created a scatter plot of attendance versus score, using department as the color grouping.

## 6. Visual Results

The project includes six visualizations to explore student performance and dataset characteristics.

1. **Figure 1:** Average Score by Department (adjusted scores from Q4).
2. **Figure 2:** Distribution of Student Scores (10 bins).
3. **Figure 3:** Attendance vs Score.
4. **Figure 4:** Score Distribution by Grade (Seaborn bar plot).
5. **Figure 5:** Number of Students per Department.
6. **Figure 6:** Attendance vs Score by Department.

## 7. Findings

The generated dataset has an average original score of 67.30 and average attendance of 79.58%. Scores range from 41 to 99.

The visualizations provide several descriptive views:

- Department-level averages.
- Overall score distribution.
- Grade-group score averages.
- Department record counts.
- Relationship between attendance and scores.

The scatter plots allow visual inspection of attendance and score patterns, but they do not prove a causal relationship.

## 8. Limitations

- The dataset is synthetic, generated for practice, and does not represent a real school.
- There are only 50 records, so department-level groups may be small or unequal.
- The project is descriptive and does not train or evaluate a machine learning model.
- A scatter plot alone cannot establish that attendance causes a change in academic score.

## 9. Conclusion

This project demonstrates a complete beginner-level workflow for creating a dataset, performing numerical and tabular analysis, and communicating results through charts. It reinforces practical use of NumPy, Pandas, Matplotlib, and Seaborn and provides a foundation for future study in data analysis and machine learning.

## 10. Reproducibility Note

The portfolio notebook copy aligns the variable names used in Q2 with the arrays created in Q1 so that the notebook can run sequentially in a fresh runtime.

This is a small reproducibility correction; the original uploaded assignment file is not overwritten.

Q5 uses the adjusted scores created in Q4, while Q6–Q10 reload the original CSV and therefore visualize original scores.
