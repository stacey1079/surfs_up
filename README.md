# Surfs_Up Module 9 Challenge
## Overview of the Analysis
This analysis was done in order to give W. Avy more information regarding temperature trends in Oahu before he made a final decision on where to open his surf shop.  He wanted the temperature trends for the months of June, and Dec from each of the stations.  In order to do that I queried the Hawaii.sqlite database to filter out the dates and the temperature recordings for each date from all of the June recordings, and then from all of the December recordings.  I created a list from the june temperatures, and then put those into a DataFrame and then used .describe() to get the statistics for June.  I then did the same with December.
## Results
These are the .describe() statistics for the June months:
![Surfs_up_June](https://user-images.githubusercontent.com/45715246/213934838-0d2344b8-2702-45e0-ae03-3d6f183b0099.png)




These are the .describe() statistics for the December months:
![dec_stats_surfs_up](https://user-images.githubusercontent.com/45715246/213934851-52c9f3b9-54a7-408d-b344-07efa84666df.png)
### Three key differences between June and December statistics:
* There were 1700 measurements taken throughout the January months, and only 1517 in the December months.  That means there were 183 more measurements taken in the June months which gives considerably more data towards the statistics.
* The lowest temp for June is 64 where the low for December is 56.
* When rounded, the average temperature for June is 75 and the average temperature for December is 71.  Which is only the difference of a few degrees.  

## Summary
Overall, I don't see too big of a temperature difference between the June months, and the December months which means this would be a good surf/ice cream location for the entire year.  It doesn't seem to me that there would be any months that would be slow due to colder temperatures.  All year round the shop should have great business!

One additional query that I think would be helpful is to separate the locations and temperatures to find the exact locations with the best temperature.

Another query that I think would be helpful is to query the lowest temperatures of all measurements in ascending order to see the coldest locations.  Those would be the worst locations to put the shop. 
