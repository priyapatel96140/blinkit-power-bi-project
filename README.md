# BlinkIT Grocery Data Analysis

A personal project where I analyzed BlinkIT's sales data to understand what drives grocery sales, how different store types perform, and how product placement impacts the bottom line.

## Brief Summary
An end-to-end data project analyzing over 8,500 grocery rows to find patterns in sales, item types, and customer ratings across different store sizes and locations.

## Overview
I took a raw dataset containing sales figures for various products sold at BlinkIT outlets and turned it into an interactive dashboard. The goal was to look past just the raw profit numbers and see *why* certain stores or items make more money than others. I handled everything from data cleaning (fixing messy text data) to calculating KPIs and building the final visual layout.

## Problem Statement
Fulfillment platforms like BlinkIT move thousands of items daily, but it’s hard to tell what's working without looking at the data. I wanted to answer a few specific business questions:
1. Which item categories bring in the most money, and do people actually care about fat content?
2. How do smaller grocery stores compare to large supermarkets in terms of average customer ratings and total sales?
3. Does making an item highly visible on the platform actually translate to more sales?

## Dataset
The dataset consists of 8,523 rows covering various grocery items and outlet details. Key columns include:
* **Product Details:** Item Identifier, Item Type (Fruits, Snacks, Frozen Foods, etc.), Item Fat Content, Item Visibility, Item Weight, and Customer Rating.
* **Store Details:** Outlet Identifier, Establishment Year, Outlet Size (Small, Medium, High), and Outlet Location Type (Tier 1, Tier 2, Tier 3).
* **Target:** Total Sales.

## Tools & Technologies
* **Data Cleaning:** Microsoft Excel (cleaning up inconsistent labels and handling blanks)
* **Analysis & Visuals:** Power BI / Excel Pivot Tables
* **Version Control:** Git & GitHub

## Method (How I Built This)
1. **Data Cleaning:** The raw data had some inconsistencies. For example, fat content was written as "low fat", "LF", and "Low Fat" randomly—I standardized these into clean categories. I also checked for missing values in item weights and outlet sizes.
2. **Exploratory Analysis:** I ran pivot tables to group the data by product type and outlet type to see where the bulk of the revenue was coming from.
3. **KPI Metrics:** I created measures to track core metrics: Total Sales ($1.20M), Average Sales per item, total item count, and the average customer rating (out of 5).
4. **Dashboard Design:** I designed the layout to be clean and easy to read. I put the big high-level numbers at the top, item-specific trends on the left, and store type/location breakdowns on the right.

## Key Insights
* **Top Earners:** Fruits & Vegetables along with Snack Foods are the undisputed heavy hitters, driving the highest revenue across almost every store.
* **Health Trends:** "Low Fat" products sell significantly more in total volume compared to "Regular" fat options.
* **Store Type Winner:** Supermarket Type 1 is the most efficient and profitable outlet model compared to small standalone grocery stores.
* **Location Surprise:** Tier 3 locations (often smaller towns/suburbs) brought in massive sales numbers, showing that the demand for quick-commerce isn't just tied to Tier 1 metro cities.

## Dashboard Output
Here is a look at the final dashboard:

![BlinkIT Analytics Dashboard](image_b285c2.png)

*Quick stats from the view:*
* Total Revenue: **$1.20M**
* Items Analyzed: **8,523**
* Overall Average Rating: **3.9 out of 5**

## How to Run this Project
1. Download the `.pbix` file
2. Open the file in Power BI Desktop
3. Refresh the dataset if required
4. Interact with filters and visuals
