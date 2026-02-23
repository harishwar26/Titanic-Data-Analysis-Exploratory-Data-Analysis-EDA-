# Titanic-Data-Analysis-Exploratory-Data-Analysis-EDA-
📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on the classic Titanic dataset. The goal is to identify the key factors that influenced passenger survival rates, using statistical summaries and data visualization.
🛠️ Tools & Libraries
Python 3.x

Pandas: Data manipulation and cleaning.

Matplotlib & Seaborn: Data visualization (Statistical plotting).

Jupyter Notebook: Interactive environment for analysis.

🚀 Analysis Workflow
Data Inspection: Used .info(), .describe(), and .isnull() to understand data types and identify missing values (notably in 'Age', 'Cabin', and 'Embarked').

Univariate Analysis: Analyzed individual distributions of passenger ages, ticket fares, and survival counts using Histograms and Boxplots.

Bivariate Analysis: Investigated relationships between survival and categorical variables (Sex, Class, Port of Embarkation) using Bar plots and Countplots.

Multivariate Analysis: Created a Heatmap to visualize correlations between numerical features and a Pairplot to see multidimensional clusters.

📊 Key Findings
Gender Bias: Females had a significantly higher survival rate than males, supporting the "women and children first" historical narrative.

Class Impact: Passengers in 1st Class had the highest probability of survival, while those in 3rd Class faced the highest mortality rate.

Fare Correlation: Higher fares (associated with 1st class) show a positive correlation with survival.

Age Factor: Younger passengers (children) had a higher survival density compared to middle-aged adults.

📁 Deliverables
Titanic_EDA.ipynb: The complete Python code and visualizations.

Findings_Report.pdf: A summary report of the statistical insights and plots.
