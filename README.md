# Surf's Up!!!

## Overview of the analysis

I used Python and SQLAlchemy to do basic climate analysis and data exploration of my climate database. All of the following analysis was completed using SQLAlchemy ORM queries, Pandas, and Matplotlib. I used these functions to filter the date and measurements of precipitation. Here is what I did to anaylze the infomation given to me:
* Designed a query to retrieve the last 12 months of precipitation data.

* Selected only the date and precipitation values.

* Converted the query results into a Pandas DataFrame and set the index to the date column.

* Sorted the DataFrame values by date.

* Ploted the results using the DataFrame plot method.

* Used Pandas to print the summary statistics for the precipitation data.

## Results
June Summary Results

![](https://github.com/alainacox/surf-s_up/blob/main/June%20Summary.png)

December Summary Results

![](https://github.com/alainacox/surf-s_up/blob/main/December%20Summary.png)

* As you can see that the differnce in temperature is slightly higher in June than in December
* The count in s high in June than in December
* There is only a 2 degrees in between June and December maximum and a 8 degree between the minimum

## Summary

You can see that there are multiple dates that have the same temperature. As you can see from the additonal queries that the average temperatures for June and December fall in the 70 degree range. The temperature maximum maybe higher in June because the count is by 183 dates. With that being shown that may be way June is higher in all because it had a larger data set.
