# covid19-powerbi-dashboard
Interactive Power BI dashboard analyzing global and country-level COVID-19 trends using time-series data, KPIs, and visual insights.

# COVID-19 Power BI Dashboard Analysis

## Project Overview

This project presents an interactive Power BI dashboard to analyze the global impact of COVID-19 using real-world time-series data.  
The report includes KPIs, trend analysis, country-level exploration, and comparative visualizations to understand the spread and severity of the pandemic.

## Dataset Used

The analysis is primarily based on the **covid_19_clean_complete** dataset, which contains:

- Date-wise global COVID-19 records  
- Country/Region information  
- Confirmed, Deaths, and Recovered case counts  

## Data Preprocessing

The following preprocessing steps were performed in Power BI:
- Loaded CSV datasets into Power BI  
- Checked data types for Date and numeric columns  
- Removed null or inconsistent values  
- Ensured consistent country naming  
- Created aggregated measures for KPIs (Confirmed, Deaths, Recovered)

## Dashboard Pages

### 1. Overview Page
Provides a global summary of COVID-19:
- Total Confirmed, Deaths, Recovered, and Active cases (KPIs)  
- Time-series trend of confirmed cases  
- Country-wise comparison of confirmed cases  
- Clean layout with consistent formatting and imagery

### 2. Country Analysis Page
Enables interactive country-level exploration:
- Country selector (slicer)  
- Dynamic KPIs based on selected country  
- Line chart showing confirmed case trend over time
-  Detailed table displaying:
     -Country/Region
     -Confirmed
     -Recovered
     -Deaths
- Navigation buttons for smooth page transition

## Key Insights

- COVID-19 cases increased rapidly from March 2020 onward.  
- A small number of countries contributed to the majority of global confirmed cases.  
- Country-level trends vary significantly, highlighting differences in spread and recovery patterns.  
- Interactive filtering helps quickly analyze individual country situations.

## Conclusion

This dashboard demonstrates how Power BI can transform raw pandemic data into meaningful visual insights.  
The project highlights skills in **data visualization, dashboard design, interactivity, and analytical interpretation**, making it suitable for inclusion in a data analytics portfolio.

### Repository Contents
  -covid-19 _powerbi_dashboard.pbix → Power BI dashboard file
  -covid_19_clean_complete.csv → Dataset
  -README.md → Project documentation
