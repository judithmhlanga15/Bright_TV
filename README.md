📺 BrightTV Viewership Analytics
📌 Case Study Overview

BrightTV is looking to grow its subscription base during the current financial year. The CEO has approached the Customer Value Management (CVM) team to provide data-driven insights that can support this objective.

This project analyzes BrightTV subscriber profiles and viewing-session data to understand who is watching, how they watch, when consumption is highest or lowest, and what factors influence viewing behavior.

The analysis is designed to support strategic decisions around customer engagement, content recommendations, retention, and subscriber acquisition.

🎯 Business Objective

The primary objective of this case study is to provide actionable insights that can help BrightTV:

Increase subscriber consumption.
Improve customer engagement.
Understand viewing behavior and usage trends.
Identify factors that influence consumption.
Develop content strategies for low-consumption periods.
Identify opportunities to grow the BrightTV user base.
Support CVM initiatives with data-driven recommendations.
❓ Key Business Questions

The analysis focuses on four key questions:

1. What are the user and usage trends of BrightTV?

The analysis investigates:

Subscriber demographics.
Age-group viewing behavior.
Gender differences in consumption.
Regional consumption patterns.
Viewing frequency.
Viewing duration.
Viewing trends over time.
Weekday versus weekend consumption.
Peak and low viewing periods.
Channel performance.
2. What factors influence consumption?

Potential consumption drivers investigated include:

Age group
Sex
Ethnicity
Region
Day of the week
Day classification
Time of day
Hour of day
TV channel
Viewing duration
Screen-time bucket

The objective is to identify which customer and behavioral characteristics are associated with higher or lower BrightTV consumption.

3. What content should be recommended for low-consumption days?

The analysis identifies days and periods where viewing consumption is lower and investigates which TV channels and content categories perform better during comparable periods.

This can help BrightTV develop targeted programming and content recommendations designed to increase engagement during low-consumption periods.

4. What initiatives could grow BrightTV's user base?

The findings are translated into potential CVM initiatives focused on:

Customer acquisition
Engagement
Retention
Cross-selling
Referral opportunities
Social media engagement
Targeted campaigns
Content-led acquisition
🗂️ Dataset

The dataset contains information about BrightTV subscribers and their viewing sessions.

Each viewing session represents one record in the dataset.

This means that if a subscriber watches BrightTV multiple times, each session is recorded separately.

📊 Dataset Fields
Field	Description
Sub_ID	Unique subscriber identifier
Sex	Subscriber gender
Ethnicity	Subscriber ethnicity
Age_group	Subscriber age segment
Region	Subscriber geographic region
Email_flag	Indicates whether the subscriber has an email contact
Social_media_handle_flag	Indicates whether the subscriber has a social media handle
RecordDate_SAST	Record date converted to South African Standard Time
Watch_date	Date of the viewing session
Day_name	Day of the week
Month_name	Month of viewing
Event_year	Year of the viewing event
Event_day	Day number
Hour_of_day	Hour during which the session occurred
Day_classification	Classification such as weekday/weekend
Watch_time	Time of the viewing session
Time_of_day	Viewing period
Duration	Session viewing duration
Duration_hours	Viewing duration in hours
Duration_seconds	Viewing duration in seconds
Screen_time_bucket	Categorized viewing duration
Tv_channel	TV channel watched
🕐 Time Zone Conversion

The original dataset contains timestamps supplied in UTC.

For this analysis, timestamps are converted to South African Standard Time (SAST) to ensure that viewing behavior is analyzed according to the correct local time.

This is particularly important when analyzing:

Peak viewing hours
Low-consumption periods
Day-of-week patterns
Weekday versus weekend behavior
Content performance
Channel performance

Incorrect time-zone handling could result in viewing sessions being assigned to the wrong day or time period.

👀 Consumption Definition

BrightTV consumption is measured at the session level.

Each session represents one viewing record for a subscriber.

Key consumption measures include:

Viewing Sessions

The number of viewing sessions recorded.

Total Sessions = COUNT(Session Records)

