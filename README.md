# Power-BI
A full project done on power bi desktop

### Introduction
I noticed that there's no single day without a single accident case, so I dexided to make researches on the factors causing these accidents using the little knowledge I've acquired over time.

### Stakeholder Requiremts / problem statements;
Clients wants to create a Road Accident Dashboard for year 2021 and 2022 so they can have an insight on the requirements below;

. PRIMARY KPI1 -  Total Casualties by Accident Values for current year(2022) and YOY growth.

. PRIMARY KPI2 - Total Casualties by Accident Severity for current yesr(2022) and YOY growth

. SECONDARY KPIs;

Total casualties with respect to vehicle type for current year(2022),

Monthly trend showing comparison of casualties for current year and previous year,

Casualties by road type for current year,

Current year casualties by area / location & by day/night,

Total casualties and Total Accidents by location


### Power BI Concepts applied
. DAX Concepts; Calculated columns, calculated measures.

. Data modelling; star schema(*:1).

. Grouping of some columns.

### Data Cleaning
Noticed that there was a typo error in the "accident severity" column, instead of fatal, a user registered it as fetal. So i had to use the "replace values" option in the power query editor so as to avoid having a wrong category in the column.

### Data Transformation
. A new Date Table was created so as to meet the stakeholder's requirements.
