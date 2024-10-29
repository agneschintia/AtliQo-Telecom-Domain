# AtliQo-Telecom-Domain
## Project Background

AtliQo Telecom, is one of the leading telecom providers in India and launched its 5G plans in May 2022 along with other telecom providers.

However, the management noticed a decline in their active users and revenue growth post 5G launch in May 2022. AtliQo’s business director requested their analytics team to provide a comparison report of KPIs between pre and post-periods of the 5G launch. The management is keen to **compare the performance between these periods** and get insights that would enable them to make informed decisions to **recover their active user rate** and other key metrics. They also wonder if they can **optimize their internet plans to get more active users**. 

Insights and recommendations are provided on the following key areas:

- **Comparative Analysis of Pre and Post-5G Launch Performance**: An evaluation of the key metrics by pre and post of the 5G launch, focusing on Revenue, ARPU, Monthly Active Users, and Unsubscribed Users.
- **Marketshare Level Performance**: An analysis of Atliqo’s position among competitors in the market.
- **Plans Revenue Analysis**: Evaluation of historical plans sales pattern between pre and post of the 5G launch.

An interactive Power BI dashboard can be viewed here: https://app.powerbi.com/view?r=eyJrIjoiYzI3ZjJkZTQtYmIwMy00YTYxLWE1ZmYtZjY0MDRhMGU2ODk5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9.

The Codebasics Resume Project Challenge can be found here: https://codebasics.io/challenge/codebasics-resume-project-challenge/6.

## Data Structures and Initial Checks

AtliQo’s database structure as seen below consists of six tables: dim_cities, dim_date, dim_plan, fact_atliqo_metrics, fact_market_share, fact_plan_revenue.

![Atliqo ERD](https://github.com/user-attachments/assets/15a2d6bd-2ed6-4de2-9fbe-7688bcbdf87c)

During the data transformation process, I converted the currency from lakhs or crores to INR. This normalization process can make the analysis process much easier and better to understand.

## Executive Summary

### Overview of Findings

After peaking in February which was the Pre-launch of the 5G, the company’s revenue is decreasing and lost monthly active users in June just a month after the launch of the 5G, by losing monthly active users the company gained unsubscribed users and the only metrics that works well is ARPU. Key performance indicators have shown the comparison between pre and post launch of the 5G: revenue by -0.51%, ARPU by 9.95%, Montly Active Users by -9.03%, and Unsubscribed users by 19.03%. This decline can be broadly attributed to a post-launch 5G normalcy, the following sections will explore additional contributing factors and highlight areas for improvement.

Below is the overview page from the Power BI dashboard and more examples are included throughout the report. The entire dashboard can be found here: https://app.powerbi.com/view?r=eyJrIjoiYzI3ZjJkZTQtYmIwMy00YTYxLWE1ZmYtZjY0MDRhMGU2ODk5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9.

#### Main KPI Dashboard

<img width="591" alt="Main KPI" src="https://github.com/user-attachments/assets/f69be814-2f1b-43c2-a6a7-c6a88a84facc">

This KPIs are included Revenue, Average Revenue Per User (ARPU), Monthly Active Users (MAU), and Unsubscribed Users in the period of time of Pre and Post Launch of the 5G products in AtliQo.

#### Market Share Dashboard

<img width="599" alt="Marketshare" src="https://github.com/user-attachments/assets/78e8d4f1-d288-41f5-887d-d615a1b848da">

This shows the AtliQo position in the market share, and this dashboard also shows the top and bottom cities for Revenue, ARPU, MAU, and Unsubscribed Users.

#### Plans Dashboard 

<img width="599" alt="Plan" src="https://github.com/user-attachments/assets/e86fc4fb-642d-4983-940c-5d84d0b5318e">

This dashboard shows the revenue of each plans whether it is the non-5G or the 5G products from Jan-Apr (pre-launch) until Jun-Sep (post-launch). This dashboard also shows the top 5 cities by Plan Revenue.

### **Comparative Analysis of Pre and Post-5G Launch Performance**:

- **Pre and Post-Launch 5G Revenue:** The total revenue from January to April, before the 5G launch, ₹ 15.98 billions. After 5G launch in May, the revenue decreased slightly to ₹ 15.90 billions. This -0.51% downfall revenue suggests a need for further analysis to understand whether the issue lies in pricing, customer perception, external factors, and to inform potential adjustments in strategy.
- **ARPU Pre and Post Launch 5G:** The total ARPU before the 5G launch is ₹ 190.23. After the 5G launch in May, the ARPU increased to ₹ 211.25. This rise can indicate increased customer spending due to the enhanced capabilities of the 5G.
- **Monthly Active Users (MAU) Pre and Post Launch 5G:** The total MAU before the 5G launch ₹ 1.41 millions. After 5G launch in May, the MAU decreased to ₹ 1.29 millions. This fall can indicate weak interest and satisfaction with 5G.
- **Unsubscribed Users Pre and Post Launch 5G:** Total Unsubscribed users before 5G launch is ₹ 5.63 millions, and after the launch of the 5G the total unsubscribed users increased by ₹ 6.96 millions. This increasing number suggests that the customers are more satisfied with the Pre-5G services.

### **Marketshare Level Performance:**

- AtliQo remained in the third place of the market share, the Post-launch of the 5G is reducing the company’s market share. The rise in ARPU likely indicates effective upselling to existing customers who are willing to pay more for 5G features or premium plans. However, the drop in market share suggests that the 5G product may not be attracting new customers at the same rate as competitors.
- The top 5 cities for Revenue, ARPU, MAU, and Unsubscribed Users are always the same; Mumbai, Delhi, Kolkata, Bangalore, and Chennai. These are the main cities in India.

### Plan Revenue Analysis:

- The P8, P9, and P10 has discontinued in Post-launch of 5G, and P11, P12, and P13 are the 5G products which has launched alongside with the 5G. P1 drives the most revenue growth by total ₹ 4.20 billions from Pre to Post 5G launch. The P11 which the 5G product has contributed around ₹ 1.86 billions from June to September. The company achieved the biggest revenue in July, this because the high demand of 5G in the market.

### Key Takeaways and Recommendations:
- **Decline in Revenue and Active Users in May.** Many users may be hesitant to switch to 5G due to cost concerns, limited device compatibility, or uncertain benefits over 4G. The initial price point of 5G plans, especially if premium-priced, may lead to a decline in active users, particularly among cost-sensitive customers who see less immediate value in upgrading. To address this challenge the company may introduce phased, competitive pricing for 5G, including promotions or incentives for early adopters.
- **Recovering Active Users.** Offer competitive pricing or promotional deals for existing users to encourage them to stay or reactivate their accounts. Consider tiered pricing that caters to different user needs.
