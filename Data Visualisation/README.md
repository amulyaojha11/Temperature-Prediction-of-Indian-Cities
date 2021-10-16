## Introduction
In this section, we try to visualize our dataset using pyhton libraries: pandas and matplotlib.
We create pivot tables and plot them for better visualisation.

## How to visualize the Data?
- Start with reading the data.
- Set the date column as index, convert it into datetime format using `to_datetime()` function.
- Extract month and year from the date and create seperate columns for each using `index.month()` and `index.year` functions respectively.
- Create pivot table using `pivot_table()` function and assign values to paramters: temperature as value, month as index and year as columns.
- Plot the pivot table, it visualises the trend in monthly temperature over years.
- Take mean across the vertical axis using `mean()` function and assign value to axis paramater as 1 for vertical axis. Plot the seasonality trend.

## Why Pivot table?
Pivot table allows us to reorganize and summarize selected columns of our choice.
If we direcly plot the data present in csv file, we'll get a simple line graph of temperature over years.
Plotting the pivot allows us to recognize the monthly trend over years and compare monthly temperature over years in a single graph.
Also, taking the mean over vertical axis gives us the seasonality trend.