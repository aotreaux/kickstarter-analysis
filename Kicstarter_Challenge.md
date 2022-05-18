# Helping Louise Understand Comparable Data

## Overview of Project

### The purpose of this analysis is to help Louise understand how other theatrical plays fared according to their launch date and fund raising efforts.

## Analysis and Challenges

### To begin, a date conversion was needed for both the launched_at and the deadline columns since these columns contained a string of integers. 
Once completed, we could then extract the year of the launch date by using the year() command in a new column. Now we are ready to build a pivot table to filter out
what is needed to see what the theater outcomes look like by launch month. The results for the successul, failed, and cancelled for all the years could be graphed by using a line chart based on the individual month.

### For the second part of the analysis, we must break down the number of successful, failed, and cancelled plays based on a particular fun raising goal range. 
We then used the COUNTIFS function to count the number of plays that were succesful, failed, and cancelled for that particular monetary range. Once those values were 
determined, the percentages of those values could be calculated based on the total number of successful, failed, and cancelled plays. 

### There were a few challenges that were encountered during these analysis'. First, when making the line graph based on the theater outcome by launch date, the filters 
would carry over to the graph itself and I had to find a way to clear those filters off the graph. Second, for the outcomes based on goals it was important to include the "$" in definying the cells for the COUNTIFS functions that were referenced in Sheet1. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? First, there is a strong rampup of successful outcomes starting in March through May
(this would be the time to launch) followed by an equally step decline from May through September. Secondly, the data for the failed plays followed a similiar path
as the successful but on a smaller magnitude of outcomes.

- What can you conclude about the Outcomes based on Goals? The data lines for the successful and failed plays are the inverse of each other. 

- What are some limitations of this dataset? One limitation is that the dataset is that the staf pick and spotlight columns contain only True and False words which do
not have any meaning. Another limitation is the countries are all abbreviated making it difficult to distinguish country names.

- What are some other possible tables and/or graphs that we could create? Another graph could be outcomes based on average donation. This could be helpful in estimating 
how much each indiviual donation could be based on a given population of an area.
