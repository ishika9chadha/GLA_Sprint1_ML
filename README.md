# Student Performance Analysis
This project analyzes student performance, identify eligible students, and create meaningful insights using feature creation and data visualization.

The dataset contains information about:

- Student ID
- Attendance Percentage
- Assignment Score
- Quiz Score
- Lab Completion Status

# Technologies Used
- Python
- Pandas
- Matplotlib
- Google Colab

# Features Created

# 1. Total Score

It calculates the total marks obtained by each student.

Total Score = Assignment Score + Quiz Score

# 2. Eligible Students

A student is eligible if:
- Attendance is 75% or above
- Total Score is 70 or above
- Lab work is completed

# 3. Need Improvement

Students with Total Score below 70 needs improvement and comes under category 'Yes'.

# 4. Score Gap

It shows how many marks a student needs to get a perfect score of 100.

Score Gap = 100 - Total Score

# 5. Top Batch

Students with Score Gap less than or equal to 20 are in top batch.

# Rule-Based Analysis:

# Eligible Students

Students who satisfy all eligibility conditions.

# Top Students

Students with Total Score greater than or equal to 90.

# Visualizations:

# Graph 1: Student Performance

Line chart showing Total Score of each student.

# Graph 2: Eligible vs Non-Eligible Students

Bar chart showing the number of eligible and non-eligible students.

# Graph 3: Top Batch Students

Bar chart showing students are in Top Batch or not.

# Key Insights

- Students with higher scores have smaller score gaps.
- Students scoring below 70 needs improvement.
- Eligibility depends on attendance, performance, and lab completion.
- Top Batch students are those whose marks lies between 90 and 100.
