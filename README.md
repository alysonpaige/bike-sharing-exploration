# GoBike Data Analysis

## Introduction
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

Questions that are explored in this dataset are:
* What is the demographic of GoBikes userbase?
* What is the most popular station to pick up and/or return a bike?
* How long does the average trip take by gender?
* When are most trips taken in terms of time of day and day of the week?
* Does the above depend on if a user is a subscriber or customer?

## Libraries
* pandas
* NumPy
* seaborn
* Matplotlib
* csv

## Getting Started

### Data Wrangling 
GoBike data was gathered from a csv and an initial assessment of quality and tidiness was conducted. There were several issues identified with this dataset that were to be addressed during the cleaning phase. There were null values, datatype discrepancies, and other extraneous information that is not needed for this analysis. The main features of interest in this dataset were times, and user and station information.

### Exploratory Data Analysis
* Males account for the majority of GoBike's total users. 74.6% of GoBike users are male. 23.3% of users are female. The remaining 2.1% are not identified. Over half of the users, 65.2% are ages 18-35
* The most popular station users begin GoBike trips is at "Market St. at 10th St." with over 2% of users starting their trips at this station
* On average, women take longer trips than men by just more than 2 minutes. The average trip duration for women is just over 12 minutes. The average trip duration for men is just over 10 minutes
* The average duration of a customer trip is 21 minutes. This is higher than the subscriber average of 10 minutes.

### Explanatory Data Analysis

* GoBike users start trips most frequently at 8am and 5pm. Based on this data we can surmise most GoBike users are commuting to/from work
* The most common day of the week for GoBike users to take a trip was Thursday. This confirms the conclusion that the bikes are predominately used during the week for commuting
* We can see the trip duration for the older age group of 56-75 has the largest gap in time. Their trips are either very short or very long

### Conclusions
The insights gathered from the analysis present some opportunities for GoBike to capitalize on:
* Men are the majority of GoBike users so more resources can be allocated towards male subscribers or upselling male customers to become subscribers
* Ensure there is enough supply of GoBikes during peak times of 8AM and 5PM. Consider a small surcharge during these times or when supply is low
* Consider targeting the youngest age group of 18-35 "other" users who seem to take the longest trips. This could involve finding out what stations they start and end their trips at most frequently
* Remove "other" and include additional gender options to allow for more finite analysis in the future