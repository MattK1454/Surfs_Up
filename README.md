# Surfs Up Oahu Surf & Ice cream shop climate analysis project
Data modelling project using python, sqlite, and jupyter notebooks

## Overview

In order to expand our understanding of the overall climate variance and weather conditions for our ice cream and surf shop, we collected all of the temperature readings in the month most commonly associated with Summer seasonal weather and the temperature readings in the month most commonly associated with Winter seasonal weather: June and December respectively.

## Results

![June temperature stats](https://github.com/MattK1454/Surfs_Up/blob/main/June_temp_stats.png)

Above is a statistical analysis of the June temperature readings for Oahu.

![December temperature stats](https://github.com/MattK1454/Surfs_Up/blob/main/December_temp_stats.png)

Above is a statistical analysis of the December temperature readings for Oahu.

Looking at the above statistical anaysis, 3 points regarding the two months should be addressed:

* The June temperatures analysis was conducted on 1700 samples where as Decembers data contains 1517 sample points. This suggests that June's statistical analysis will be more accurate.
* The average temperature in June was 74.94 degrees Fahrenheit where as December's average temperature was 71.04 degrees Fahrenheit. This is a difference of 3.9 degress F in average temperture over the year.
* The largest difference between the two months can be found in the measure of the minimum temperature. In June, Oahu's minimum temperature was recorded to be 64 degrees F. In December, Oahu's minimum temperature was recorded to be 56 degrees F. This difference of 8 degrees represents the largest swing in temperature between the two months.

## Summary

Analyzing the two months shows the average temperature for Oahu stays relatively the same throughout the year. The maximum temperatures recorded also seem to be within one standard deviation of each other suggesting it is reasonable to expect the maximum temperature to reach between 83 and 85 degrees F at any point in the year. The largest difference in temperature was found in the recordings for the minimum temperature. With December recording 56 degrees F as a minimum and June recording 64 degrees F as a minumum, it is reasonable to expect that there will be less surf and ice cream sales in December on the days where the temperature drops the lowest.

However, it may be beneficial to perform at least two more data parsing searches for a better understanding of where the optimal location for the surf and ice cream shop would be:
1. A query that isolated exactly what station on the island recorded what temperatures on what days might allow for the selection of a shop location where the temperature remained closer to the average temperature for the entire island throughout the year.
2. It may be of some benefit to query the precipitation data for each station as well as the temperature that station recorded in June and December to determine the likelihood of having warmer weather with rainfall vs. colder weather with rainfall and how that realates to possible shop locations.
