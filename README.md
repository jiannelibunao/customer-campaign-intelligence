# Customer and Campaign Intelligence Dashboard
![campaign-page](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/504b82b9b2c5e4eb4d2a5696eadaac14dbb2923f/Assets/header_2.png)

## Table of Contents
1. Project Background
2. Data Structure and Initial Checks
3. Executive Summary
4. Insights Deep Dive
5. Recommendations

## **Project Background**
Maven Marketing is a small digital marketing agency that delivers campaigns for their products and services via physical and digital channels.
The company has significant amounts of data on its sales, marketing efforts, customer demographics and activity, and campaign performance which has underperformed lately. This project thoroughly analyzes and synthesizes this data to uncover critical insights that will improve Maven’s commercial success.

Insights and recommendations are provided on the following key areas:
- **Customer Acquisition:** Evaluation of historical customer activity patterns globally
- **Revenue Indicators:** Exploration of different areas of revenue growth focusing on customer profile, and product & channel performance, understanding their impact on sales and marketing strategies
- **Customer’s Purchasing Power:** An analysis of customer groups that drives revenue the most, understanding their impact on sales and marketing
- **Campaign Performance:** An assessment of the campaigns’ success based on channel reach and customer profiles

## **Data Structure & Initial Checks**
Maven Analytics dataset structure as seen below consists of one single table with 28 native columns and a total row count of 2,240 records.

![dataset-structure](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/353d379ff529c9abaaf8f0c3c76d7ebe792d3ffa/Assets/dataset-structure.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the dataset. Power Query was utilized to inspect and perform quality checks.

## Executive Summary
### Overview of Findings
After the sudden peak in July 2012, the agency’s efforts in customer acquisition have steadily declined, with significant drops in April and June 2013. On the other hand, most successful campaign can be seen in the last stage with 864 responses (20.6%). Key performance indicators have shown mixed year-over-year outcomes: total customers by +33.33%, average customer value (ACV) by -19.4%, revenue by +93.6%, and campaign success rate by -25.5%. Despite the positive trend for customer acquisition, the declining rate of campaign success and its possible factors should be explored further. This additional step will highlight key areas for improvement and better efficiency.

## Insights Deep Dive
### Overview’s Page 

![overview-page](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)

- **The agency’s customer acquisition biggest peak was one month after its opening in August 2012 with 117 new customers.** This corresponds to the company’s opening campaigns with attractive benefits and discounts.
- **Steady but slowly declining growth was seen** despite having a high growth rate of 140%. This can be explained by the start date of the data set being in July.
- **Average Customer Value (AOV) also declined with only $602 per customer or 19.40% compared to the previous year.** This could indicate weaker customer activity from the date of enrollment.
- **Uneven success rate across campaign stages.** However, “Last” campaigns showed to be the most effective with 5,958 responders totaling a 33.47% success rate. 
- **Highest value customer segment emerged as middle-aged and married, having middle-income salaries and holding a bachelor’s degree.** This group consistently generated the strongest revenue.
- **Wine dominated product categories with $6.3M in revenue**, followed by Meat and Gold.
- **Across all campaigns, In Store engagement outperformed Web and Catalog by a wide margin.** This channel remains the most reliable touchpoint for conversions.

### Customer’s Page

![customer-page](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard2.jpg)

Apart from the growing customer base and decreasing ACV, here are the insights under this section:
-	**Middle-income customers are highest in number, however, Upper Middle Income has the highest Average Order Value.** This suggests an opportunity to attract big spenders with targeted campaigns.
-	**Bachelor’s degree holders dominate** across income groups and appear to drive higher order values. 
-	**Wine consistently tops the list** of most popular products across the segments: Income, Age, and Marital Status. Meat section falls second.
-	**Recency in purchase slightly declined** by 2% compared to previous year. 
-	**Most of the purchase activity occurs beyond the 30-day benchmark** despite having 414 active buyers out of 1,170 customers, as shown by the lighter bars dominating the right side of the chart. This suggests delayed repeat purchases, campaign inefficiency, and revenue pacing concerns.

### Campaign’s Page

![campaign-page](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard3.jpg)

-	**Accepted campaigns and responders grew by 79% and 63% respectively** compared to previous year despite a drop of 25% in success rate.
-	**Spain was the most responsive country** accounting 260 campaigns entertained.
-	**Last campaigns were the most effective in converting customers across all segments**, accounting for 31.55% of the total responders via In Store engagements. 
-	**Last campaigns delivered the strongest results across all channels**, especially in In-Store (1,440) and Web (900). 
-	**First and Fifth campaigns also performed well**, suggesting they are strong entry and re-engagement points.
-	**The most responsive profile: Middle Aged, Middle Income, Married, Bachelor’s Degree holders**, also delivers the highest monetary values. This shows that customer engagement is proportionate to profitability, making this segment the strongest target for campaigns and loyalty strategies.
-	**130 out or 283 or 46% of the responders were active buyers**. This indicates that despite the declining immediate success of campaigns, they are still effective in retaining loyalty among our customers.
-	**Only 130 out of 283 responders were considered active buyers**, with most purchases occurring beyond the 30-day mark. This delayed engagement suggests campaign mismatch, weak urgency or relevance, and retention gaps.

## Recommendations
Based on the uncovered insights, the following recommendations have been provided:
-	**Prioritize High-Value Segments**
    - Focus on Middle Aged, Middle Income, Married, Bachelor’s Degree holders. They consistently drive the highest revenue and engagement across both customer and responder profiles.
    - Use this segment as the foundation for persona-based targeting, loyalty tiering, and tailored messaging.
-	**Replicate Winning Campaigns**
    - The Last campaign had the highest success rate (31.55%) and response volume (2,754). First and Fifth campaigns also performed well.
    - Replicate the messaging, timing, and channel mix of successful campaigns into earlier stages to boost engagement and reduce marketing costs.
-	**Optimize Channel Strategy**
    - In Store is the top performing channel across all campaign stages, especially in the Last campaign (1,440 responses).
    - Prioritize In Store for high impact campaigns and consider pairing it with Web for broader reach and digital convenience.
-	**Address Recency Gaps**
    - Only 414 of 1,170 customers and 130 of 283 responders are active buyers within 30 days.
    - This low recency may be contributing to the 25.5% drop in campaign success rate. Introduce retention-focused strategies like post-purchase nudges, time-sensitive offers, and loyalty perks to encourage faster repeat purchase.
-	**Leverage Product Preferences**
    - Wine is the top revenue driver, especially among Middle Income customers. Use this insight to craft product-led campaigns that resonate with high-value segments.
    - Consider bundling wine with other popular products (e.g., meat, gold) for upsell opportunities.
-	**Refine Education-Based Messaging**
    - With 50.85% of customers holding a Bachelor’s degree, education-based messaging can enhance relevance and trust.
    - Position campaigns with aspirational, value-driven language that appeals to educated buyers.
-	**Monitor Value Trends**
    - Despite strong revenue growth (93.6%), average customer value dropped by 19.4%. This signals a need to balance acquisition with retention and increase order value through bundling, tiered pricing, or exclusive offers.


## Let's Connect
[LinkedIn](https://www.linkedin.com/in/jiannelibunao/ "LinkedIn")  |  Digital Portfolio
