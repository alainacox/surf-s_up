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

As you can see the result are for June and December. Choosing a month that is in the summer and in the winter you can see the differnce that tthe emperature makes. The precipitation in June as you see from the anaylsis is higher than it is in the winter the high the temperature the water in the air seems to be higher.

## Summary

In June you can see that there are multiple dates that have the same level in preciptiation. As you can see from the additonal queries that the levels faulactes. But you can see the maximum level didn't go above 60 and the mimuimum didn't go below 30.