Unique Subscribers

The number of individual subscribers who generated viewing sessions.

Unique Subscribers = COUNT(DISTINCT Sub_ID)

Total Watch Time

The total amount of time spent watching BrightTV.

Total Watch Time = SUM(Duration)

Average Session Duration

The average amount of time spent per viewing session.

Average Session Duration =
Total Watch Time / Total Sessions

🧹 Data Preparation

The analysis includes several data preparation steps:

Reviewing missing values.
Checking duplicate records.
Standardizing categorical variables.
Converting UTC timestamps to SAST.
Creating useful date and time dimensions.
Creating viewing-time categories.
Standardizing duration fields.
Creating consumption metrics.
Segmenting subscribers by demographic characteristics.
Identifying high- and low-consumption periods.
📈 Analysis Areas
👥 Subscriber Analysis

Subscriber characteristics are analyzed to understand the BrightTV customer base.

Key dimensions include:

Age group
Sex
Ethnicity
Region
Email availability
Social media availability

This helps identify which subscriber segments have the highest engagement and where opportunities may exist for targeted CVM strategies.

📺 Viewership Analysis

Viewership behavior is analyzed using:

Total viewing sessions
Unique subscribers
Total watch time
Average session duration
Viewing frequency
Channel consumption
Time-of-day consumption
Day-of-week consumption
📅 Time-Based Analysis

Viewing patterns are analyzed across:

Days
Months
Years
Weekdays
Weekends
Hours
Time-of-day categories

This helps BrightTV understand when customers are most and least engaged.

🔎 Consumption Drivers

A major objective of this analysis is to determine which factors are associated with higher consumption.

The analysis compares consumption across different:

Demographics
     ↓
Age Group
Sex
Ethnicity
Region

Behavior
     ↓
Viewing Time
Day
Duration
Frequency

Content
     ↓
TV Channel


These relationships can help CVM identify customer segments and behavioral patterns that can be targeted with specific interventions.

📺 Low-Consumption Day Strategy

Low-consumption days are identified by comparing viewing sessions and watch time across days.

Once these periods are identified, BrightTV can investigate which channels perform well during higher-consumption periods and use those insights to inform programming strategies.

Potential recommendations include:

Promoting popular content before low-consumption periods.
Scheduling high-performing content during weak viewing periods.
Creating themed programming days.
Using targeted notifications to promote upcoming content.
Promoting content based on subscriber viewing preferences.
Creating weekend or weekday-specific campaigns.
Using popular channels as lead-in programming.

The objective is not simply to increase the number of sessions, but to increase meaningful viewing engagement.

🚀 User Growth Recommendations

Based on the analysis, BrightTV can consider several CVM initiatives.

1. Targeted Acquisition

Identify high-engagement subscriber segments and use their characteristics to develop targeted acquisition campaigns.

For example:

Age-specific campaigns
Region-specific campaigns
Content-interest campaigns
Social media campaigns
2. Referral Programme

Subscribers with high engagement could be encouraged to refer friends and family.

Potential incentives include:

Additional viewing benefits
Promotional discounts
Free trial extensions
Exclusive content access
3. Content-Led Acquisition

Popular content can be used as an acquisition tool.

BrightTV could promote:

"Join BrightTV to watch what everyone is watching."

Popular channels and programmes can become part of acquisition campaigns.

4. Personalized Content Recommendations

Use viewing behavior to recommend relevant content to subscribers.

For example:

Subscriber viewing history
          ↓
Preferred channel
          ↓
Preferred time
          ↓
Recommended content
          ↓
Increased engagement

5. Re-engagement Campaigns

Subscribers with declining or low consumption can be targeted with personalized campaigns.

Possible triggers include:

Reduced viewing frequency
Shorter sessions
No recent viewing
Low engagement periods
6. Digital Engagement

The Email_flag and Social_media_handle_flag fields can help BrightTV understand which subscribers can be reached through digital channels.

This creates opportunities for:

Email campaigns
Social media campaigns
Content alerts
New-release notifications
Personalized recommendations
Promotional offers
📊 Dashboard Recommendations

