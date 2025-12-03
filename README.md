# SQL-Portfolio_Google-Analytics-Sample
My Google Analytics Sample dataset SQL Portfolio project, accessed via BigQuery.

Overview: This project analyzes one year of Google Analytics (Universal Analytics) sample ecommerce data stored in BigQuery.
The focus is behavioral traffic patterns — evaluating how different acquisition channels and device types impact user engagement.

Because the sample dataset contains limited ecommerce transactions, I centered the analysis on session-level engagement, not revenue.

Objective: Identify which traffic channels and device types drive the strongest user engagement, using metrics such as pageviews per session, bounce rate, session duration, and the share of new vs. returning visitors.

Data Source: bigquery-public-data.google_analytics_sample.ga_sessions_*

Date Range: Aug 1st, 2016 - Aug 31st, 2017

The dataset includes session-level fields such as:

- channelGrouping
- device.deviceCategory
- totals.pageviews
- totals.timeOnSite
- totals.bounces
- totals.newVisits
- fullVisitorId

My SQL Query is below:

[Behavioral Traffic Patterns.sql](https://github.com/user-attachments/files/23892817/Behavioral.Traffic.Patterns.sql)

Here are my findings:

1. Referral traffic drives the strongest engagement

Referral sessions showed the highest pageviews per session, suggesting these users arrive with stronger intent—often from blogs, reviews, or partner content.

2. Search channels (paid + organic) perform consistently well

Both Organic and Paid Search delivered above-average engagement, with users viewing more pages per session compared to Social.

3. Social traffic underperforms across all device types

Social consistently had the lowest pageviews per session and highest bounce rates, which are common for casual, mobile-heavy traffic.

4. Desktop and Tablet users show stronger engagement than Mobile

Desktop and Tablet users consumed more content per session, indicating that larger screens may support deeper browsing behavior.

5. Desktop accounts for the majority of total traffic

Desktop drives over twice the session volume of Mobile, aligning with its stronger engagement performance.



