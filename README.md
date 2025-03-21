# 🚶‍♀️ Pedestrian and Weather Analysis in Dublin (2023)

**Author:** Beyza Kordan  
**Program:** MSc in Economics and Data Analytics, University College Dublin  
**Date:** 15 December 2024

---

## 📘 Project Overview

This project explores the relationship between hourly pedestrian footfall and weather conditions in Dublin for the year 2023. Using two datasets—pedestrian counts from Smart Dublin and weather observations from Met Éireann—the analysis investigates seasonal trends, holiday effects, and daily patterns in pedestrian traffic.

---

## 🧠 Key Methods Applied

**Data Cleaning & Merging**  
Removal of irrelevant columns and formatting timestamps  
Joining two datasets on shared datetime field  
Handling and transforming variables (e.g., ordered factors for days and months)

**Time-Based Feature Engineering**  
Extracted weekday and month for grouping  
Created new features like total daily footfall

**Descriptive and Comparative Analysis**  
Monthly footfall summaries  
Holiday traffic exploration (e.g., St. Patrick’s Day, Christmas)

**Weather Trend Summarization**  
Seasonal weather statistics including temperature, wind, and precipitation

**Visualization**  
Time series plots, bar charts, and annotated scatter plots  
Insights into how day-of-week and seasonal conditions influence footfall

---

## 📊 Highlights

**Time Mismatch Discovered**  
Only 12 rows shared the exact same timestamps between the two datasets, prompting careful alignment before merging.

**Peak Pedestrian Months**  
April recorded the highest traffic; January had the lowest.

**Weekday Patterns**  
  Wednesday and Thursday had the highest average footfall, while Sunday was the quietest.

**Holiday Effects**  
No dramatic spikes observed on St. Patrick’s Day or Christmas.

**Seasonal Weather Trends**  
Summer showed the highest temperatures; Autumn had the strongest winds.

---

## 🔧 Technologies Used

R  
`dplyr`, `lubridate`, `ggplot2`, `tidyr`, `skimr`

---

## 📎 Notes

This project was developed for academic coursework and showcases practical time series handling, data merging, and exploratory analysis in R.  
All data transformations, plots, and interpretations were prepared independently by me.

---
