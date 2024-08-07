# Crime Data Analysis

This repository contains a Python script for analyzing crime data from a CSV file. The script performs various tasks including data cleaning, extraction of key insights, and classification of crime data based on time and victim age groups.

## Requirements

- Python 3.x
- Pandas

You can install the required package using pip:

```bash
pip install pandas
```

## Data

The script uses a dataset named `crime.csv`. Ensure this file is located in the same directory as the script.

## Analysis Overview

1. ### Data Preparation
   - Loads the crime data from the CSV file.
   - Removes unnamed columns and processes the date and time columns.
   - Extracts the hour from the time column for further analysis.

2. ### Insights

   - Peak Crime Hour
     - Identifies and prints the hour of the day with the highest frequency of crimes.

   - Night Crime Analysis
     - Determines and prints the area with the highest frequency of night crimes (from 10 PM to 4 AM).

   - Victim Age Groups
     - Categorizes victims into age groups and prints the number of crimes committed against each age group.



Feel free to modify the README to fit any specific requirements or additional details you may have!
