# Machine-Learning-in-2024-Beginner's-Course

The course begins with a Machine Learning Roadmap for 2024, emphasizing career paths and beginner-friendly theory. Then it the course moves on to hands-on practical applications and a comprehensive end-to-end project using Python.

https://www.youtube.com/watch?v=bmmQA8A-yUA&t=193s


## InterQualtile

Summary of Outlier Detection Using the IQR Method
IQR (Interquartile Range): Measures the spread of the middle 50% of data. It's calculated as the difference between the third quartile (Q3) and the first quartile (Q1).

Outlier Detection: Outliers are values that are significantly higher or lower than the rest of the data.

1.5 IQR Rule:

The constant 1.5 is used to define the bounds for outliers.
Lower Bound = Q1 - 1.5 × IQR
Upper Bound = Q3 + 1.5 × IQR
Any values outside these bounds are considered outliers.
Why 1.5?:

It’s a standard choice in statistics, chosen to detect outliers while balancing sensitivity.
It helps to catch values that are unusually far from the center of the data without being overly strict.
This rule is widely used because it works well with many types of datasets, especially those that have a bell-shaped or normal distribution.