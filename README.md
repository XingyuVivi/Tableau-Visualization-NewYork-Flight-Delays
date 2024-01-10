# Tableau-Visualization-NewYork-Flight-Delays

## About this project
Welcome to my Tableau dashboards which visualize NYC flight delay patterns in 2013 by differrent dimensions. These dashboards are designed as a practical tool to help users better predict flight departure and arrival delays: users are able to easily interact with the dashboards and vsiualize the average delay time by selecting various parameters, such as their arrival and departure locations, flight times, airlines, and airplane manufacturers.

## Preview of my dashboards
In designing these visualizations, I leveraged my creativity to craft an aesthetically pleasing, intuitive, and diverse tool, with a goal of optimizing user experience and efficiency. The dashboards feature a variety of plot types, including maps, bar plots, and line graphs, each chosen to best represent the underlying data and insights. 

### Delays by geography and carriers:

**Upper Left Map**

The map provides a visual representation of air routes to and from New York City across the United States. It uniquely illustrates the average delay percentages by destination using bubble sizes. Larger bubbles signify a higher average delay percentage at a particular location. Additionally, the color coding offers an immediate understanding of the average delay times: red indicates longer delays, while blue represents shorter ones. This intuitive design allows users to quickly grasp the delay patterns and frequencies associated with different destinations

**Left Lower Bar Plot**

This bar plot compares the average lengths of arrival and departure delays across different carriers. The color gradient of each barin dicates the total number of flights for each carrier. This representation allows for a comprehensive understanding of delay patterns in relation to carrier flight volume.

**Right Bar Plot**

The bar plot on the right side focuses on average delay times categorized by state. This visualization offers a clear geographical perspective, allowing users to identify which states are more prone to delays. By comparing delay times across states, users can gain insights into regional variations in flight punctuality. 

<img width="1212" alt="Screen Shot 2024-01-09 at 4 09 50 PM" src="https://github.com/XingyuVivi/Tableau-Visualization-NewYork-Flight-Delays/assets/113918034/83f654b5-f4fd-49b3-82ff-25fbeb33bcec">

### Delays by manufacturers:

The following bar plot displays flight delay percentages categorized by manufacturers. A dashed line in the middle marks a 25% average delay across all manufacturers. The bar plot is organized in descending order, making it easy for users to identify manufacturers with the highest delay percentages. The color of the bars further distinguishes manufacturers whose delay percentages exceed or fall below the average level.

<img width="992" alt="Screen Shot 2024-01-09 at 10 29 45 PM" src="https://github.com/XingyuVivi/Tableau-Visualization-NewYork-Flight-Delays/assets/113918034/6839e7d6-0fb9-4ded-ab1b-4beef048a186">


### Delays by seasonality:

In this section of the dashboard, we delve into flight delay patterns in relation to different times of the day and days of the year.

The line plot presented here offers a clear depiction of monthly variations in flight delays. A notable observation is that December records the highest percentage of delayed flights in the New York area, at 40.02%, while September experiences the lowest. This trend is likely attributable to the holiday season in December, which typically sees an increase in travel activity. The resultant busier airports and tighter flight schedules can lead to a higher incidence of delays.

<img width="1120" alt="Screen Shot 2024-01-09 at 4 35 00 PM" src="https://github.com/XingyuVivi/Tableau-Visualization-NewYork-Flight-Delays/assets/113918034/17dba923-adb4-41c0-8102-e7921c5c01a7">

When examining flight delays relative to the time of day, a distinct pattern emerges. Our analysis reveals that 11:00 PM (23:00) experiences the longest average arrival delay times, along with the highest frequency of delayed flights. Conversely, the early morning hours, specifically between 5:00 AM and 6:00 AM, are characterized by the shortest and least frequent flight delays. This contrast highlights how flight delay patterns vary significantly over the course of a day, potentially influenced by factors such as air traffic density and operational efficiency at different times.

<img width="1120" alt="Screen Shot 2024-01-09 at 4 35 38 PM" src="https://github.com/XingyuVivi/Tableau-Visualization-NewYork-Flight-Delays/assets/113918034/91ae70f4-a379-4d5a-a70d-d508cbf49871">



### Interact with the dashboards:

The dashboards are designed for interactive exploration, allowing users to select specific destination locations to tailor the displayed data. For instance, in the example below, the selected destination is Oklahoma City, served by Will Rogers World Airport (OKC).

Upon selecting OKC, the bar plots and line graphs in the dashboard adjust to reflect data specific to this location. A notable insight from this tailored view is that July emerges as the month with the highest percentage of delayed flights for flights headed to OKC. Additionally, the data indicates that 7:00 PM (19:00) is the peak time for both the longest delay durations and the highest delay percentages at this airport. These insights provide valuable information about time-specific delay patterns, helping users to better anticipate potential delays when planning their travel to or from OKC

<img width="1126" alt="Screen Shot 2024-01-09 at 4 48 57 PM" src="https://github.com/XingyuVivi/Tableau-Visualization-NewYork-Flight-Delays/assets/113918034/781f4be0-6673-488b-98cc-44c4cb5d518c">

## Load dashboards on your local machine

Interested in exploring these visualizations on your local machine? It's simple! Just download the dataviz_project_v1.twbx file. You can open this file using either Tableau Desktop or Tableau Reader. If you don't have a license for Tableau Desktop, don't worry—Tableau Reader is a free application that allows you to view any Tableau dashboards!


## Next Steps and future improvements

Currently, the data source for this project is public and static, derived from the 2013 NYC flights dataset available at [this GitHub repository](https://github.com/tidyverse/nycflights13). 

Looking ahead, a significant enhancement would be to integrate real-time data into the dashboards. This upgrade would transform the dashboards from a static historical view to a dynamic tool that provides real-time insights into current flight delay patterns. Such a feature would greatly enhance the utility and relevance of the dashboards for users seeking up-to-the-minute information.


