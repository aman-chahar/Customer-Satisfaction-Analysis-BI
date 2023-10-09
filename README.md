# CALL CENTRE Data Analysis with Power BI
#### Dashboard 
https://www.novypro.com/project/call-centre-performance-report-2

This project focuses on analyzing the CALL CENTRE dataset and creating insightful reports using Microsoft Power BI. We will follow a structured approach to understand the data, prepare it for analysis, and generate interactive insights as per the company's requirements.

## Dataset Overview
#### The dataset consists of the following columns:

CALLER ID: Unique identification number for each caller.
AGENT: Name of each agent.
DATE: Date when each call was received.
TIME: Time of day in hh:mm:ss format for each call.
TOPIC: The subject or topic of the calls received.
ANSWERED: Indicates whether the call was received (Y/N).
RESOLVED: Indicates if the call was resolved (Y/N).
SPEED OF ANSWER IN SECONDS: Duration in seconds for each call to be answered.
AVG. TALK DURATION: Average duration of each call for a specific agent.
SATISFACTION RATE: Rating of each agent based on caller satisfaction.

## Data Preparation Steps
#### Before proceeding with analysis, follow these steps:

Replace all null or blank values with 0.
Adjust data types as necessary to ensure accurate analysis.
Extract seconds and minutes from the "AVG. TALK DURATION" column, and create a new column named "Duration on Calls" (change the data type accordingly).
Analysis and Reporting

#### To meet the client's requirements, we will perform the following tasks:

Calculate the total number of calls.

Create new columns to calculate the total number of answered and rejected calls.

Calculate the percentage of calls answered and rejected.

Create a new column to count resolved calls.

Create a new column to count unresolved calls.

Identify the top agent who answered the maximum number of calls.

Identify the top agent with the highest satisfaction rate.

Use charts to display the total number of calls by topic.

Analyze the duration of calls by each agent.

Calculate the total calls by days and months for the year 2021.

Use slicers for interactive filtering by month and day.

Provide overall performance ratings for 2021.

Use custom charts to visualize overall 2021 performance satisfaction ratings.
