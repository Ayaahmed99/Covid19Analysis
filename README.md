📊 COVID-19 Data Exploration in SQL Server
📌 About This Project

In this project, I explored a real COVID-19 dataset using SQL Server to analyze cases, deaths, and vaccination trends across different countries and continents.

The goal was to practice data cleaning, aggregation, and advanced SQL techniques while answering real analytical questions like:

Which countries had the highest infection rate?
What is the death percentage compared to total cases?
How did vaccination progress over time?
Which continent was most affected?

This project helped me strengthen my SQL skills and improve how I structure analytical queries.

🛠 What I Did
1️⃣ Data Cleaning
Filtered out aggregated regions using continent IS NOT NULL
Fixed divide-by-zero errors using NULLIF()
Ensured accurate percentage calculations
2️⃣ Exploratory Data Analysis

I calculated:

Total global cases and total deaths
Death percentage per country (e.g., Egypt)
Cases compared to population
Countries with highest infection rate
Countries with highest death rate
Continents with highest total deaths
3️⃣ Vaccination Analysis
Joined CovidDeaths and CovidVaccinations tables
Used Window Functions (SUM OVER PARTITION BY) to calculate rolling vaccination totals
Calculated percentage of population vaccinated
Built:
A CTE for cleaner query structure
A Temporary Table for step-by-step analysis
A View for reusable reporting
💡 SQL Concepts Used
JOIN
GROUP BY
SUM() and MAX()
Window Functions (OVER (PARTITION BY ORDER BY))
CTEs
Temporary Tables
Views
Error handling with NULLIF()
🎯 What I Learned
How to handle real-world messy data
How to prevent calculation errors in SQL
How to use window functions for running totals
How to structure queries in a clean and readable way
How to think analytically about data instead of just writing queries
🖥 Tools Used
Microsoft SQL Server

📈 Why I Built This

As someone learning data analysis, I wanted to work on a real dataset and apply SQL beyond simple SELECT statements. This project represents my progress in writing more advanced queries and building reusable analytical solutions.
