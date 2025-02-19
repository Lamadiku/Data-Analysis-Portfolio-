
# 👮 Crime Analysis in NYC🗽 (2023)
The goal of this capstone project is to understand the trends and patterns of
arrest incidents across NYC in 2023. The analysis will involve the types/frequency of
crimes per borough in New York City, and the demographics such as age group,
gender and race of perpetrators. The targeted audience for this analysis would be
mainly the residents living in New York City and people visiting as well as the policy
makers of the city. The key insights in this project will be critical to help guide NYC's
future policies and invest resources in targeted areas to enact safety measures for the
public.

# 📰 Methodology:
Python and Excel were used to analyze the data.
Tableau was used for data vilualization.

# Overview:
The NYPD Arrests Data for this project includes public arrest report from New York Police Department (NYPD). Every quarter, NYPD Arrest data has been manually extracted and reviewed by the Office of Management Analysis and Planning before being posted on the NYC OpenData website since 2006. 
Each record represents arrest in NYC by the NYPD and includes information about the type of crime, the location and prepetrator's demographics.

The original size of this dataset is 19 columns and 5.72M rows.

Data Source: https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u/about_data

# 🔍 Data Cleaning:
1. The data was filtered for the year of 2023
2. Arrest_Date column was converted from string to date values
3. 17 Missing values were found on column OFNS_DESC (Oﬀense Description)
4. Removed columns (such as Lon_Lat, X_COORD_CD, Y_COORD_CD,
   ARREST_PRECINCT, LAW_CODE) from original dataset
6. Dropped Null values instead of replacing with 0
7. Added full form of abbreviated values in columns such as Arrest Boroughs and
8. Prepetrator’s Gender (Male for M, Female for F)
9. Added a new column called “County” to NYPD Arrest dataset
10. Updated dataset has 10 columns and 226441 rows

## 📁 Findings:
1. A fluctuating arrest rate on a month to month basis throughout NYC in 2023.
2. The number of men arrested were about five times greater in comparison to
females.
3. 4. Robbery was the highest reason for the age group less than 18 to be arrested.
Brooklyn accounted for 27.50% of the total arrests rate throughout the city.
Whereas, Staten Island had the lowest arrest rate accounting 4.42%.
5. Age groups of 25-44 accounted for the highest rate of arrests among all age
groups.
6. Assault 3rd degree and related oﬀences contributed to highest arrests in all
boroughs except Manhattan where Petit Larceny took the lead.
