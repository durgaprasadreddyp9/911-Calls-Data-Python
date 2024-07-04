Analysis Steps

Import Libraries: Import numpy, pandas, matplotlib, and seaborn.

Load Data: Read the CSV file into a pandas DataFrame.

Data Overview: Check the DataFrame info and preview the first few rows.

Basic Questions:
Top 5 zip codes for 911 calls.
Top 5 townships for 911 calls.
Number of unique title codes.

Create New Features:
Extract the reason for the call from the title.
Convert timeStamp to DateTime objects and extract Hour, Month, and Day of Week.

Data Visualization:
Countplot of 911 calls by Reason.
Countplot of Day of Week with hue based on Reason.
Countplot of Month with hue based on Reason.

Further Analysis:
Group data by Month and plot the count of calls per month.
Create a linear fit on the number of calls per month.
Plot the counts of 911 calls by date.
Separate plots for each Reason.

Heatmaps and Clustermaps:
Restructure the DataFrame for heatmaps and clustermaps.
Create heatmaps and clustermaps for Day of Week vs Hour and Day of Week vs Month.

This work underscores the importance of data-driven decision-making in enhancing public safety and emergency response.

