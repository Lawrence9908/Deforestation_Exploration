# ForestQuery Data Analysis Project

## Introduction

Welcome to the ForestQuery Data Analysis Project! ForestQuery is a non-profit organization with a mission to reduce deforestation globally and raise awareness about this crucial environmental issue. As a data analyst, you have been tasked with understanding countries and regions that have experienced shrinking forests and identifying areas with significant forest coverage.

## Project Overview

My goal was to create a comprehensive report for the ForestQuery executive team, using SQL queries to analyze forestation data between 1990 and 2016. I was working with three tables: `forest_area`, `land_area`, and `regions`. These tables were joined to create a view called "forestation," which will provide insights into the forestation situation over time.

### Steps Completed

1. Create a View called "forestation" by joining all three tables: `forest_area`, `land_area`, and `regions`.
2. In the "forestation" View, include all columns from the original tables and a new column representing the percent of land area designated as forest.
3. Analyze the data to answer specific questions related to the global situation, regional outlook, and country-level detail.

## Part 1 - Global Situation

### 1. GLOBAL SITUATION

In this section, I answer essential questions to understand the global deforestation overview between 1990 and 2016.

a. What was the total forest area (in sq km) of the world in 1990? Please note that you can use the country record denoted as "World" in the region table.

b. What was the total forest area (in sq km) of the world in 2016? Please keep in mind that you can use the country record in the table denoted as "World."

c. What was the change (in sq km) in the forest area of the world from 1990 to 2016?

d. What was the percent change in forest area of the world between 1990 and 2016?

e. If you compare the amount of forest area lost between 1990 and 2016, to which country's total area in 2016 is it closest to?

## Part 2 - Regional Outlook

### 2. REGIONAL OUTLOOK

In this section, I focus on regional data and analyze the forest area percentage changes between 1990 and 2016.

Create a table that shows the Regions and their percent forest area (sum of forest area divided by sum of land area) in 1990 and 2016. (Note that 1 sq mi = 2.59 sq km).

Based on the table you created, answer the following:

a. What was the percent forest of the entire world in 2016? Which region had the HIGHEST percent forest in 2016, and which had the LOWEST, to 2 decimal places?

b. What was the percent forest of the entire world in 1990? Which region had the HIGHEST percent forest in 1990, and which had the LOWEST, to 2 decimal places?

c. Based on the table you created, which regions of the world DECREASED in forest area from 1990 to 2016?

## Part 3 - Country-Level Detail

### 3. COUNTRY-LEVEL DETAIL

In this section, I examine the forest area changes at the country level and categorize countries based on their forestation percentage.

a. Which 5 countries saw the largest amount decrease in forest area from 1990 to 2016? What was the difference in forest area for each?

b. Which 5 countries saw the largest percent decrease in forest area from 1990 to 2016? What was the percent change to 2 decimal places for each?

c. If countries were grouped by percent forestation in quartiles, which group had the most countries in it in 2016?

d. List all of the countries that were in the 4th quartile (percent forest > 75%) in 2016.

e. How many countries had a percent forestation higher than the United States in 2016?

## Conclusion

This report aims to provide a comprehensive overview of global deforestation between 1990 and 2016. By analyzing the data, we hope to assist ForestQuery in making informed decisions and allocating resources effectively to achieve their mission of reducing deforestation worldwide.
