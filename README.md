# Surfs_Up

## Overview & Objectives

Climate information can be beneficial in helping to determine the suitability of new businesses to a location. Specifically, information such as temperature and precipation trends and patterns over a period of time can be an influencial factor in determining if a specific business, such as a surf shop, is right for a specific geographical location. 

Provided with data collected by several weather stations and stored in a flat database file (hawaii.sqlite), the objective of this project was to extract and analyze the temperature data for the months of June and December in Oahu, Hawaii, to determine if a surf and ice cream shop business is sustainable year-round based on the weather.

## Tools and Resources

* Python 3.7, Jupyter Notebook 6.4.6, VS Code 1.63.2
* SQLAlchemy 


## Results

Table 1 and 2 below provides a comparison of the statistical analysis computed in Jupyter notebook for the temperature in June and December.

Table 1 Statistical temperature results for the month of June

<img width="138" alt="june temp" src="https://user-images.githubusercontent.com/92636438/147856665-651a8cf3-60e8-41c0-a760-27af77f95e7e.png">



Table 2 Statistical temperature results for the month of December

<img width="141" alt="dec temp" src="https://user-images.githubusercontent.com/92636438/147856734-7374ade7-632b-436c-87b4-b953db61ac7f.png">


The major observations that can be made from the analyzed results are:

* The temperature in June is generally higher than in December; June temperature varies from a minimum of 64 to a maximum of 85 Farenheight, while the temperature in December varies from 56 to 83 Farenheight. 
* Although there is generally a higher temperatures in June than in December, the difference is not significant with June and December having an average temperature of 74.9 and 71.0 Farenheight, respectively.
* With a standard deviation of 3.75 in December compared to 3.25 in June, one can say the temperature in December is slight more dispersed than in June. In other words, the June temperature is slightly more consistent and less dispersed from the mean.


## Summary

The information analyzed indicates that the location is suitable to set up a surf shop based on weather data. The temperature is generally hot during the months of June and December temperatures, the most anticapted tourist months. In addition, as can be observed from the box plot presented in Figure 1 below, generally there isn't a significant variation in the temperatures for these months, although June temperature is slighly more steady (less dispersed) than December temperature as mentioned above. The green markers on the figure indicates the average temperature for June and December from the year 2010 to 2016.

Figure 1

<img width="538" alt="Temp box plot" src="https://user-images.githubusercontent.com/92636438/147856819-ab8ad6d4-b3dd-4174-ad8e-659faac2d321.png">


In addition to the temperature, the monthly rainfall is very important in determining the suitability of the site. Figure 2 below compares the monthly total rainfall for both June and December from 2010 to 2016. As with the temperature, there isn't a noteworthy significant difference in the two months rainfall totals with one exception. In December 2010, the rainfall was surprisingly very high compared to other years. This could be just a one off anomaly due to the unpredictabily of weather or other reasons for example, faulty equipment. But based on the data avaiable, this high amount of rainfall is not within the normal and thus the location is still suitable to set up shop. 

Figure 2

<img width="338" alt="Total rainfall" src="https://user-images.githubusercontent.com/92636438/147856874-69a33193-2ddb-422d-9549-c46c3cabf09a.png">


Let's Get To Surfing!!!
