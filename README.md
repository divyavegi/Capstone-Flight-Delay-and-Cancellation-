# U.S. Flight Delay Analysis
This project analyzes U.S. domestic flight performance in 2024 with a focus on delays, cancellations, and diversions. Using Bureau of Transportation Statistics (BTS) on-time performance data, the analysis uncovers when disruptions are most likely, which airlines and airports are most affected, and what factors contribute most to delays.

The goal is to identify patterns and risk indicators that can help travelers make better decisions and help stakeholders understand operational performance.

## Motivation
With increasing reports of flight delays and cancellations—especially during peak travel periods and adverse weather—air travel disruptions have become a common experience. As someone who enjoys traveling and has personally faced unexpected delays and cancellations, I wanted to explore:
-How often do these disruptions really happen?
-When are they most likely to occur?
-What factors drive delays across the flight network? 

## Key Questions
- How frequently do flight delays, cancellations, and diversions occur?
- When are delays most likely (by month, season, and time of day)?
- Which airlines and airports experience higher disruption rates?
- How severe are delays, and how are they distributed?
- What are the primary causes of delays?
- How do weather-related conditions affect flight outcomes?

## Data Sources
- U.S. Department of Transportation – Bureau of Transportation Statistics  https://www.bts.gov/
- Weather Data Airport-level ASOS / METAR observations

## Data Preparation & Normalization
Combined monthly 2024 BTS on-time performance files into one consolidated dataset (millions of records)
Standardized date and time fields
Created unified flight outcome categories
Separated cancelled and diverted flights from operated flights to avoid skewing delay metrics
Aggregated data by airline, airport, month, season, and departure time block

## Tools & Technologies
- Python 
- Matplotlib & Seaborn 
- Power BI  
- Excel  
- PowerPoint
- Git

## Conclusion
The analysis shows that flight disruptions do not happen evenly across all flights. Some months, seasons, and times of day are more likely to experience delays than others. Airlines also differ in how they manage disruptions, with some experiencing more delays while others cancel flights more often.The analysis shows that operational issues such as late aircraft and congestion are just as important as weather in contributing to delays