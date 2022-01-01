# Surfs_Up

## Overview & Objectives

Climate information can be beneficial in helping to determine the suitability of new businesses to a location. Specifically, information such as temperature and precipation trends and patterns over a period of time can be an influencial factor in determining if a specific business, such as a surf shop, is right for a specific geographical location. 

Provided with data collected by several weather stations and stored in a flat database file(hawaii.sqlite), the objective of this project was to extract and analyze the temperature data for the months of June and December in Oahu, Hawaii, to determine if a surf and ice cream shop business is sustainable year-round based on the weather.

## Tools and Resources

* Python 3.7, Jupyter Notebook 6.4.6, VS Code 1.63.2
* SQLAlchemy 


## Results

Table 1 and 2 below provides a comparison of the statistical analysis computed in Jupyter notebook for the temperature in June and December.


The major observations that can be made from the analyzed results are:

* The temperature in June is generally higher in June than in December; June temperature varies from a minimum of 64 to a maximum of 85 Farenheight, while the temperature in December varies from 56 to 83 Farenheight. 
* Although there is generally a higher temperatures in June than in December, the difference is not significant with June and December having an average temperature of 74.9 and 71.0 Farenheight, respectively.
* With a standard deviation of 3.75 in December compared to 3.25 in June, one can say the temperature in December is slight more dispersed than in June. In other words, the June temperature is slightly more consistent and less dispersed from the mean.


## Summary

The information analyzed indicates that the location is suitable to set up a surf shop based on weather data. Figure 1 below shows a box plot comparison of the June and December temperatures, the most anticapted tourist months. As can be observed, generally there isn't a significant variation in the temperatures for these months. The green markers on the figure indicates the average temperature for June and December the year 2010 to 2017.



In addition to the temperature, the monthly rainfall is very important in determining the suitability of the site. Figure 2 below compares the monthly total rainfall for both June and December from 2010 to 2016. As with the temperature, there isn't a noteworthy significant difference in the two months rainfall totals with one exception. In December 2010, the rainfall was surprisingly very high compared to other years. This could be just a one off anomaly due to the unpredictabily of weather or other reasons for example, faulty equipment. But based on the data avaiable, this high amount of rainfall is not within the normal and thus the location is still suitable to set up shop. 

Let's Get To Surfing!!!