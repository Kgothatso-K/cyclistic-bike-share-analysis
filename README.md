# Cyclistic Bike-Share Analysis

## Project Overview

This project analyses behavioural differences between casual riders and annual members in a bike-share system to identify data-driven strategies for increasing membership conversion.

The analysis is built as a **reproducible end-to-end pipeline** using Quarto, combining R and SQL to transform raw trip data into actionable business insights.

---

## Business Problem

Cyclistic aims to increase the number of annual members, as they provide more consistent and profitable revenue compared to casual riders.

The key question is:

> **How do casual riders and members behave differently, and how can those differences be used to drive membership conversion?**

---

## Dataset

- 12 months of trip data  
- ~5.6 million ride records  
- 14 variables including ride duration, timestamps, bike type, and station data  

The dataset was cleaned, validated, and transformed into an analysis-ready format before exploration.

---

## Key Insights

- **Casual riders take longer trips**  
  → Indicates leisure-oriented usage  

- **Casual riders are weekend-focused**  
  → Peak activity on Saturdays and Sundays  

- **Members ride more consistently during weekdays**  
  → Reflects commuting and routine usage  

- **Casual demand is highly seasonal**  
  → Strong peaks during spring and summer  

- **Members generate more trips overall**  
  → Indicates higher frequency and dependency on the service  

---

## Recommendations

- Target casual riders during **peak usage periods (weekends & summer)**  
- Position membership as **cost-effective for frequent riders**  
- Encourage transition from **occasional to habitual usage**  
- Focus campaigns on **high-traffic casual rider locations**  
- Align messaging with **distinct behavioural patterns**  

---

## Tools & Technologies

- **R (tidyverse, ggplot2)** — data cleaning, analysis, visualisation  
- **SQL (SQLite)** — validation and aggregation  
- **Quarto (.qmd)** — reproducible reporting  

---

## How to Run

1. Clone the repository  
2. Open the `.qmd` file in RStudio  
3. Install required packages  
4. Render the file to generate the HTML report  

---

## Key Outcome

This project demonstrates the ability to:

- Clean and structure large datasets (5M+ records)  
- Perform behavioural segmentation analysis  
- Build clear, decision-oriented visualisations  
- Translate data into actionable business recommendations  
- Develop a reproducible analytics workflow  

---

## Full Analysis

See the complete analysis and report in:

`cyclistic_analysis.qmd`  

(Render to HTML for best viewing experience)

---

## Data Source

The dataset used in this analysis is publicly available from the Cyclistic (Divvy) bike-share system. Due to file size constraints, raw data is not included in this repository.

You can download the dataset here: https://divvy-tripdata.s3.amazonaws.com/index.html
