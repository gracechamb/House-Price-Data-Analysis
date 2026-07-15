# House Price Data Analysis — Python Project

## Situation
As a data analyst for a real estate agency, I was given a housing dataset and asked to 
identify trends that could inform business decisions, with a focus on understanding what 
factors influence house prices.

## Task
Analyze the dataset to understand pricing patterns, evaluate the relationship between 
home size and price, flag potential data quality issues, and demonstrate a full data 
pipeline from raw data to structured storage.

## What I Did
Cleaned and analyzed a residential housing dataset in Python, using pandas for data 
transformation and Plotly for interactive visualizations to examine price distribution and 
the relationship between living space and price, flagging likely data-entry errors along 
the way. Persisted the cleaned data into a SQLite database to demonstrate a full 
pandas-to-SQL pipeline.

## Key Findings
- House prices are heavily right-skewed, with most homes priced between $300K–$650K and 
  a median around $461K.
- A small number of high-end outliers (47 homes above $2M) compress the distribution and 
  make it harder to read.
- 49 records showed a price of $0, likely data entry errors rather than real listings.
- Living space shows a general positive relationship with price, but it's loose rather 
  than tight — homes of similar size often sell for very different prices.
- Two extreme outliers (a $26.6M home at 1,180 sqft, and a $12.9M home at 2,190 sqft) were 
  flagged as likely data errors rather than legitimate high-value sales.

## Key Skills / Technologies
- Python (pandas, Plotly)
- Data cleaning & transformation
- Exploratory data analysis (EDA)
- Data visualization (histograms, scatter plots)
- SQLite (`sqlite3`)
- Outlier detection

## Files
- `Real_Estate_Data_Analysis.ipynb` — full notebook with code and analysis
