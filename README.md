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
   - age brackets = IF(L2>55, "Old", IF(L2>=30, "Middle Age", IF(L2<30, "Youth","Invalid")))


### Data Analysis
1. Used pivot table to calculate and analyse data
2. Created 3 pivot charts to visually analyse the data at a quick glance
3. Added slicers to analyse the results on the basis of marital status, region, and education
4. Connected all the charts with slicers to analyse the data as per user selection 

### Results/ Findings

The analysis results are summarized as follows:
- Average income of male is $60,124 and female is $55,774 who purchased bike
- Ones who commute 0-1 Miles puchased the maximum number of bikes 200 out of 481
- Middle Age (31-54)years people purchased 383 out of 481 bikes

### Recommendations
Based on the analysis, recommend the following actions:
- Aim for people who are in the middle age group (31-54)years
- Target the people with average income more than $55,000
- Give offers to ones who commutes less than 1 Mile per day

    
