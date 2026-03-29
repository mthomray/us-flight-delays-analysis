# US Flight Delays (2011–2020): Exploratory and Explanatory Analysis

## Overview
This project analyzes U.S. domestic flight performance data from 2011 to 2020 to better understand the factors that influence arrival delays. It is organized into two complementary parts:

- **Part I:** exploratory data analysis focused on understanding structure, distributions, missingness, and relationships in the data
- **Part II:** explanatory analysis focused on communicating the most important findings through polished visualizations

The project was completed in Python using Jupyter Notebook and common data analysis libraries.

## Project Goal
The primary goal of this analysis is to investigate flight punctuality, with a particular focus on:

- **Arrival delay (`ArrDelay`)**
- **Departure delay (`DepDelay`)**

Supporting variables include airline, month, day of week, distance, airtime, cancellation status, and diversion status.

## Dataset
The analysis is based on the **U.S. Department of Transportation Reporting Carrier On-Time Performance Dataset**. For manageability and relevance, the project uses a cleaned subset covering the most recent ten years in the sample: **2011–2020**.

### Dataset Summary
- Approximately **597,000 flight records**
- **20 variables**
- Each row represents a single domestic U.S. flight
- Variables include timing, delay, airline, route, distance, cancellation, and diversion information

Some delay-related fields contain missing values, primarily because certain flights were cancelled or diverted.

## Key Insights
The analysis produced several clear findings:

- Arrival delays are **right-skewed**, meaning most flights arrive on time or only slightly late, while a smaller number experience very large delays.
- **Departure delay is the strongest predictor of arrival delay**, showing a clear positive relationship.
- Delay patterns vary by **month** and **day of week**, suggesting seasonal and operational effects.
- Some **airlines consistently show higher average delays** than others.
- **Flight distance alone is not a strong predictor** of arrival delay, although it appears to affect delay variability.
- **Cancellations represent a distinct operational outcome**, often occurring instead of extreme delays.

## Repository Contents
- `Part_I_exploration_template.ipynb` — exploratory data analysis notebook
- `Part_I_exploration_template.html` — exported HTML version of the exploratory analysis
- `Part_II_explanatory_template.ipynb` — explanatory visualization notebook
- `Part_II_explanatory_template.html` — exported HTML version of the explanatory analysis
- `README.md` — project overview

## Notebook Descriptions

### Part I - Exploratory Analysis
This notebook focuses on exploring the cleaned dataset, understanding variable structure, identifying missing values, and examining relationships between delays and other flight characteristics.

### Part II - Explanatory Analysis
This notebook presents a smaller set of polished, audience-focused visualizations designed to communicate the most important takeaways from the exploratory phase.

## Tools Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Availability
The original cleaned CSV used during this project, `flights_clean_10yr.csv`, is not currently included in this repository.

As a result, this repository is best viewed as a **portfolio project showcase** rather than a fully reproducible analysis environment. The notebooks and HTML exports are included to document the analysis process, visualizations, and final conclusions.

## Why This Project Matters
This project demonstrates my ability to:

- clean and structure real-world data
- perform exploratory data analysis
- identify meaningful patterns in a large dataset
- create explanatory visualizations for a non-technical audience
- communicate results clearly and concisely

## Author
**Matthew Ray**
