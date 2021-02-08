# surfs_up
Columbia Data Science Module 9


## Overview

This analysis uses Python and SQLAlchemy to query a SQLite file containing weather data for the island of Oahu. I analyzed the 2010-2017 weather data with the aim of understanding how best to build a surfshack business. This analysis contains two parts. First, I determined the temperatures we can expect on Oahu in June. Second, I ran the same analysis for the month of December. 

## Results

June

December 


* There are not significant differences between June weather and December weather. 
This is unsurprising, given Hawaii's tropical climate. But, this helps confirm our intuition that having our surfshack open year round will not face many problems from uncooperative weather. The mean June temperature is roughly 75 degrees and the mean December temperature is a balmy 71. 

* The minimum temperature is lower in December. 
The minimum temperature in June was 64 degrees compared to the minimum temperature in December, which was 56 degrees. While 56 degrees isn't exactly skiing weather, it may be cool enough to deter some people on the coldest days of the year. This may inform our decision to close the shop briefly during the part of the year when the coldest temperatures are likely to occur. We may also decide to close the shop at an earlier time in the day during the winter before colder nighttime temperatures drive customers away from the beach. 

* The weather is equally consistent in June and December. 
The standard deviation of temperatures is 3.26 in June and 3.75 in December. If certain times of the year had temperatures with higher standard deviations (i.e. more variable weather) that could influence our decision to shut down at times of unpredictable weather. However, the weather has a similar variability throughout the year. 50% of temperatures in June are between 73 and 77 degrees, while 50% of the temperatures in December are between 69 and 74 degrees. 
