Project Overview

This repository contains a Power BI project that analyzes and visualizes restaurant data from Zomato. Zomato is a global restaurant search and discovery service. The goal of this project is to create an interactive Power BI report to help Zomato stakeholders analyze restaurant data across continents, countries, and cities.

Business Requirements

Total Restaurants Analysis: Track the number of restaurants across continents, countries, and cities.
Global and Granular Views: Allow views from both global and detailed levels.
Top Restaurants: Identify top performers by customer ratings and cost.
Filters: Filter by geographic dimensions (continent, country, city) and services (online delivery, table booking).
Rating Colors: Use color-coded ratings for restaurants based on their average scores.
Cuisine Analysis: Rank restaurants by the number of cuisines served.
Interactive Reports: Create a multi-page, navigable report accessible on both web and mobile devices.

Files Required

The dataset includes: Africa, Asia, Country-Code, Europe, North America (NAM), South America (SAM), Oceania and Fact Table.

Steps Involved

1. Data Import : Import data from the Excel files into Power BI.

2. Data Transformations : Correct city names (e.g., “Paulo” to “São Paulo”).
Remove unnecessary columns and create separate columns for restaurant name and address.
Create a separate table for cuisines served by each restaurant.
Ensure unique, non-blank values in the Country-Code table.

3. Data Modeling : Build relationships and ensure proper cardinality and cross-filtering for accurate aggregations.

4. Other Data Manipulations : Categorize geographic columns and create a hierarchy for geography dimensions.Group countries by continents.

5. DAX Measures & Calculations : Create a “Rating Color” column based on predefined rating slabs.
Create measures for Restaurant Count, Average Cost, Average Rating, and Cuisine Count.
Add a Continent column to the Country-Code table and map countries to continents.

6. Data Visualization :
   
Card Visuals: Display Average Cost, Average Rating, and Restaurant Count.

Map Visual: Show geography hierarchy and restaurant count.

Infographic Designer: Display top 5 restaurants by average cost and average rating.

Slicers: Allow filtering by rating colors, countries, and cities.

Gauges and Grids: Show the selected restaurant’s average rating, average cost, address, and cuisines.
