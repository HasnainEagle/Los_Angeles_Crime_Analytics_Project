**dataset_link  : https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/about_data**

# Los Angeles Crime Analysis

This repository contains a full analysis of **Los Angeles crime data**, including data cleaning, insights extraction using SQL, and interactive dashboards built in Power BI

## Project Overview

The goal of this project is to analyze crime patterns in Los Angeles, identify trends, and create interactive dashboards for visual exploration. This includes:

- Data Cleaning:Standardizing columns, handling missing values, creating derived features like `premises_category` and `datetime_occ`.
- SQL Analysis:Extracting insights such as crime trends by area, type, weapon used, and victim demographics.
- Power BI Dashboard:Building interactive visualizations to help understand crime patterns over time and across neighborhoods.

## Key Features

- Date & Time Processing: Combined `date occ` and `time occ` into `datetime_occ` for time-based analysis.
- Premises Categorization:Grouped `premis desc` into broader categories like Residential, Commercial, Transportation, Healthcare, etc.
- Weapon Categorization:Standardized `weapon desc` and `weapon_category`.
- Dashboard:Power BI visuals include heatmaps, bar charts, line charts, and time-series analyses.

## Tech Stack

- Python:Pandas, NumPy  
- MySQL(for insights extraction)  
- Power BI:Interactive dashboards and visualizations  
