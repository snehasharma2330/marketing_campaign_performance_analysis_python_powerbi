
MARKETING CAMPAIGN PERFORMANCE ANALYSIS

## PROJECT OVERVIEW

### The project analyzes marketing campaign performance to understand how marketing spending, customer engagement, clicks, impressions and conversions affect campaign success.
 The project covers the period from ** July 2024 to June 2025** and uses **55,555 marketing campaign records**.
---

## BUSINESS PROBLEMS
### The analysis has the following real-world business questions that are asked?
•	Which factors influence marketing campaign ROI?
•	Does higher acquisition cost lead to better ROI?
•	Does higher reach through impressions result in more clicks and conversions?
•	Do more clicks lead to more conversions?
•	Does higher customer engagement improve ROI?
•	Which campaign generate the highest number of conversions?
•	How does campaign performance change over time?

---


## DATASET
<img width="1045" height="611" alt="image" src="https://github.com/user-attachments/assets/cc778a30-6ded-4fd9-a18e-ae5018bb632d" />
<img width="1042" height="580" alt="image" src="https://github.com/user-attachments/assets/23a18381-f4ad-494a-a36a-5c0108381cef" />




## TOOLS USED
•	**Jupyter Notebook** - Data cleaning and validation
•	**Pandas** - Exploratory Data Analysis 
•	*Matplotlib** - Data visualization
•	**Power BI** - Interactive dashboard and business reporting
---

## DATA CLEANING
### The dataset was first reviewed and cleaned before analysis by using pandas in python.
### Cleaning steps included:
### •	Checked for missing values
### •	Checked for duplicate values
### •	Reviewed data types
### •	Standardized date formats
### •	Checked numerical columns for invalid values
### •	Reviewed ROI values, including negative ROI
### •	Checked acquisition cost values
### •	Verified categorical values
### •	Reviewed outliers using statistical summaries and scatter plot
---

## ANALYTICAL APPROACH
### - Initial analysis showed the Average ROI, Conversions and clicks were relatively similar across campaign types. 
### - Therefore, relying only on average values by category would not provide strong or actionable conclusions. Instead, the analysis focused on campaign-level relationships using scatter plots.
### - This allowed the project to investigate questions such as whether higher spending leads to higher ROI, whether clicks lead to conversions and whether engagement and reach are associated with better campaign outcomes.
### - This approach helped avoid forcing conclusions from similar category averages and allowed the recommendations to be based on the actual patterns present in the data. 
## Exploratory Data Analysis
### Python was used to investigate relationships between important marketing patterns.
### •	Acquisition Cost vs ROI
### •	Clicks vs Conversions
### •	Impressions vs Clicks
### •	Engagement Score vs ROI
### •	Distribution of Conversions
### •	ROI distribution by campaign type
### •	Campaign performance over time 
---

## BUSINESS INSIGHTS
### 	Campaigns with higher clicks generally generated more conversions but similar clicks volumes sometimes produced very different conversion results, indicating that traffic alone does not guarantee conversions.
### 	The overall click-to-conversion rate was 22.03%, means around 22 out of 100 clicks resulted in a conversion, customer actually bought a product.
### 	The highest-performing campaigns achieved ROI of around 74.42 with low cost as outlier while several campaigns with high acquisition cost had ROI close to 0 or even negative.
### 	Only a small number of campaigns generated exceptionally high conversion volumes while most had lower numbers. This suggests that company should replicate the strategies used by the best performing campaigns.
### 	Campaigns with higher impressions generally generated more clicks and conversions but those with similar impression level produced different results, showing that reach alone is not enough.
### 	The average ROI across campaign types was also relatively similar, so individual campaign performance is more useful than simply comparing campaign types.
---
## RECOMMENDATIONS
	Increase investment in high ROI campaigns
Especially campaigns achieving results close to the top after checking their performance is consistent.
	Review high cost, low ROI campaigns and reduce or stop spending where campaigns continue to generate ROI close to 0 or negative.
	Since the overall click-to-conversion rate is 22.03%, investigate campaigns performing significantly below this level and improve their targeting, messaging or conversion process.
	Study the small group of campaigns generating exceptionally high conversions and identify what they have in common in terms of cost, engagement, audience and channel.
	Improve campaign target and creative rather than simply increasing impressions because campaigns with similar impressions still produced different click and conversion results.
	Avoid allocating budget based on category as it shows the average ROI and others were quite similar across them. So individual campaign will be better to make investment decisions.

---

## POWER BI DASHBOARD
### The dashboard was created to provide an executive-level view of campaign performance.
## Marketing Overview
### KPI Cards
•	Total Campaigns
•	Total Marketing Cost
•	Average Conversion
•	Average ROI
•	Average engagement score
### Visuals
•	Campaigns by Type Distribution
•	Average ROI by Customer Segment
•	ROI Trend
•	Conversion Trend
•	Short table summary by category (Num of campaigns, avg conversions, avg ROI)
---
## Campaign Performance
### KPI Cards
•	Total Clicks
•	Click-to-conversion rate
•	Total Conversions
•	Total Impressions
### Visuals
### •	Acquisition cost vs ROI
### •	Avg ROI by campaign IDs
### •	Clicks vs Conversions
### •	Engagement score vs ROI

### Interactive Filters
•	Date
•	Campaign Type
•	Channel Used
•	Customer Segment

---
## FINAL DASHBOARD
<img width="1056" height="554" alt="image" src="https://github.com/user-attachments/assets/476b261b-845c-4df6-99c4-2976e29cade5" />
<img width="1054" height="584" alt="image" src="https://github.com/user-attachments/assets/4af6be20-8aa4-46c7-94e3-b3e5d7de14d2" />

## BUSINESS IMPACT
This analysis helps marketing teams:
### •	Identify high performing campaigns
### •	Control inefficient marketing spending
### •	Understand the relationship between clicks and conversions.
### •	Improve customer engagement
### •	Monitor campaign performance over time
### •	Make better budget allocation decisions
---

## CONCLUSION
This project provided a detailed view of marketing performance by examining spending, reach, engagement and conversations. The analysis revealed that campaign results can vary significantly, highlighting the importance of evaluating multiple performance factors together. Overall, the findings provide a data-driven decision for improving future campaigns strategies and performance.

## Author
Sneha Sharma
www.linkedin.com/in/12sneha-sharma
