This is my Readme file
The project contains different files:
1. Data files
    i. AviationData.csv: contains aviation dataset
    ii. USState_Codes.csv: contains US Codes for different states
    iii. clean_aircraft.csv: contains cleeanded data
2. Readme file:
    iv. README.md
3. A Jupyter Notebook file
    v. index.ipynb

## Overview

The project seeks to explore data on different aircrafts accidents in order to advise company stakeholders on which type of aircraft to choose for business as they would like to join this industry. 

## Business Understanding
The company is seeking to start a new business endeavor, operating aircrafts for commercial and private enterprises, in which they are novice to it. The stakeholders are seeking to understand what type of aircrafts have low risk to accidents from prevoius occurences. 

The dataset has various incidents since 1962. The information on the database is on continual update once an incident happens. Using this data would help identify the patterns/trends on these occurences. 


## Include stakeholder and key business questions

At the end of the data analysis, getting aircraft types which are low-risk we need to answer questions such as: 
    
    what factors should we consider for low risk. This may include looking at the number of injuries, level of damage, etc.

    What make have minimal or no accidents, which models specifically?
    
    what level of damage did they acquire during those incidences?
    
 This would aid in making decisions on which type of aircrafts to purchase.

## Data Understanding and Analysis
The processes involved include:
- Data understanding by checking the data types, number of records by methods such as, info(), head(), tail(), describe()

- We start by checking the essential columns and dropping the unnecessary ones.

- The company needs 'Airplane'. If you check the AircraftCategory, there are aircraft of the Airplane Category. So we will create a dataset of that category.

- To determine the low risk aircraft, it needs specific kind of data such as the model, make, category, engine type, level of damage, number of injuries, etc.
Columns such as Event Id, Investigation Type, Accident Number, etc. may not be useful. So we will drop these columns

- The data may be having spaces at the edges, we will strip the empty spaces in case the are present.

- Rename the columns to be easy handling by removing dots on column names 

- Check null values and see how to handle them, drop, replace by mode , mean or median.

## Source of data
The was obtained from Kaggle: (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses), from the National Transportation Safety Board that includes aviation accident data and selected incidents covering United States, its territories and international waters from 1962

## Description of data
From the above data, we can see aviation dataset has 88,889 rows with 35 columns. It gives info on aircraft type, location, country where the incident occured, information about the aircraft, dates, etc.

There are missing data from the null values seen in the data. The dataset has numbers on injuries - fatal, seroius or minor ones, and number of engines of the aircraft.

## Three visualizations (the same visualizations presented in the slides and notebook)
Visualization was done mostly on tableau - creating a story from different sheets and dashboards

## Conclusion
Recondatoins are done in te jupyter file, index.ipynb and the presentation.pdf

## Summary of conclusions including three relevant findings
1. We would recomend the top 3 showing more safety in terms of non-Fatal accidents and Level of Damage. i.e.: Cessna, Piper and Beech Make.

2. The model that has low-risk are the 172 models (of Cessna), with the most non-fatal injuries. This is followed by Piper and Beech.
Cessna has the highest number of model count for non-fatal injuries. Thus showing more safety.
3. More research to be done based on other factors before making a decision on the chose of Airplane.
