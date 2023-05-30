# Power-BI - Road Accident Analysis
A full project done on power bi desktop
![](https://github.com/laplacepaul/Power-BI/blob/main/Road%20accident.png)
### Introduction
I noticed that there's no single day without a single accident case, so I dexided to make researches on the factors causing these accidents using the little knowledge I've acquired over time.

### Stakeholder Requiremts / problem statements;
Clients wants to create a Road Accident Dashboard for year 2021 and 2022 so they can have an insight on the requirements below;

**PRIMARY KPIs**
-  Total Casualties by Accident Values for current year(2022) and YOY growth.

- Total Casualties by Accident Severity for current yesr(2022) and YOY growth

**SECONDARY KPIs**

1. Total casualties with respect to vehicle type for current year(2022),

2. Monthly trend showing comparison of casualties for current year and previous year,

3. Casualties by road type for current year,

4. Current year casualties by area / location & by day/night,

5. Total casualties and Total Accidents by location


### Data Cleaning
Noticed that there was a typo error in the "accident severity" column, instead of fatal, a user registered it as fetal. So i had to use the "replace values" option in the power query editor so as to avoid having a wrong category in the column.

### Data Transformation
. A new Date Table was created so as to meet the stakeholder's requirements.

### Measures;
1. Current Year Casualties
2. Current Year Accidents
3. Prev. Year Casualties
4. Prev. Year Accidents
5. YOY Casualties (Current Year Casualties-Prev. Year Casualties)/Prev. Year Casualties
6. YOY Accidents (Current Year Accidents-Prev. Year Accidents)/Prev. Year Accidents

**Data Modelling**

Star Schema(* : 1)


