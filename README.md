# CRM Sales Dashboard

## The Situation
You work as a Sales Manager for Maven Tech, a company that specializes in selling computer hardware to large businesses.

## The Assignment
They've just started using a new CRM system to trak their sales opportunities but have no visibility of the data outside of the platform.

## The Objectives
1. Prepare the data for analysis
2. Explore the data with pivot tables
3. Build a dynamic dashboard

## The Data Set

#### CRM Sales Opportunities
B2B sales pipeline data from a fictitious company that sells computer hardware, including information on accounts, products, sales teams, and sales opportunities.

#### Recommended Analysis
1. How is each sales team performing compared to the rest?
2. Are any sales agents lagging behind?
3. Can you identify any quarter-over-quarter trends?
4. Do any products have better win rates?

#### Objective 1: Prepare the data for analysis
Your first objective is to explore the sales pipeline dataset, conduct some basic data QA and profiling, and join it with the sales team table to prepare the data for analysis.

* Open the "sales_pipeline.csv" file
* Take a moment to familiarize yourself with the data. How many opportunities have been won, over what period of time? What products were sold? Are there any missing values?
* Open the "sales_teams.csv" file in a new tab
* Bring in the "manager" and "regional_office" for each "sales_agent" in the sales pipeline table

#### Objective 2: Explore the data with pivot tables
Your second objective is to slice and dice the sales pipeline data with pivot tables, and create views to analyze quarterly trends and sales agent performance.

* Insert a pivot table on a new tab to show opportunities won by quarter
* Add another pivot table (on the same sheet) to break down the percentage of won & lost opportunities by quarter
* Create a final pivot table that shows the opportunities won by quarter for each sales agent, and sort the sales agents in descending order by opportunities won
* Restructure the first two pivot tables so they have the quarters as pivot table columns (not rows), and sort them so the most recent quarter always comes first

#### Objective 3: Build a dynamic dashboard
Your final objective is to visualize the data with charts and add filters to design an interactive dashboard for sales agents to track quarterly performance.

* Insert a "Scorecard chart" visual to show the opportunities won for the most recent quarter (2017-Q4) compared to the previous one (2017-Q3)
* Visualize the percentage of deals won and lost in the most recent quarter using a pie chart
* Use a bar chart to visualize the opportunities won by sales agent for the most recent quarter
* Add slicers for the "regional_office" and "manager" fields
* Finish things off by arranging the visuals into a dashboard and adding a title

#### [Project Link](https://docs.google.com/spreadsheets/d/1n0ibb1jw2HE5kkzo9yOFhHKS-gk1dK9vUvair3X_Iec/edit?gid=589242039#gid=589242039)