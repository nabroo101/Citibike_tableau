# New York Citi Bike Analysis

This project is an analysis of the New York Citi Bike program, the largest bike-sharing program in the United States. Since 2013, the Citi Bike program has been collecting data on the program's utilization and each month, bike data is organized and made public on the Citi Bike Data webpage.

## Project Overview

This project focuses on generating regular reports for city officials looking to publicize and improve the Citi Bike program. This analysis aims to answer the following questions:

- How many trips have been recorded in total during the chosen period?
- By what percentage has total ridership grown?
- How have the proportions of short-term customers and annual subscribers changed?
- What are the peak hours when bikes are used during the summer months?
- What are the peak hours when bikes are used during the winter months?
- Today, what are the top 10 stations in the city for starting a journey? 
- Today, what are the top 10 stations in the city for ending a journey? 
- Today, what are the bottom 10 stations in the city for starting a journey? 
- Today, what are the bottom 10 stations in the city for ending a journey? 
- How does the average trip duration change by the type of user? 
- What is the average distance in miles for a bike trip?
- Which bikes (by ID) are most likely due for repair or inspection in the timespan?
- How variable is the utilization by bike ID?

The final report will contain dashboards and visualizations to answer these questions, along with additional analysis for the observed data phenomena. 

## Files

Data for this project is obtained from the [Citi Bike Data](https://www.citibikenyc.com/system-data) source. citibikes data from 4/2019 - 11/2019 . i used pandas to concatnate and take a sample fir memory porposes.

## Tools

This project utilizes [Tableau Public](https://public.tableau.com/en-us/s/gallery) for data visualization and reporting. however , i had access to Tableau desktop so i was able to save my files localy.


### Total Trips

During the chosen period, a total of 3,270,010 trips were recorded. This considerable figure demonstrates the importance and utilization of the bike-sharing program in New York City.

### Ridership Growth

To analyze ridership growth, we examined data from April 2019 to November 2019.

In April 2019, a total of 353,235 trips were recorded, which grew to 488,743 trips in September 2019. This is a growth of approximately 38.37%.

Following this peak, there was a drop in rides recorded right before Christmas in November 2019, with 295,273 trips. This is a decrease of approximately 39.64% compared to September 2019.

### Customer vs Subscriber Ridership Changes

A more granular analysis was conducted to understand how the proportions of short-term customers and annual subscribers changed over the period.

In April 2019, customer trips accounted for 45,814, while subscriber trips were 307,402. By November 2019, these figures changed to 30,428 for customers and 265,325 for subscribers.

This indicates a drop of approximately 33.58% for customers and a drop of around 13.7% for subscribers from April 2019 to November 2019.

The percentage change has been calculated using the formula:

```
Percentage Change = (New Value - Old Value) / |Old Value| * 100%
```

The decrease in both categories suggests an overall drop in ridership during the colder months, which is consistent with expectations considering the weather conditions. 

we can also notice the percentage drop for subscribers is lower than the percentage drop for customers . which means most of the subscribers are a newyork residents . which means they ride for living not like customers as a liesure. 
## Peak Hours of Bike Usage

After visualizing the number of trips per hour of the day, we observed specific patterns in the bike usage times. These peak times align with common commuting hours, suggesting that the bike sharing program is heavily utilized for daily commuting.

### Morning Peak Hours

The data shows that the busiest time in the morning is between 7 AM - 10 AM. The highest usage within this period is at 8 AM, with a total of 131,384 trips. This time coincides with common working hours' start times, indicating the bikes are being used for commuting to work.

### Evening Peak Hours

In the evening, the usage again peaks around the typical end of the workday. Between 4 PM - 7 PM, there is a significant increase in the number of trips. At 5 PM, the number of trips reaches its highest point for the day, with a total of 176,496 trips.

These patterns highlight the critical role the bike-sharing program plays in the city's daily commute. Understanding these patterns can help in managing and allocating resources effectively during peak usage times.

This updated README file will serve as an overall guide and summary of the findings in the New York Citi Bike analysis project.
