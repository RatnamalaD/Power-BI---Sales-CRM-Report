# About this Project
As a BI Developer for Mavy Tech (a computer hardware company), I created an interactive Power BI dashboard for sales managers to track their teams' quarterly performance and provide actionable recommendations to improve performance and increase sales.

## The Dataset
The dataset contained records exported from Mavy Tech's CRM from October 2016 to December 2017. It held details of opportunities with associated information such as product, account, and whether the sale was won or lost.

## Key Assumptions
When creating a dashboard/report, I always work with business owners to make sure I truly understand the intended purpose and the questions they seek to answer. In this report, I made the following key assumptions:

### Sales managers are looking for answers to the following questions for their team and obtain actionable insights:
#### Key questions include:
- How is my team tracking against KPIs?
- Are there team members who require extra support?
- Where should I focus my efforts to improve performance?
- Is my team performing above average compared to the rest of the business?
#### Main KPI: 
- Dollar value of sales made
#### Other important metrics: 
- Number of sales, conversion %, and average sales value
- Managers may want to compare performance across teams or over time
- Focus is on team-level dashboards rather than executive-level comparisons
- Assumed "Current quarter" is Q4 2017, but the dashboard would update continuously in practice

## Dashboard:
### 1. Quarterly Performance Summary

This is the main page of the report, containing the most critical information for sales managers. Users select their name from the sales manager slicer and quarter from the Quarter slicer, and this populates all the KPIs for their team. The key KPIs are shown clearly at the top of the page, with figures for the previous quarter and the average figure across all sales teams for each metric provided below for additional context. This allows the sales manager to see their own figures and understand generally how they are doing compared to other teams and towards their own goals.

![Summary](https://github.com/user-attachments/assets/8f0293cd-a6f3-44db-9446-5e29493b18b8)
 

### 2. Sales Agent and Product KPIs

This page lets sales managers select the quarter and their name from the slicers and view KPIs like total sales, Win %, average weeks to close, and lost % for that quarter compared to other teams.

![Product and Sales agent metrics](https://github.com/user-attachments/assets/f7b685f1-7177-4c7a-80ef-eb7818779de9)
 

### 3. Quarterly KPIs at Team Level

This page allows sales managers to view their team's performance over the previous quarters to identify trends. Managers can select their name and quarter to get insights into different product sales and the performance of their sales agents.

![Team Performance](https://github.com/user-attachments/assets/6e547e07-7a06-4d26-ae99-f42250f7db0f)


 ## Insights and recommendations at the team level
- **Cara Losch’s team** shows a consistent quarter-over-quarter decline in total sales, and their performance has remained below the overall team average. The primary drivers are the significantly lower contributions from Violet Mclelland and Garret Kinder compared to their peers, indicating a need for targeted coaching and training to improve their results.
- **Celia Rouche’s team** is experiencing a steady quarter-over-quarter decline in total sales, consistently performing below the overall team average. The primary contributions to this trend are the poor performance of Rosalina Dieter and Hayden Neloms; they need coaching and training to improve their sales.
- **Dustin Brinkmann’s team** shows a consistent quarter-over-quarter decline in total sales and continues to perform below the overall team average. All the team members have lower sales compared to other teams, with Versie Hillebrand showing a particularly significant drop each quarter. These trends indicate that the team would benefit from targeted training and performance support.
- **Melvin Marxen team's** total sales have shown steady quarter-over-quarter growth through Q3, consistently outperforming the overall team average. Q4 is not as good as other quarters, though.
- **Rocco Neubert’s team** has experienced a slight quarter-over-quarter decline in total sales since Q2, although their performance continues to remain above the overall team average. Boris Faz consistently records lower sales than the other team members, indicating a need for targeted coaching and development.
- **Summer Sewald’s team** has experienced a slight quarter-over-quarter decline in total sales since Q2, though their performance remains above the overall team average. Within the team, Kami Bicknell consistently records lower sales compared to other members, indicating a need for targeted training and development.

## Quarter-over-quarter trend
- Decline since Q2
- Overall sales have been declining quarter over quarter for most teams
- The pattern suggests a need for deeper analysis into pipeline quality, seasonality, and pricing impacts.

## Product conversion and revenue
- **GTX Pro** demonstrates a stronger win rate compared to the other products.
- **GTK 500** is a high-value product, yet sales remain very low or non-existent across all teams. This presents an opportunity to launch targeted marketing campaigns to boost its visibility and drive sales growth.
   
