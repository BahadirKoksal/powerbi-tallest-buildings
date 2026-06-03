# Power BI – Tallest Buildings Analysis

## Project Overview
This project involves data cleaning and visualization of the world's tallest buildings using Power BI. The dataset was sourced from Wikipedia and contains 133 buildings with information about height, floors, country, and year built.

## Dataset
- **Source:** Wikipedia – List of tallest buildings
- **File:** `Wiki_buildings_PowerBI.pbix`
- **Rows:** 133 buildings
- **Original columns:** Description, Built, Country, Floors, Height (ft), Rank

## Data Cleaning (Power Query Editor)
- Split the `Description` column into three new columns: **Building**, **City**, and **Height (m)**
- Removed unwanted text (`meters`, `)`) from the Height column
- Created a custom column: **Average floor height (m)** = Height / Floors

## Visualizations
- **Column Chart:** Number of buildings constructed per year
- **Matrix:** Maximum floors and maximum height per country

## Key Findings
- UAE has the tallest building: Burj Khalifa (828m, 163 floors)
- Construction peaked around 2015
- China leads in total number of tall buildings
