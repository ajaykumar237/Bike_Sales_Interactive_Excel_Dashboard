# Bike Sales Interactive Excel Dashboard

### Project Overview
This project aims to provide actionable insights into the sales performance of a bike organization. So that, organization can understand their customers and increase sales in the upcoming year. 






### Data Sources
Sales Data: The primary dataset used for this analysis is the "raw_bikedata.xlsx" file, containing detailed information about each sale made by the store.
### Tools
- Excel - Data Cleaning, Data Analysis and Dashboard Creation
  
### Data Cleaning/ Preparation
In the initial data preparation phase, performed the following tasks:
1. Data loading and inspection
2. Data Cleaning - remove the duplicates from dataset, made data consistent in columns (marital status, gender, income, commute distance)
3. Data Processing - added a new column (age brackets)
   - age brackets = IF(>55, "Old", IF(>=30, "Middle Age", IF(<30, "Youth","Invalid")))


### Data Analysis
1. Used pivot table to calculate and analyse data
2. Created 3 pivot charts to visually analyse the data at a quick glance
3. Connected all the charts with slicers to analyse the data as per user selection

### Results/ Findings

The analysis results are summarized as follows:
- Women are more likey to buy compared to men (~65%)
- Maharashtra, Karnataka, Uttar Pradesh are the top 3 buying states (~35%)
- Adult age group 30-49 years contributing max (~50%)
- Amazon, Flipkart and Myntra are max contributing (~80%)

### Recommendations
Based on the analysis, recommend the following actions:
  -  Target women customers of age group 30-49 years
  -  Aim for women who lives in Maharashtra, Karnataka, Uttar Pradesh
  -  Show ads/coupons/offers availabe on Amazon, Flipkart and Myntra

    
