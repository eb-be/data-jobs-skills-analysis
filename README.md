# data-jobs-skills-analysis
Analysing in-demand skills for Data Analyst, Data Scientist and Data Engineer roles using Python and Tableau. Dataset: 30,000 job listings from Naukri.com.

## Overview
This project analyses 30,000 job listings to identify the most in-demand skills for data roles. The goal was to answer one question: **what skills do you actually need to get a job in data?**

## Tools Used
- **Python** (Pandas) — data cleaning and analysis
- **Jupyter Notebook** — development environment
- **Tableau Public** — dashboard and visualisation

## Dataset
- **Source:** [Naukri.com Jobs Dataset — Kaggle](https://www.kaggle.com/datasets/promptcloud/jobs-on-naukricom)
- **Size:** 30,000 job listings
- **Note:** Dataset is sourced from India. Findings reflect global demand for data skills rather than UK-specific roles.

## Key Findings
- **Python** is the most in-demand skill, appearing in 87 job listings
- **SQL** and **Machine Learning** are joint second, appearing in 59 listings each
- **Data Analysis** and **Big Data** round out the top five

## Files
- `analysis.ipynb` — full Python analysis with line by line explanation
- `skills_count.csv` — cleaned skill demand counts
- `locations_count.csv` — job counts by location

## How To Run
1. Download the dataset from the Kaggle link above
2. Place the CSV in the same folder as `analysis.ipynb`
3. Run all cells top to bottom in Jupyter Notebook
