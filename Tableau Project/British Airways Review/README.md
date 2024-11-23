## Introduction
This is a project visualising British Airways Customer Reviews and Ratings on various areas.

## Quick Link
[Dashboard](https://public.tableau.com/views/BritishAirwaysReviews_17323955846680/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Scenario
I've been tasked to create a dashboard using Tableau to visualise the data of British Airway Customer Reviews. The dashboard should be dynamic and interactive.

## Process
### Data cleaning
The original dataset needs cleaning. The rating in multiple fields are invalid as the rating should be from 1 to 10. But in the dataset, some ratings are in negative values. Therefore, I use Excel to clean the data, turning negative ratings to positive ratings.

Also, I check if there is any missing values. If there is, I make it as a null value rather than leave it blank. After cleaning the dataset, the next step is to create a dashboard using Tableau.


### Dashboard creating
To start with, I load the datasets into Tableau and create a relationship between two tables. I use 'place' in the review.csv file and 'Country' in the Countries.csv file as a joint between datasets.

To create a interactive dashboard, there are four components: Summary, Map, Month, and Aircraft.

First of all, I create a parameter to show the metric of the reviews. Then I create a calculated field to show the average metric selected. After that, I add the rest of the filters. From there, the Map element is completed.

Second, I create a summary banner showing the average overall rating, average cabin staff service score, average entertainment score, average food beverages score, average ground service score, average seat comfort score, average value for money score.

Third, I creat a line graph showing the average metric selected by Month. Lastly, I create a dual bar graph to show the average metric by aircraft and number of reviews.

After finishing all the elements, the rest is to put all elements together and design the dashboard making it easy to read and appealing to watch.

## Conclusion
The dashboard of British Airways Reviews is a good example of my skills and ability using Tableau to analyse data and create visuals. 
