# students_eda
Exploratory Data Analysis on the Students Performance dataset to understand factors affecting math, reading, and writing scores using Python, Pandas, and Seaborn.



Dataset Information

The dataset contains 1000 student records with information about demographic factors and exam scores.

Dataset Shape
Rows: 1000
Columns: 8
Exploratory Data Analysis Process

The following steps were performed during EDA:

1️ Data Understanding
Loaded the dataset using Pandas
Checked dataset structure using head(), info(), and shape
2️ Data Cleaning
Verified missing values
Checked for duplicate records
Ensured correct data types
3️ Statistical Summary

Used the describe() function to analyze:

Mean
Standard deviation
Minimum and maximum values
Quartiles
 Data Visualization

Different visualization techniques were used to understand patterns in the dataset:

Histogram → Distribution of exam scores
Boxplot → Detect outliers in scores
Bar plots → Compare categorical variables
Scatter plots → Relationship between exam scores
Heatmap → Correlation between numerical variables
Correlation Analysis

A correlation matrix was created to study relationships between the exam scores.

Key Correlations
Variables	Correlation
Math & Reading	0.82
Math & Writing	0.80
Reading & Writing	0.95

Observation:
Reading and writing scores have a very strong positive correlation, indicating students who perform well in reading also tend to perform well in writing.

 Key Insights
1️ Reading and Writing Performance

Students with high reading scores usually have high writing scores, showing strong skill overlap.

2️ Test Preparation Impact

Students who completed the test preparation course generally scored higher in all subjects.

3️ Lunch Type Influence

Students with standard lunch tend to perform better academically compared to those with free/reduced lunch.

4️ Math Performance

Math scores show strong correlation with both reading and writing, but slightly lower compared to reading-writing correlation.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
erns and identify factors that influence academic success.
