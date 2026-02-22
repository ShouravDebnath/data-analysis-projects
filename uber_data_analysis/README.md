# 🚖 Uber Ride Data Analysis

## 📌 Project Overview

This project analyzes Uber ride booking data to understand ride
patterns, customer behavior, distance trends, time-based demand, and
booking purposes.

The objective is to generate actionable insights about when, why, and
how people use Uber services.

------------------------------------------------------------------------

## 🎯 Business Questions Answered

-   In which category do people book the most Uber rides?
-   For which purpose do people book Uber rides the most?
-   At what time of day do people book Uber rides the most?
-   In which months do people book Uber rides less frequently?
-   On which days of the week do people book Uber rides the most?
-   How many miles do people usually book a cab for through Uber?

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

-   Dataset: Uber Ride Dataset
-   Records: ~1,150 rides

### Key Columns

-   START_DATE
-   END_DATE
-   CATEGORY (Business / Personal)
-   START (Location)
-   STOP (Location)
-   MILES
-   PURPOSE

------------------------------------------------------------------------

## 🛠 Project Workflow

### 1️⃣ Data Loading & Inspection

-   Loaded dataset using Pandas
-   Checked shape and data types
-   Identified missing values

### 2️⃣ Data Cleaning

-   Filled missing PURPOSE values with "NOT"
-   Converted START_DATE and END_DATE to datetime
-   Dropped rows with invalid dates

### 3️⃣ Feature Engineering

Extracted: - Date - Hour - Month - Weekday

Created Day-Night categories: - Morning - Afternoon - Evening - Night

### 4️⃣ Exploratory Data Analysis (EDA)

-   Category distribution
-   Purpose distribution
-   Time-of-day analysis
-   Monthly ride trends
-   Weekly ride trends
-   Ride distance distribution

### 5️⃣ Visualization

-   Count plots
-   Bar charts
-   Histogram (Distance distribution)
-   Time-based demand charts

------------------------------------------------------------------------

## 📈 Key Insights

-   Business category dominates Uber bookings.
-   The most common booking purpose is NOT (unspecified), followed by
    Meeting.
-   People book Uber rides mostly during the Afternoon and Evening.
-   Friday has the highest number of rides.
-   Some months show lower booking frequency, indicating seasonality.
-   The median ride distance is approximately 5.7 miles, meaning most
    trips are short-distance rides.


-----------------------------------------------------------------------