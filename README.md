# Bellabeat_Case-study-Smart-device-analysis-using-Fitbit-Data

Defining Business Task

**Business Task**

How consumers are using their smart devices.

**Deliverables**

A report with the following deliverables:

1.A clear summary of the business task

2.A description of all data sources used

3.Documentation of any cleaning or manipulation of data

4.A summary of analysis

5.Supporting visualizations and key findings

6.Top high-level content recommendations based on your analysis

**Stake Holders:**

Primary

Urška Sršen: Bellabeat’s co-founder and Chief Creative Officer

Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

Secondary

Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy. You joined this team six months ago and have been busy learning about Bellabeat’’s mission and business goals — as well as how you, as a junior data analyst, can help Bellabeat achieve them


# **Data-set Integrity Check and Cleaning Preparation**

**Tools Used**

DB Browser for SQLite (SQL) - For exploring, processing and cleaning of data (Some of the files contained rows more than Excel can handle)

Tableau - Analysis and visualization

 **Data & Source Integrity**

 **Reliability**

 Data used for this project is from a fitness tracking device under brand Fitbit open/public data which can be found in this link. The data is about fitness data from 30 individuals wearing Fitbit fitness tracker. Since there is no information regarding participants' age, sex and profession, accuracy and unbiased stand can not be vetted.

**Originality**

Data set contains 30 user fitness tracking data down to the minute. This data was collected by Amazon Mechanical Turk between 03.12.2016 - 05.12.2016. This data has been preprocessed and uploaded by Kaggle user Mobius. Data set is under Creative Commons license which claims no copyright of the data and allows copy, modification and performing work, even for commercial purposes, all without asking permission. Details of the license can be found [here](https://creativecommons.org/publicdomain/zero/1.0/)

Since data has been collected from third party and was preprocessed as well, originality can not be vetted as well.

**Comprehensiveness**

30 eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. However, there are some discrepancies in the data set:

* There is no information about the age, sex, height and profession of the personnel providing fitness logs. This makes identifying pattern of activity of individual

* dailyActivities_merged.csv contains distance data but there is no information regarding distance measuring unit.

* There are inconsistencies in logged data. Not all participants have full 30 days of data. Moreover, Since this data spreads for both May and April months, there are participants with 31 days of data. This makes the time-frame for data analysis inconsistent.

* Some of the data contains 1440 mins of Sedentary minutes which is equivalent to hour. This indicates not wearing the tracker throughout the day.

* There are no information regarding what intensity is and how to measure and unit of intensity in the hourlyIntensities_merged.csv

**Data Collection Period**

This data was collected by Amazon Mechanical Turk between 03.12.2016 - 05.12.2016. This indicates that data is quite outdated. This decreases usability of the data.

**Data-set Observations**

* The Fitbit data set contains 18 files containing different tracking data. These are:

- dailyActivity_merged.csv

- dailyCalories_merged.csv

- dailyIntensities_merged.csv

- dailySteps_merged.csv

- heartrate_seconds_merged.csv
  
- hourlyCalories_merged.csv

- hourlyIntensities_merged.csv

- hourlySteps_merged.csv
  
- minuteCaloriesNarrow_merged.csv
  
- minuteCaloriesWide_merged.csv
  
- minuteIntensitiesNarrow_merged.csv
  
- minuteIntensitiesWide_merged.csv

- minuteMETsNarrow_merged.csv

- minuteSleep_merged.csv

- minuteStepsNarrow_merged.csv

- minuteStepsWide_merged.csv

- sleepDay_merged.csv

- weightLogInfo_merged.csv

- dailyActivity_merged.csv contains all the column data from dailyCalories.csv, dailyIntensities.csv, dailySteps.csv.

- Some of the data are in both long and wide format. These are calorie, heart rate and steps data.

- heartrate_seconds_merged.csv contains heart rate of an individual for 24 hrs at 15 seconds interval.

## Cleaning and Processing Data

The data set has been marked as pre-processed. There is less chance of blanks or dirty data. However, in order to clean obtained data following cleaning activities have been performed:


