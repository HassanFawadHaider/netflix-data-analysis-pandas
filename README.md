Netflix Data Analysis using Pandas
📌 Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Netflix Movies & TV Shows dataset using Python and Pandas in Google Colab. The primary objective was to clean the dataset, explore its structure, identify meaningful patterns, and gain insights into Netflix's content library.

Throughout the project, emphasis was placed on developing an analytical mindset by asking data-driven questions, handling missing values appropriately, and interpreting results based on evidence.

🎯 Objectives
Understand the structure and quality of the Netflix dataset.
Perform data cleaning and preprocessing.
Handle missing values using appropriate strategies.
Explore the distribution of Movies and TV Shows.
Analyze content trends across decades.
Identify the major content-producing countries.
Analyze individual genres and cast members.
Document the complete analytical process and findings.
📂 Dataset Information
Dataset: Netflix Movies & TV Shows
Total Records: 8,807
Total Columns: 12
Features
Show ID
Type
Title
Director
Cast
Country
Date Added
Release Year
Rating
Duration
Listed In (Genres)
Description
🛠 Technologies Used
Python
Pandas
Google Colab
📋 Data Cleaning

The following preprocessing steps were performed:

Explored dataset structure using info() and describe().
Identified missing values using isnull().
Replaced missing values in:
Director → Unknown
Cast → Unknown
Country → Unknown
Removed records with missing values in:
Date Added
Rating
Duration
Created a new Decade feature from the release_year column.
📊 Exploratory Data Analysis

The project includes the following analyses:

✅ Movies vs TV Shows
Compared the distribution of Movies and TV Shows.
Observed that Movies dominate the Netflix catalog.
✅ Decade-wise Analysis
Created a Decade column.
Analyzed content growth across decades.
Identified the 2010s as the most content-rich decade.
✅ Country-wise Analysis
Identified the top content-producing countries.
Compared Movies and TV Shows across different countries.
✅ Genre Analysis
Transformed the multi-value listed_in column into an analysis-ready format.
Identified the most common genres, including:
International Movies
Dramas
Comedies
International TV Shows
Documentaries
✅ Cast Analysis
Transformed the multi-value cast column for individual actor analysis.
Identified the most frequently appearing actors in the dataset.
Distinguished missing cast information (Unknown) from actual actor data.
🔍 Key Findings
Movies significantly outnumber TV Shows.
The majority of Netflix content in the dataset was released during the 2010s.
Netflix offers content from a wide range of countries, highlighting its global catalog.
International Movies and Dramas are among the most common genres.
Several Indian actors appear frequently, reflecting the strong presence of Indian content in the dataset.
Proper data transformation is essential before analyzing columns containing multiple values.
📄 Project Report

A detailed project report is included in this repository, covering:

Project Overview
Dataset Description
Data Cleaning Process
Exploratory Data Analysis (EDA)
Key Findings
Limitations
Final Conclusion
📁 Repository Structure
netflix-data-analysis-pandas/
│
├── Netflix_Data_Analysis.ipynb
├── Netflix_Data_Analysis_Report.pdf
├── netflix_titles.csv
├── README.md
🚀 Future Improvements
Data visualization using Matplotlib and Seaborn.
Interactive dashboards using Power BI or Tableau.
Build a Movie Recommendation System.
Apply Machine Learning techniques for predictive analysis.
📚 What I Learned

This project strengthened my understanding of:

Data Cleaning
Missing Value Handling
Pandas Operations
Feature Engineering
Exploratory Data Analysis (EDA)
Analytical Thinking
Data Interpretation
Technical Documentation

More importantly, it taught me that data analysis is not just about writing code—it is about asking the right questions, interpreting results responsibly, and communicating insights effectively.

🤝 Connect With Me

If you have suggestions, feedback, or would like to discuss Data Analytics, Machine Learning, or AI projects, feel free to connect!

⭐ If you found this project helpful, consider giving this repository a star!
