# NYC Restaurant Inspection Data – Exploratory Data Analysis

## Objective
This project explores New York City restaurant inspection data to understand patterns in inspection grades and scores. The analysis focuses on identifying basic trends and potential indicators of poor inspection outcomes.

## Dataset
NYC Open Data – Department of Health and Mental Hygiene Restaurant Inspection Results  

The raw CSV file is not included in this repository due to size limitations.
The dataset can be downloaded directly from NYC Open Data:
https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/data_preview

## Methods
- Data cleaning and preprocessing using Python and pandas
- Handling missing and invalid inspection dates
- Feature engineering for inspection outcomes and time variables
- Exploratory data analysis using simple visualizations

## Key Findings
- Most graded inspections result in an A grade.
- Roughly 10% of graded inspections receive a B or C.
- Inspection scores are generally low, with a small number of extreme values.

## Limitations
Not all inspections result in a final grade, and some records lack valid dates. This project is exploratory and does not attempt to establish causal
relationships.

## How to Run
Open and run `notebooks/01_eda.ipynb` in Jupyter Notebook after installing dependencies listed in `requirements.txt`.