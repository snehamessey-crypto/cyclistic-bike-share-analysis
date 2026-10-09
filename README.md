# Cyclistic Bike-Share Case Study: Maximising Annual Memberships

## Executive Summary 
This case study evaluates historical trip data from Cyclistic, a fictional bike-share company in Chicago, to identify behavioural differences between casual and annual members. The final recommendations outline a targeted marketing strategy to increase annual membership conversions.

## Business Problem & Core Questions
Cyclistic's finance team established that annual members generate higher profit margins than casual riders. Rather than targeting entirely new customers, Marketing Director Lily Moreno wants to convert existing casual riders into members.
* **Primary Question:** How do annual members and casual riders use Cyclistic bikes differently?

## Tools Used
* **Data Inspection & Cleaning:** Microsoft Excel (Formulas, Conditional Formatting, Outlier filtering)
* **Data Processing & Transformation:** Python(Pandas, NumPy)
* **Interactive Visualization:** Tableau Public

## Key Insights 
1. **Trip Purpose:** Annual members use bikes primarily for commuting, creating sharp usage peaks at 8:00 AM and 5:00 PM on weekdays with consistent durations of 10-12 minutes.
2. **Leisure Patterns:** Casual riders ride primarily on weekdays (peaking Saturday afternoon) with average duration of 25-35+ minutes.
3. **Geographic Concentration:** Casual trips originate heavily from lakefront and park stations, while member trips are distributed across commercial and residential hubs.

## Dashboard Previews
*<img width="1584" height="591" alt="Cyclistic_dashboard_image" src="https://github.com/user-attachments/assets/f671aef9-12b9-4fa6-bd3a-7f819a301fe5" />*
![Cyclistic Dashboard]

**[View Interactive Tableau Public Dashboard](https://public.tableau.com/views/CyclisticExecutivePerformanceDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## Repository Structure
* `data/`: Clean summary metrics and aggregated datasets.
* `python/`: Data cleaning scripts and Jupyter analysis notebooks.
* `tableau/`: Link to the interactive dashboard.
* `docs/`: Project documentation and dashboard visuals.

## Strategic Recommendations
1. **Weekend Member Pass:** Introduce a flexible weekend-tailored membership tier targeting recreational casual riders.
2. **Post-Ride Savings Prompts:** Display in-app cost comparisons to casual riders after trips longer than 30 minutes.
3. **Targeted Station Campaigns:** Focus seasonal digital ads and dockside branding on high-volume recreational stations along the lakefront.
