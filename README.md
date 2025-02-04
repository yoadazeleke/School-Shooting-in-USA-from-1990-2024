# School Shootings in the USA from 1990-2025: A Data Analysis Project

## Introduction
As a person who attended school in the United States, school shootings have always been a serious concern. Over the years, we’ve seen the devastating impact of these events on students, families, and entire communities. This project aims to understand the patterns behind school shootings in the USA, from 1990 to 2025, and how data analysis can provide insights into trends, severity, and geographic areas most affected. By analyzing this data, we can contribute to the development of better laws, regulations, and policies that could ultimately help prevent such tragedies and improve school safety across the nation.

## Why This Project?
School shootings have long been an issue affecting our nation’s youth and education system. As an advocate for using data to inform decisions, I believe that data analysis can help us better understand the factors surrounding these events, potentially shaping more effective policies, regulations, and laws. By exploring the historical data on school shootings, we can identify key trends, hotspots, and patterns that can guide future legislative actions and preventive measures.

# Contents
* Day 1 - Data Cleaning and Missing Information (Completed)
* Day 2 - Summarizing and Analyzing Data (Coming Soon)
* Day 3 - Visualizations in Tableau (Coming Soon)
* Day 4 - Write Report and Share on GitHub & LinkedIn (Coming Soon)

## Day 1: Data Cleaning and Missing Information
**Data Cleaning Documentation**  
**Link to Dataset:** [School Shootings in USA from 1990-2024](https://www.kaggle.com/datasets/ecodan/school-shootings-us-1990present?select=pah_wikp_combo.csv)

### Overview
This dataset represents school shootings, containing information about incident dates, locations, severity, and other related attributes. The goal of Day 1 was to clean and transform the data to ensure consistency, completeness, and accuracy, making it ready for analysis. Below is an outline of the steps taken during the data cleaning process.

### Original Dataset Attributes
* **Date**: The date of the shooting incident.
* **City**: The city where the shooting occurred.
* **State**: The state where the shooting took place.
* **AreaType**: The type of area (urban, suburban, or rural) of the shooting.
* **School**: The type of school where the incident occurred (e.g., high school, middle school, etc.).
* **Fatalities**: The number of fatalities in the shooting.
* **Wounded**: The number of individuals wounded in the incident.
* **Dupe**: Duplicate rows indicating repeated data entries.
* **Source**: The source of the data (e.g., media outlet, governmental report).
* **Desc**: A brief description of the incident.

### Transformed Dataset Attributes
* **Date**: The date of the shooting incident.
* **City**: The city where the shooting occurred.
* **State**: The state of the shooting.
* **AreaType**: The classification of the area (urban, suburban, rural).
* **School**: The type of school (e.g., high school, middle school).
* **Fatalities**: The number of fatalities.
* **Wounded**: The number of wounded individuals.
* **Month**: The month when the shooting incident occurred.
* **Day of Week**: The day of the week when the shooting occurred.
* **Region**: The region of the United States where the shooting occurred (Northeast, South, Midwest, West).
* **Severity**: The severity of the shooting, classified as "Low", "Moderate", or "High".
