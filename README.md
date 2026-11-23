# Exploratory Data Analysis (EDA) on Visa Dataset

## 📌 Project Overview
This repository contains an Exploratory Data Analysis (EDA) of a visa application dataset. The primary goal of this project is to uncover patterns, trends, and key factors influencing visa approval rates across different applicant demographics, job roles, regions, and employer profiles.

## 🎯 Objectives
- Perform data cleaning and preprocessing (handling missing values, duplicates, and data type conversions).
- Conduct univariate, bivariate, and multivariate analysis to understand feature distributions.
- Identify the strongest predictors and correlations associated with visa approval or denial (`case_status`).
- Visualize insights clearly to support data-driven conclusions and future predictive modeling.

## 📂 Dataset Description
The dataset includes historical records of visa applications with features such as:
- **`case_id`**: Unique identifier for each visa application.
- **`continent`**: Continent of the applicant's origin.
- **`education_of_employee`**: Highest level of education attained by the applicant (e.g., High School, Bachelor's, Master's, Doctorate).
- **`has_job_experience`**: Whether the applicant has prior work experience (`Y`/`N`).
- **`requires_job_training`**: Whether the role requires on-the-job training (`Y`/`N`).
- **`no_of_employees`**: Size of the sponsoring employer.
- **`yr_of_estab`**: Year the sponsoring company was established.
- **`region_of_employment`**: Geographic region where the job is located.
- **`prevailing_wage`**: Average wage paid to similarly employed workers in the area.
- **`unit_of_wage`**: Unit of the prevailing wage (Hour, Week, Month, Year).
- **`full_time_position`**: Whether the position is full-time (`Y`/`N`).
- **`case_status`**: Target variable indicating whether the visa was **Certified** or **Denied**.

*(Note: Adjust or remove any column names above if your specific dataset schema differs.)*

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly *(remove if unused)*
- **Environment:** Jupyter Notebook

## 📊 Key Insights & Findings
*(Customize these bullet points with the exact numbers from your analysis)*
- **Education Impact:** Applicants with a Master's or Doctorate degree showed significantly higher approval rates compared to those with only a High School diploma.
- **Work Experience:** Prior job experience positively correlates with visa certification.
- **Regional Trends:** Certain employment regions exhibited higher application volumes and distinct approval patterns.
- **Wage Analysis:** Higher prevailing wages generally aligned with higher approval probabilities.
