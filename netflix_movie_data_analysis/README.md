# 🎬 Netflix Movies Data Analysis

## 📌 Project Overview

This project analyzes a Netflix movies dataset to understand genre
trends, rating behavior, popularity distribution, release growth, and
language dominance.

The objective is to generate actionable insights about movie performance
and audience engagement.

------------------------------------------------------------------------

## 🎯 Business Questions Answered

-   What is the most frequent genre of movies released on Netflix?
-   Which Vote_Average category has the highest total votes?
-   Which Vote_Average category contains the highest number of movies?
-   What movie got the highest popularity? What is its genre?
-   What movie got the lowest popularity? What is its genre?
-   Which year has the most filmed movies?
-   Which original languages dominate Netflix movies?

------------------------------------------------------------------------

## 🧰 Tools & Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## 📂 Dataset Information

-   Dataset: Netflix Movies Dataset
-   Records: \~9,800+ movies

### Key Columns

-   Release_Date
-   Title
-   Popularity
-   Vote_Count
-   Vote_Average
-   Genre
-   Original_Language

------------------------------------------------------------------------

## 🛠 Project Workflow

### 1️⃣ Data Loading & Inspection

-   Loaded dataset using Pandas
-   Checked dataset shape and data types
-   Identified missing values

### 2️⃣ Data Cleaning

-   Removed duplicate records
-   Dropped unnecessary columns
-   Converted Release_Date to datetime format

### 3️⃣ Feature Engineering

-   Extracted Year and Month from Release_Date
-   Categorized Vote_Average into:
    -   not_popular
    -   below_avg
    -   average
    -   popular
-   Split multi-genre values for accurate genre-level analysis

### 4️⃣ Exploratory Data Analysis (EDA)

-   Genre distribution analysis
-   Vote category analysis
-   Popularity analysis
-   Yearly release trend analysis
-   Language distribution analysis

### 5️⃣ Visualization

-   Bar charts
-   Count plots
-   Histograms
-   Category comparison plots

------------------------------------------------------------------------

## 📈 Key Insights

-   Drama is the most frequent genre on Netflix.
-   The "popular" Vote_Average category has the highest total votes.
-   The "average" Vote_Average category contains the highest number of
    movies.
-   English dominates as the primary original language.
-   Movie releases increased significantly in recent years.

------------------------------------------------------------------------

## ▶️ How to Run This Project

1.  Clone the repository git clone
    https://github.com/ShouravDebnath/netflix_movie_data_analysis.git

2.  Move into project folder cd netflix-movie-analysis

3.  Install required libraries pip install -r requirements.txt

4.  Run Jupyter Notebook jupyter notebook

------------------------------------------------------------------------