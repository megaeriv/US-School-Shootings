# Introduction 

This is an Exploratory Data Analysis for School shootings in the US from 2000 to 2021

As defined by the Congressional Research Service, mass shootings are multiple firearm-related homicides involving at least four victims at one or more nearby locations. Foreign terrorists are not included.

Every day in America, 12 children die and 32 are injured because of gun violence, according to the Sandy Hook foundation. A foundation formed after the deadly shooting at Sandy Hook Elementary School in 2012. 

Throughout the last few decades, gun violence has been growing in the United States. This has caused a lot of protests and foundations to spring up. As a data analyst enthusiast, I examined one of many datasets regarding gun violence for insight.

# Content

1. Aim

2. Data Sourcing

3. Data Cleaning

4. Exploratory Data Analysis

5. Data Visualization

6. Conclusion

# Aim

This project aims to get valuable and meaningful insight into school shootings over the years.


# Resources

Datasets were downloaded from Kaggle. In these datasets, locations, times, reasons, and casualties of school shootings are recorded.

Details relating to the different school years recorded, 21 school years in total.

Datasets include:

- **Casualties from shootings**

  School year : Year of shooting,

  Total: Total number of casualties including injuries and deaths,

  Deaths: number of persons killed in shootings,

  Injuries: number of persons injured in shootings


- **Number of school shootings, by type of casualty**

  School year : Year of shooting,

  Total: Total number of Shootings per year,

  Number with Deaths: Shootings that had at least 1 death,

  Number with Injuries: Shootings that had at least 1 injured person only,

  Number with no casualties: Shootings with no injuries or deaths,


- **School shooting-by location**

  School year : Year of shooting,

  Locations of shootings (e.g Classroom),

  Period of shootings (e.g Morning class),


- **School shooting-situation associated**

  School year : Year of shooting,

  Grade of school in shootings


- **Shootings by level(grade) of school**

  School year : Year of shooting,

  Situation associated: reason for shooting

**Packages used for Analysis:
ggpubr, tidyverse, here, skimr, janitor, lubridate, ggrepel, readxl, ggplot2, treemapify* 

# Data Cleaning
After downloading the data from Kaggle, I needed to clean the data to perform an Exploratory data analysis. First, I checked for missing and duplicated data with Excel. I also separated and renamed columns. 



# Exploratory Data Analysis

I looked at the distribution of the data and created data frames to get an insight into the data and visualize

Analysis:

1. Shooting trend

2. School shootings by grade

3. Vulnerable Times of Shootings

4. Vulnerable places of attack

5. Reasons for shootings


# Data Visualization

In addition to exploring the data, I visualized it in R studio using R, as well as in Power BI. Here is the full project you can check out [US School Shooting Analysis](https://github.com/megaeriv/US-School-Shootings/blob/main/US-School-Shootings.md)

Power BI
![Power BI First Page](https://user-images.githubusercontent.com/111463558/195843790-0f3ddd38-6fed-44b3-9a3a-90db67cec6da.png)
![Power BI Second Page](https://user-images.githubusercontent.com/111463558/195843811-94240766-3078-4972-893e-17b2cca78131.png)


R studio:
![Screenshot 2022-10-14 131018](https://user-images.githubusercontent.com/111463558/195843826-8c5107be-bd99-4437-ad02-272a66ec080a.png)


# Insight
 
 - The steady increase in Shooting frequency from 2011/12 to 2020/21, just after a steady low rate of school shootings for 3 school years.
School years 2009/10, 2010/11, and 2011/12 had the lowest numbers of school shootings in the dataset, but this period is then followed by an ever-increasing frequency of school shootings till the present.

- 2017 to 2021 has seen a rise in the number of school shootings and has been on the rise since which has also led to an increase in casualties.
The 2012/13 school year is an anomaly as it's the only year where the number of deaths recorded surpassed the number of persons injured and the number of total shootings. 

  With an increase in school shootings in the past years, it can be stated that the US is not closer to solving its gun crisis as more shootings and protests against gun laws occur more frequently.

  The increase in shootings after this period can be attributed to the District of Columbia v. Heller 2008 hearing where the Supreme court reinterpreted the 2nd Amendment from the long-time state right to maintain militia to an individual right to own guns,
  This caused an increase in gun ownership in the US and the eventual increase in annual gun deaths.

  This however conflicts with the low number of shootings for 3 years just after the Heller hearing. With further research, I discovered a report by senior data journalist Daniel Dunford reporting that from 2008 to 2012, there were over 200,000 more background checks for gun sales than the previous years.

- From observations, most shootings in the dataset occur in High schools with the second most shootings occurring in elementary schools.

  High School average age: 17-18
  Elementary school average age: 5-11

  High Schools recording the most shootings correlates with escalation of dispute being the topmost reason for school shootings as students of this age are more likely to handle weapons. 

- Analysis shows the majority of school shootings occur during non-teaching hours, like classes as the shooter would most likely seek to inflict the most damage to people. Outside school hours, after/before school sporting events are times when there are groups around chatting and playing which makes it the most vulnerable time for mass shootings.

- From the insight gotten revealing the most vulnerable time of school shooting is outside school hours, it is no surprise that the most vulnerable place of attack is outside school buildings on the school's property. This data however could be misleading as it does not specifically tell if this is where the shootings started, ended, or recorded the most casualties.


