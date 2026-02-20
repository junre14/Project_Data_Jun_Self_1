🏃 Running Event Performance Analysis

📌 Project Overview
This is my first self-initiated data analytics project using running event data from Kaggle.
The objective of this project is to analyze event performance from the perspective of an Event Manager — focusing on runner performance, participation insights, and operational evaluation.
This project helped me practice SQL for data transformation and Power BI for visualization while improving my analytical thinking from a business point of view.

🎯 Business Objective
As an Event Manager, I want to understand:
1. How was the overall event performance?
2. How many runners finished vs DNF/DNS?
3. How was the runners' performance overall?
4. Which country had the best average pace?
5. Which category performed better?
6. Were there any potential anomalies or fraud indications?

📊 Dataset Information
The dataset includes:
1. Name
2. Category / Class
3. BIB Number
4. Country
5. 3.9K Checkpoint Time
6. Chip Time
7. Finish Time
Since start time data was not available, DNF/DNS detection was analyzed based on available timing fields.

📈 Analysis Conducted
1️⃣ Overall Performance
1. Average pace calculation
2. Finish rate analysis
3. DNF/DNS identification

2️⃣ Performance by Segment
1. Average pace by Country
2. Average pace by Category
3. Top 3 Podium per Category

3️⃣ Operational & Data Check
1. Checkpoint time consistency
2. Potential anomaly detection
3. Data validation through timing comparison

🛠 Tools & Technologies
1. SQL → Data cleaning, transformation, pace calculation
2. Power BI → Dashboard & visualization
3. Kaggle Dataset → Data source

📂 Project Files
1. Query File → Contains SQL transformation and analysis queries
2. BI File → Power BI dashboard visualization

📌 Key Insight
This project demonstrates how race event data can be transformed into actionable insights for event evaluation and performance monitoring.
Beyond technical analysis, this project focuses on applying business thinking into sports event data.

----------------------------------------------------
[Informal - Only for me]
Hi this is my first data analytic self-project
I looked up for running sports data from kaggle that good to be use
Learning and undestanding by asking AI dan search from google for syntax

MOVE TO MAIN PROJECT TOPICS
What I want to know from the data?
POV if I were the event manager?

1. How was the event going? Is it clear?
2. How was the operational? any challange? 
3. How was the performance of runners/athletes? How good it is?
4. How was the feedback from sponsorship, etc?

What data we have?
Name, Class, BIB, Country, 3.9K (Checkpoint), Chip Time, Finish Time
So what we can analyze is performance.

I want to know the:
1. Overall pace
2. Finish, DNF/DNS
3. Country avg pace
4. Category avg pace

Another data that I want to know?
1. DNF or DNS? Check the Start Time (not exist)
2. Any Fraud? Check 3.9K Checkpoint and Start Time
3. Podium name for 1-3 with every category
Will be conduct next if it wanted to be analyze

Now focus for the performance
You can see the BI file

Need to check how to query?
You can see the query file
