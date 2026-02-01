🦠 COVID-19 Data Analysis using SQL & Python

This project focuses on analyzing global COVID-19 data using MySQL, Python, Pandas, and Data Visualization libraries. The goal is to extract meaningful insights related to infection rates, death rates, and vaccination progress across countries and continents.

📌 Project Overview

The project uses two CSV datasets:

CovidDeaths.csv

CovidVaccinations.csv

These datasets are imported into a MySQL database and queried using SQL.
The results are then analyzed and visualized using Python.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

MySQL

SQLAlchemy

Jupyter Notebook

📂 Project Structure
covide-19-analysis-sql-python/
│
├── notebook/
│   └── covide_19.ipynb
│
├── data/
│   ├── CovidDeaths.csv
│   └── CovidVaccinations.csv
│
├── .gitignore
├── readme.md

🗄️ Database Setup

Create a MySQL database:

CREATE DATABASE covide19;


Update database credentials in Python:

user = 'root'
password = 'password'
host = 'localhost'
database = 'covide19'


CSV files are imported into MySQL tables:

covid_deaths

covid_vaccinations

📊 Analysis Performed
🔹 Top 10 Countries by Infection Rate

Calculates maximum total cases relative to population.

Displays countries with the highest infection percentage.

🔹 Top 10 Countries by Death Rate

Analyzes total deaths per country.

Shows death percentage based on population.

🔹 Global COVID Summary

Total global cases

Total global deaths

🔹 Vaccination Analysis by Continent

Population vs total vaccinated people.

Comparison across continents.

🔹 Monthly Trend Analysis

Monthly aggregation of:

New cases

New deaths

Vaccinations

Line chart showing COVID trends over time.

📈 Visualizations Included

Bar charts for infection and death rates

Population vs vaccination comparison

Global cases vs deaths

Monthly trends of cases, deaths, and vaccinations

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/Sudip0Shrestha/covide-19-analysis-sql-python.git


Install required libraries:

pip install pandas numpy matplotlib seaborn sqlalchemy mysql-connector-python


Ensure MySQL server is running.

Open the Jupyter Notebook:

jupyter notebook

📌 Key Learnings

SQL querying on large real-world datasets

Connecting MySQL with Python using SQLAlchemy

Data cleaning and transformation

Exploratory Data Analysis (EDA)

Visual storytelling with data

👨‍💻 Author

Sudip Shrestha
BSc. CSIT
Aspiring Data Scientist

🔗 linked-in : https://www.linkedin.com/in/sudip-shrestha-532622372/

