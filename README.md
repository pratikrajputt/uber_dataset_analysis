# uber_dataset_analysis

This repository contains an analysis of Uber pickup data in New York City from April to September 2014. The analysis is performed using Python and Jupyter Notebook and provides insights into user patterns based on date and time.

Dataset

The dataset includes over 4.5 million Uber pickups and is organized into six files, separated by month. Each file contains the following columns:

	•	Date/Time: The date and time of the Uber pickup.
	•	Lat: The latitude of the Uber pickup.
	•	Lon: The longitude of the Uber pickup.
	•	Base: The TLC base company code affiliated with the Uber pickup.

Note: Revenue or fee per trip information is not available, so the analysis focuses on user patterns.

Analysis Overview

Introduction

This analysis aims to understand user patterns in Uber pickups by examining data over a six-month period. The main focus is on analyzing the patterns by date and time to gain insights into user behavior.

Key Observations

Observation 1: April 2014 Data

	•	Weekday Patterns:
	•	Lowest Counts: Mondays and Sundays have the least number of rides.
	•	Highest Counts: Tuesdays and Wednesdays have the most rides.
	•	Time of Day: Approximately 60% of rides occur between 14:00 - 21:00.
Possible Reasons:
	•	Commuting Patterns: Tuesdays and Wednesdays are busy weekdays with regular commuting, resulting in higher ride counts. Mondays and Sundays have fewer rides due to more flexible schedules or being off work.
	•	Business Travel: Tuesdays and Wednesdays are popular for business travel, contributing to higher ride counts.
	•	Weekend Leisure: Mondays and Sundays may see fewer rides as people engage in leisure activities closer to home.

Observation 2: Peak and Pit Patterns (April - September 2014)

	•	Peak Days:
	•	Thursdays and Fridays: Highest number of rides, indicating increased demand possibly due to higher travel activity or events.
	•	Pit Days:
	•	Sundays: All 33 days with the lowest ride counts were Sundays, showing lower demand for Uber rides.

These observations are consistent throughout the six-month period, suggesting that the patterns are continuous rather than seasonal. Higher commute needs during weekdays lead to increased ride volume, while reduced activities on weekends result in decreased demand.

Observation 3: Heatmap Analysis

	•	Thursdays: Show the highest ride volume throughout the year, with rides extending to suburban areas such as Bridgeport, Clverton, and Bridgewater Township.
	•	Sundays: Rides are concentrated in areas like New Brunswick and downtown.

These heatmaps provide compelling evidence to support the proposal that weekday commute needs are the primary drivers of ride demand, while reduced activity on weekends represents a key pain point.

Repository Contents

	•	uber_data_analysis.ipynb: Jupyter Notebook containing the data analysis.
  •	uber dataset april to september.

Usage

To view the analysis, open the uber_data_analysis.ipynb file in Jupyter Notebook. The notebook includes data preprocessing, visualizations, and detailed analysis of the Uber pickup data.

Conclusion

This analysis provides valuable insights into the user patterns of Uber pickups in NYC. By understanding these patterns, we can better comprehend the factors influencing ride demand and make informed decisions for future transportation planning.
