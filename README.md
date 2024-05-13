# HR-ANALYSIS-IN-POWER-BI
The data I used for creating an interactive dashboard in Power BI.

DATA TRANSFORMING

Firstly, I cleaned the data by removing null values and duplicates. Then, I created a new conditional column called 'Attrition Count,' where I utilized an existing column to calculate the attrition rate.

MODELING

In modeling, I created a new measure for the percentage of attrition. I simply used the percentage formula: Sum(employees) / Sum(attrition count).
