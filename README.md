# Cyclistic Bike-Share Analytics: Maximizing Annual Memberships

[![Tools](https://img.shields.io/badge/Tools-Excel%20%7C%20Python%20%7C%20Power%20BI%20%7C%20Tableau-blue)](#tech-stack--workflow)
[![Case Study](https://img.shields.io/badge/Google%20Analytics-Capstone-orange)](#business-context--core-problem)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Executive Summary
This case study evaluates historical trip data from Cyclistic, a bike-share program in Chicago, to identify behavioral divergence between casual riders and annual members. The resulting analysis guides a targeted conversion strategy designed to turn high-margin recreational casual riders into long-term annual subscribers.

### Key Performance Indicators
* **Commuter Utilization:** Annual members display double daily commute peaks at **8:00 AM** and **5:00 PM** on weekdays.
* **Trip Duration Disparity:** Casual riders average ride durations of **25–35+ minutes**, over 2x the consistent **10–12 minute** rides of members.
* **Weekend Leisure Dominance:** Casual rider volume peaks heavily on Saturdays and Sundays, concentrated around lakefront recreation zones.

---

## Business Context & Core Problem
Cyclistic's financial analysis determined that annual members generate significantly higher profit margins than casual riders purchasing single-ride or day passes. Marketing leadership seeks to drive growth by converting existing casual riders rather than acquiring cold leads.

* **Primary Business Questions:**
  1. How do annual members and casual riders use Cyclistic bikes differently?
  2. Why would casual riders be incentivized to buy an annual membership?
  3. How can digital marketing channels influence casual riders to transition?

---

## Tech Stack & Workflow
* **Microsoft Excel:** Legacy function testing, timestamp parsing, trip duration calculation, and preliminary spot audits.
* **Python (Pandas, NumPy):** Large-scale data transformation, filtering out negative/test trip durations, datetime parsing, and geospatial station aggregation.
* **Power BI & Tableau:** Interactive route mapping, hourly usage distributions, and rider segment comparison views.

---

## Key Analytical Insights
* **Trip Purpose Disparity:** Annual members utilize bikes primarily for utility and office commuting (sharp weekday peaks at 8 AM and 5 PM), whereas casual riders display weekend afternoon leisure usage.
* **Ride Duration Patterns:** Casual trips run 2–3x longer than member trips, indicating recreation, tourism, and casual exercise rather than point-to-point transit.
* **Station Geographic Clustering:** Casual trips originate heavily along waterfront stations (lakefront, Navy Pier, city parks), while member activity remains distributed across central business hubs and transit links.

---

## Strategic Recommendations
1. **Weekend Bridge Pass:** Introduce a flexible or seasonal membership tailored for weekend leisure riders, with pass credits that can be rolled over into full annual memberships.
2. **Post-Ride Savings Prompts:** Display in-app savings summaries to casual riders following trips longer than 30 minutes, highlighting how much money an annual membership saves per ride.
3. **Targeted Station Campaigns:** Concentrate seasonal digital ad spend, geo-targeted mobile pushes, and dockside physical branding at high-traffic recreational and lakefront stations.

---

## Repository Structure
```text
├── data/
│   └── cyclistic_cleaned_trip.xls                     # Preprocessed trip data
├── python/
│   └── cyclistic_trips.ipynb                          # Data cleaning, wrangling, and duration anomaly filtering
├── dashboards/
│   └── cyclistic_executive_performance_dashboard.twbx # Tableau packaged workbook file
├── docs/
│   └── cyclistic_dashboard.png                        # High-resolution dashboard screenshot
└── README.md