The analysis can be presented through an interactive dashboard containing the following KPI cards:

👥 Unique Subscribers
▶️ Total Viewing Sessions
⏱️ Total Watch Time
📺 Average Session Duration
🏆 Top TV Channel
📅 Highest Consumption Day
🕐 Peak Viewing Hour
📉 Lowest Consumption Day

Suggested visualizations include:

Subscriber Demographics
Subscribers by age group
Subscribers by region
Subscribers by sex
Subscriber distribution by ethnicity
Viewership
Sessions over time
Watch time over time
Average session duration
Consumption by day
Consumption by hour
Consumption by time of day
Content
Top TV channels
Channel watch time
Channel session volume
Channel performance by demographic
Channel performance by day
Customer Value Management
High-consumption segments
Low-consumption segments
Re-engagement opportunities
Acquisition opportunities
Digital-contactable subscribers
🎤 20-Minute Presentation Structure

The analysis is designed to support a 20-minute executive presentation.

Slide 1 — Introduction

BrightTV Viewership Analytics

Business objective
Case study context
Analytical approach
Slide 2 — Executive Summary

Present the most important findings and recommendations.

Slide 3 — Subscriber Overview

Show:

Subscriber demographics
Regional distribution
Age distribution
Slide 4 — Usage Overview

Show:

Total sessions
Unique subscribers
Total watch time
Average session duration
Slide 5 — Consumption Trends

Analyze:

Daily trends
Monthly trends
Weekday versus weekend
Slide 6 — Peak Viewing

Identify:

Peak hours
Peak days
High-consumption periods
Slide 7 — Low Consumption

Identify:

Lowest-consumption days
Lowest-consumption periods
Potential reasons
Slide 8 — Consumption Drivers

Show the demographic, behavioral, and content factors associated with consumption.

Slide 9 — Content Recommendations

Recommend channels/content strategies for low-consumption periods.

Slide 10 — User Growth Strategy

Present CVM recommendations for:

Acquisition
Engagement
Retention
Re-engagement
Slide 11 — Recommended Actions

Prioritize initiatives based on expected business impact.

Slide 12 — Conclusion

Summarize the key findings and recommended next steps.

🔄 Project Workflow
Raw BrightTV Data
        ↓
Data Quality Checks
        ↓
Data Cleaning
        ↓
UTC → SAST Conversion
        ↓
Feature Engineering
        ↓
Consumption Analysis
        ↓
Subscriber Segmentation
        ↓
Content & Channel Analysis
        ↓
CVM Insights
        ↓
Business Recommendations
        ↓
Dashboard / 20-Minute Presentation

💡 Expected Business Impact

The analysis aims to help BrightTV move from simply understanding what customers watch to understanding how viewing behavior can be used to grow the business.

The insights can support:

📈 Subscriber acquisition
❤️ Customer retention
📺 Increased viewing consumption
🎯 Targeted marketing
🔔 Re-engagement campaigns
📱 Digital engagement
🎬 Content strategy
💰 Customer Value Management
🚀 Future Enhancements

Future analysis could incorporate additional data sources such as:

Subscription plan information
Subscription revenue
Customer tenure
Churn data
Content genre
Programme-level information
Marketing campaign exposure
Device type
Customer acquisition channel
Viewing location
Subscription upgrades/downgrades

Combining these datasets would allow BrightTV to move toward predictive churn modelling, customer lifetime value analysis, personalized recommendations, and subscription propensity modelling.

👤 Author

BrightTV Viewership Analytics

A data analytics case study focused on transforming subscriber and viewing-session data into actionable insights for Customer Value Management and subscription growth.

⭐ Project Summary

This project demonstrates the end-to-end analytics process:

Data Cleaning → Time-Zone Transformation → Feature Engineering → Exploratory Analysis → Consumption Drivers → Content Recommendations → CVM Strategy

The ultimate goal is to turn BrightTV's viewing data into actionable business decisions that increase engagement and grow the subscriber base.
