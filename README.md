# Zomato Restaurant Analysis - PowerBI

Developed an interactive Power BI dashboard for Zomato restaurant analysis to uncover trends in ratings, cuisines, and countrywise restaurant. Imported and transformed large datasets using Power Query, created DAX measures for key metrics, and designed visually compelling charts and maps. Implemented slicers for dynamic filtering and drill-through functionality for in-depth insights. Presented findings on popular cuisines, cost-effectiveness, and location-based performance to aid business decision-making.



## Problem Statement

 The goal is to uncover trends in ratings, cuisines, and countrwise outlets, Table booking, online delivery details. Imported and transformed large datasets using Power Query, created DAX measures for key metrics, and designed visually compelling charts and maps.

Key Objectives:
1. Perform data cleaning and preprocessing on raw data.
2. Conduct Exploratory Data Analysis (EDA) to identify trends, patterns, and outliers.
3. Create a dashboard which analyze  ratings, cuisines, and countrwise outlets, Table booking, online delivery details.



### Steps followed 

- Step 1 : Get data set from https://colorstech.net/data-analytics/indian-restaurants-sample-dataset-for-educational-data-analysis/
- Step 2 : Load data into Power BI Desktop, dataset is a excel file.
- Step 3 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 4 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 5 : It was observed that in none of the columns errors & empty values.
- Step6 : Change the datatype of datekey_opening column to date field.
- Step7 : Close and apply.
- Step 8 : In report view, created 6 cards, "No.of restaurant","No.of countries" ,"No.of cities", "No.of cuisines","Votes" and "Ratings".
- Step 9 :Added a clustered bar chart for countrywise restaurants.
- Step 10 : Added a line and stalked column chart for cuisines and its avg ratings by restaurants. 
- Step 11 : Added a clustered bar chart for cuisines in restaurants.
- Step 12 : Added Donut chart for "Table Booking".
- Step 13 : Added Donut chart for "Online Delivery".
- Step 14 : Added two slicers for countries and year. 

 
    
 
 # Report Snapshot (Power BI DESKTOP)

 
![Image](https://github.com/user-attachments/assets/6051f3e7-d5cd-4dcb-af8a-f683809ff11f)
