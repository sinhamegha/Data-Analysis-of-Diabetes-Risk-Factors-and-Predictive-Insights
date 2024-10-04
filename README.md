Diabetes Analysis Project
This project analyzes a dataset of health indicators to explore the key factors contributing to diabetes. Using statistical methods, visualizations, and machine learning models, the analysis identifies significant correlations and patterns that link diabetes with other health conditions such as high blood pressure, high cholesterol, BMI, physical activity, and more.

Table of Contents
.   Project Overview
•	Data
•	Installation
•	Analysis Summary
•	Key Findings
•	Visualizations
Project Overview
The aim of this project is to perform an in-depth analysis of health data to identify key factors associated with diabetes. The dataset contains several health-related variables such as BMI, blood pressure, cholesterol levels, physical activity, and general health ratings, among others. Through exploratory data analysis, correlation studies, and visualizations, the project seeks to uncover meaningful insights that can aid in understanding the relationship between diabetes and other health conditions.

Data
The dataset used in this project is a health survey with the following variables:

•	Diabetes_binary: Indicates whether an individual has    been diagnosed with diabetes.
•	HighBP: Indicator of high blood pressure.
•	HighChol: Indicator of high cholesterol.
•	Smoker: Whether the individual is a smoker.
•	Stroke: Indicates if the individual has had a stroke.
•	HeartDiseaseorAttack: Indicates heart disease or a heart attack.
•	PhysActivity: Engagement in physical activity.
•	Fruits: Consumption of fruits.
•	Veggies: Consumption of vegetables.
•	BMI: Body Mass Index.
•	Age: Age group of the individual.
•	Education: Education level of the individual.
•	Income: Income category of the individual.
Installation
To run this project, you need Python 3.x and the following Python libraries:

.   pandas
•	seaborn
•	matplotlib
•	plotly
•	dython
•	scipy
Analysis Summary
This project explores several key questions related to diabetes, such as:

•	The relationship between diabetes and high blood pressure.
•	The prevalence of high cholesterol among individuals with diabetes.
•	The impact of BMI on the likelihood of developing diabetes.
•	The connection between physical activity, general health, and diabetes.
•	The percentage of individuals with diabetes who have also suffered a stroke or heart disease.
Statistical tests, such as chi-square tests, are used to measure the significance of relationships between categorical variables.

Key Findings
•	High Blood Pressure: Individuals with diabetes are twice as likely to have high blood pressure (75.27%) compared to non-diabetics (37.42%).
•	High Cholesterol: A higher percentage of individuals with diabetes (67.01%) also have high cholesterol compared to those without diabetes (38.13%).
•	BMI: The average BMI of people with diabetes is significantly higher (31.94) than those without diabetes (27.77).
•	Physical Activity: Despite their condition, 63.05% of individuals with diabetes engage in regular physical activity.
•	Heart Disease: There is a significant correlation between diabetes and heart disease, with many individuals experiencing both conditions.
Visualizations
This project generates various visualizations to better understand the data, including:

•	Correlation heatmaps for categorical variables.
•	Bar plots showing the relationship between diabetes and high blood pressure.
•	Pie charts for physical activity and general health.
•	Heatmaps to illustrate the co-occurrence of high blood pressure and high cholesterol.
•	Violin plots to compare age distribution between individuals with and without diabetes.
All visualizations are created using matplotlib, seaborn, and plotly. You can find the visualizations in the visualizations folder.

Contributing
