# titanic-project
📌 Project Overview
This project analyzes the Titanic dataset to understand the factors that influenced passenger survival.
Using Python in Google Colab, we cleaned the data, performed exploratory data analysis (EDA), and generated visual insights.
The goal is to identify key survival patterns based on gender, passenger class, age, and embarkation port.

📁 Dataset


File: Titanic-Dataset.csv


Rows: 891


Columns include:


Survived


Pclass


Name


Sex


Age


SibSp


Parch


Ticket


Fare


Cabin


Embarked





🔧 Steps Performed
1. Importing Libraries
Used pandas, matplotlib, and seaborn for analysis and plots.
2. Loading Dataset
The CSV file was uploaded to Google Colab using files.upload().
3. Data Cleaning


Filled missing Age values with median.


Filled missing Embarked values with mode.


Dropped the Cabin column due to too many missing values.


4. Exploratory Data Analysis
Calculated:


Overall survival rate


Survival by gender


Survival by passenger class


Survival by embarkation port


Age distribution comparison


5. Visualizations
Generated:


Bar plot: Survival vs Gender


Bar plot: Survival vs Passenger Class


Bar plot: Survival vs Embarked Port


Age distribution histogram



📊 Key Findings
✔ Overall Survival Rate
38.38%
✔ Survival by Gender


Female: 74.2%


Male: 18.8%


✔ Survival by Passenger Class


1st Class: 62.9%


2nd Class: 47.3%


3rd Class: 24.2%


✔ Survival by Embarked Port


Cherbourg: 55.3%


Queenstown: 38.9%


Southampton: 33.9%



📁 Deliverables


Python Notebook (.ipynb)


Output charts and visualizations


Project Report (PDF or Google Doc)


README.md (this file)



🚀 How to Run This Project


Open Google Colab


Upload the notebook


Upload Titanic-Dataset.csv


Run cells in order


Visualizations and analysis will appear automatically



