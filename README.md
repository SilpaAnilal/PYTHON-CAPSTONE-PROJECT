# Employee Insights Analysis: A Data-Driven Study of ABC Company Teams

# Project Overview
This project focuses on analyzing a dataset containing information about ABC company team employees,consisting of 458 rows and 9 columns including their team, position, age, and salary. The goal is to explore trends, uncover insights, and visually represent key findings through Python-based data analysis and visualization techniques.

# Preprocessing Steps
1.Loaded the CSV file using pandas.

2.Corrected the data in the "height" column by replacing it with random numbers between 150 and 180.

3.Handling missing values.

# Analysis Tasks
1. Employee Distribution by Team : Counted the number of employees per team & Calculated the percentage split relative to the total dataset.

2. Segregation by Position : Counted the number of employees in each position (PG, SG, SF, PF, C).

3. Predominant Age Group : Binned ages into groups to identify the most common age range.

4. Highest Salary Expenditure : Aggregated total salary by team and position & Identified the top-spending combination.

5. Correlation Between Age and Salary : Computed Pearson correlation coefficient.


# Visual Representations
All visualizations were created using Matplotlib and Seaborn for effective data storytelling. They include:

1.Horizontal bar charts for team and salary distributions

2.Pie chart for position breakdown

3.Bar chart for age group analysis

4.Bar chart of top 10 highest salary expenditures.

5.Scatter plot with regression line for correlation.

#  Insights
Team Sizes: Most teams have 15 employees, with slight variations.

Common Positions: SGs, PFs, and PGs dominate the dataset.

Age Range: Most employees are aged between 23–28, aligning with typical athletic peaks.

Salary Trends: Certain teams (e.g., Cleveland Cavaliers) spend more on key roles like SF.

Age vs. Salary: Weak positive correlation,indicating performance drives salary more than age.



