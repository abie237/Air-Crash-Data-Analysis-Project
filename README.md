# Air-Crash-Data-Analysis-Project
Digging into the the data of air crashes form 1908-2023 to find insights and discover trends related to fatalities, routes, AC type and various operators
## Overview
- Project Objective:
     The main aim to this was to discover insights from a given aircrash dataset to discover some patterns and insight related to thier causes and how disastreous they were
- Scope : We had data from crashes ranging from 1908-2023


## Data Documentation, Preparation and Cleaning
 ### Data Cleaning
- The firts step was the analyse what we needed to uncover from the data set as given in the word file problem statement you will find in this resposiotry
- We then identified the columns that will be needed and delete the one which will be use(Deleted the columne time(which represented the time of crash))
- We cleaned  the data using Microsoft Excel, it mainly involved the corrected to mispelled aircrafts names, operator names, city and country name etc§.
 #### Data Preparation
- Once the data was cleaned i added new column which i found will be helpull for the analysis e.g extracting the Year and months from the date column and creatign corresponding columns for this.
- Using the flashfill in excel to easily extract country name which was present in the location column in the form (state,country or city,state,country for some) and will not have been useful for us to use this column as it was, this same method was also used to extract the state.

## Methodology
- Once the analysis complete i proceed direct to importing the excel file into power Bi
- While in power Bi  i already had a brief and concise objective knowing th ekey metrics i will be wanting to represent, the type of viusal charts i will be using to correctly and better show these trends
- So i created the measures i needed using power BI DAX 
-Once all the visual created on the various pages i redo the aesthetic of the design and re-arrange the chart to respect Visual hierachy
- Added the slicers that will be needed to for easy exploration of the data in the data dashboard.


## Dashboard Publishing
- You can find the dashboard online in the Power Bi service [here](https://app.powerbi.com/groups/me/reports/3987d161-22e5-45d6-9a2b-867377766e1e/7ccb0bdd72519511d474?redirectedFromSignup=1&experience=power-bi)

