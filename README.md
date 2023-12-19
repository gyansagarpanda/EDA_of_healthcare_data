# EDA-of-Healthcare-data
Data analysis and exploration project aimed at understanding and visualizing factors that influence whether patients show up for their medical appointments.
LinkedIn article: https://www.linkedin.com/pulse/exploratory-data-analysis-healthcare-gyan-sagar-panda-skebf


**Project Overview**:
This project focuses on analyzing a dataset related to medical appointments. The primary goal is to understand the factors that affect whether patients attend their scheduled appointments or not. The dataset contains information about various aspects, including patient demographics, appointment details, and medical conditions.

**Data Import and Cleaning**:
The project starts by importing essential Python libraries for data analysis, such as Pandas, NumPy, Matplotlib, Seaborn, and datetime. Then loads a dataset from a CSV file and performs initial data exploration.

**Data Modification**:
The project standardizes date and time information, converting them into a consistent format. It calculates the weekdays for both the scheduled day and appointment day and assigns them numerical values (0 for Monday, 1 for Tuesday, and so on) for further analysis. Some column names are also renamed to make them more consistent and understandable.

**Data Exploration and Visualization**:
The project involves in-depth data exploration and visualization. Begins with a bar chart showing the distribution of the target variable, "NoShow," which represents whether patients attended their appointments (Yes or No). The percentages of appointments with and without no-shows are also calculated and displayed.

**Handling Missing Data**:
Checks for missing data, but finds none in this dataset. Mention the general guidelines for dealing with missing data, such as regression imputation for features with few missing values and considering dropping columns with a high percentage of missing values.

**Data Cleaning**:
While no missing data is present, the project demonstrates how to group data, as in the case of age groups, by defining labels and removing the original "Age" column.

**Data Exploration Continues**:
Proceeds to explore the dataset more deeply, displaying the counts and distributions of various features in relation to the "NoShow" variable. This provides insights into how factors like gender, age groups, neighborhood, scholarship status, hypertension, diabetes, and SMS reminders relate to appointment attendance.

**Data Transformation**:
The "NoShow" column is converted into binary values (0 and 1) to facilitate predictive modeling or correlation analysis.

**Dummy Variables**:
Creates dummy variables for each categorical features, (which is a common step in preparing data for machine learning models).

**Correlation Analysis**:
Then performs correlation analysis to understand the relationships between all predictors and the "NoShow" variable. This is visualized through bar plots and a heatmap, allowing for a quick assessment of which features may be more influential in predicting no-shows.

**Bivariate Analysis**:
Explores specific relationships, such as the impact of hypertension or age group on no-shows. To visualizes these relationships using count plots.

**Key Insights**:
In conclusion, this project provides several key insights, such as the gender distribution of patients, the influence of age groups on appointment attendance, the high show rate across neighborhoods, and the varying impact of factors like scholarships, hypertension, diabetes, and SMS reminders on appointment attendance. The project also highlights the absence of appointments on Sundays and the limited appointments on Saturdays.

This project aims to lay the groundwork for further analysis or predictive modeling related to appointment attendance, potentially helping medical facilities improve their patient appointment scheduling and reduce no-shows.
