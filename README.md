# Development of UKI Bike Share Dashboard
 Develop a dashboard for "UKI Bike Share" that displays our key performance metrics for informed decision-making

# Project Requirement
- Hourly Revenue Analysis
- Profit and Revenue Trends
- Seasonal Revenue
- Rider Demographics

An interactive PowerBI dashboard can be downloaded [here](https://app.powerbi.com/view?r=eyJrIjoiNjIxODMxZTgtZmQ1MS00NjI1LTg2MTItYTBkNGZjMjM1NTA2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

The SQL queries utilized to perpare data for the dashboard can be found [here]

# Data Structure & Initial Checks

The companies main database structure as seen below consists of three tables: bike_share_yr_0, bike_share_yr_1, cost_table, with a total row count of 34758 records. A description of each table is as follows:
bike_share_yr_0, bike_share_yr_1 -> dteday,season,yr,mnth,hr,holiday,weekday,workingday,weathersit,temp,atemp,hum,windspeed,rider_type,riders
cost_table -> yr,price,COGS

# Executive Summary

### Overview of Findings

This dashboard displays hourly sales data across a week, with higher earnings in midday and early evening hours, particularly around 10 to 15 hours. suggesting these are the most profitable times. Days like Wednesday and Friday show notably higher sales, indicating variable profitability across the week. 

Below is the overview from the PowerBi dashboard: 

![image](https://github.com/user-attachments/assets/a6004df4-dead-4515-8c87-30eacd141c19)


# Insights Deep Dive
### Rider Demographics:

- The number of riders doubled from 1M in 2021 to 2M in 2022 which indicates a substantial increase in customer base, contributing to revenue growth.
- In 2021, registered riders accounted for 80.11%, and casual riders for 19.89%. and in 2022, registered riders slightly increased to 81.81%, and casual riders dropped to 18.19%.
This suggests a growing preference for long-term commitment among riders.

### KPI Over Time:
Monthly Trends:

Revenue and profit followed similar growth trends in both years, peaking during summer months (June to August).
Rider counts showed significant increases during peak months in 2022 compared to 2021. The business continues to benefit from seasonality but is scaling consistently across months.  

### Hourly Sales Patterns:
Profitable Hours:
The most profitable hours (midday and early evening, around 10 AM to 3 PM) remain consistent across both years.
However, the absolute revenue earned during these hours increased significantly in 2022.

Day Impact: 
Midweek days like Wednesday and Friday continue to show higher sales.

### Overall Summary:
The business exhibited significant growth in all aspects from 2021 to 2022, doubling revenue, profit, and rider base.
Growth was consistent across all seasons and key time frames, with registered riders showing stronger engagement.
The sustained profit margin reflects effective cost management alongside expansion.


# Recommendations:

Based on the insights and findings above, we would recommend the marking team to consider the following: 

Conservative Increase: Considering the substantial increase last year, a more conservative increase might be prudent to avoid hitting a price ceiling where demand starts to drop. An ioncrease in the range of 10-20% could test the market's response withoud risking a significant loss of customeres. 
Price Setting:
- If the price in 2022 was 4.99$, a 10% increase would make the new price about $5.49.
- Or a 15% increase would set at $5.74

Recommendation Strategy: 
Market Analysis: Conduct further market research to understand customer satisfaction, potential competitive changes, and the overall economic environment. This can guide whether leaning towards the lower or higher end of the suggested price increase. 

Segmented Pricing Strategy: Consider different pricing for casual versus registered users, as they may have different price sensitivities. 

Monitor and adjust: Implement the new prices but be ready to adjust based on immediate customer feedback and sales data. Monitoring closely will allow you to fine-tune your pricing strategy without committing fully to a price that might turn out to be too high.
