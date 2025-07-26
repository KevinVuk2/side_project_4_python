![LA_Skyline](la_skyline.jpg)
# Los Angeles Crime Data Analysis

This project performs an exploratory data analysis on a dataset of crimes in Los Angeles. The analysis aims to uncover key patterns in crime incidents, focusing on the time of day, location, and victim demographics.

# Analysis Overview

The notebook uses pandas, numpy, matplotlib, and seaborn to manipulate and analyze the crimes.csv dataset to answer three main questions:


1. What is the peak hour for crimes in Los Angeles?
The analysis extracts the hour from the TIME OCC column for each crime incident. A count plot is then generated to visualize the frequency of crimes for each hour of the day, identifying the time when crimes are most commonly reported.


2. Which area has the most crimes during the night?
To understand crime distribution at night, the data is filtered for incidents occurring between 10 PM and 3 AM. The notebook then visualizes the number of crimes per AREA NAME to pinpoint the location with the highest frequency of night-time crime.


3. Which age group is most frequently targeted?
Victim ages are categorized into distinct groups (e.g., 0-17, 18-25). The analysis then counts the number of victims in each age bracket to determine which demographic is most often affected by crime in the city.


# Technologies Used

Python (pandas, numpy, matplotlib, seaborn)
