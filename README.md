Airbnb Neighbourhood Review Analysis

Project Overview

This project analyzes Airbnb property listings and reviews, focusing on neighbourhood dynamics and host verification impacts using a comprehensive dataset of over 83,000 entries and 24 features. The analysis includes exploratory data analysis (EDA), data preprocessing, statistical insights, and visualizations with Python’s data science libraries. It aims to derive actionable insights for business strategy, neighbourhood comparison, and user preference modeling.

Dataset Description

Rows: 83,411 entries

Columns: 24 features, including property type, price, reviews, location info

Key Columns: neighbourhood group, room type, review rate number, host identity verified, price, availability 365

Major Neighbourhoods: Brooklyn, Manhattan, Queens, Bronx, Staten Island

Room Types: Entire home/apt, Private room, Shared room, Hotel room

Analysis Workflow

Data Loading & Cleaning

Handled missing values, formatted datatypes (floats, dates, integers), and reviewed memory usage

Exploratory Data Analysis

Summary statistics for price, service fee, number of reviews, neighbourhood distribution

Count and percent breakdown of different property and room types

Analysis of neighbourhood group with highest listings (Brooklyn and Manhattan lead)

Visualization

Bar plots for listings per neighbourhood and review rates by property type

Distribution plots for price, service fee, review ratings

Review Analysis

Grouped by neighbour group and room type to estimate average review scores

Compared verified vs. unverified host impact on review scores

Found that verified hosts marginally receive higher average ratings (3.28 vs. 3.27)

Explored review trends per neighbourhood and property type for business recommendations

Key Results

Most Listings: Brooklyn (34,636) and Manhattan (34,566) dominate the market

Review Insights: Hotel rooms and private rooms generally score higher; verified hosts tend to receive better reviews

Neighbourhood Dynamics: Each area shows unique price and review distributions useful for targeted marketing and property investment

<img width="1086" height="664" alt="image" src="https://github.com/user-attachments/assets/59730f3c-94a7-4318-b98b-56eba48a87c3" />

<img width="1145" height="706" alt="image" src="https://github.com/user-attachments/assets/d9d73492-9a7d-4021-92b4-1e1e31484060" />

<img width="842" height="585" alt="image" src="https://github.com/user-attachments/assets/7cce9750-a403-4edb-9d9b-facf88662bc1" />

Libraries Used

Python (Jupyter Notebook / Colab)

Pandas, NumPy for data analysis

Matplotlib, Seaborn for visualization

Scikit-learn for any modeling or statistical inference (if applicable)

How to Run
Clone this repository

Open VOIS_AICTE_Oct2025_Tejashri_Wagh.ipynb in JupyterLab or Google Colab

Ensure required Python libraries (pandas, matplotlib, seaborn, etc.) are installed

Run each cell step by step to review data analysis, EDA visualizations, and insights

Project Structure
VOIS_AICTE_Oct2025_Tejashri_Wagh.ipynb (Main notebook: Cleaning, EDA, Visualizations)

README.md (Project overview and instructions)
