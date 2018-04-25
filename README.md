# EDAV_Project
Project for the EDAV course in Spring 2018, Columbia

(The same procedure is used in the Jupyter notebook and its pdf file- check for headings)

## Procedure

### 1. Get collisions data from the NYC open data website:
      Data: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95
      Description: https://data.cityofnewyork.us/api/views/h9gi-nx95/files/b5fd8e71-ca48-4e96-bf63-1b8a7c4cc47b?download=true&filename=Collision_DataDictionary.xlsx
      
### 2. Get weather data for NYC(JFK Airport) from the NOAA website
    Data: https://www1.ncdc.noaa.gov/pub/data (need to request with selections)
    Data Dictionary: https://www1.ncdc.noaa.gov/pub/data/cdo/documentation/GHCND_documentation.pdf

### 3. Data Sanity Check

#### a) Do Missing Value Analysis
#### b) Check Prominent statistics
#### c) Check for Outliers, data inconsistencies
#### d) Derive frequeutly used fields: Hour of day, Day of week, Weekend flag, Fog flag, Rain flag
#### e) Check value counts for categorical data and check for inconsistencies(like "unspecified" in Factor for accident)

### 4. Exploratory Data Analysis

#### a) Brainstorm and generate hypothesis around the target feature (or feature of importance) - here, the number of accidents, number of injuries and the number of deaths caused by accidents in NYC
#### b) Verify the veracity of Hypotheses(Effect of weather, Effect of Alcohol, Cause of severe accidents etc.)
#### a) Conclude
