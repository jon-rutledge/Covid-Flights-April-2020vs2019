# Flight Data Explorative Analysis - Coronavirus

## Dataset

The interface on the Bureau of Transportation and Statistics allows for users to manually download sets of flight data from its [website](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236).  For this analysis we will be sticking with 2 months worth of data, specifically the periods of **April 2019** and **April 2020**.  I wish to see if there are any significant trends in Airline usage or performance during the Cronovirus pandemic.

This dataset is a single table that is composed of individual flight statistics reported to the Bureau of Transportation of the United States.  This includes attributes such as time of take of and landing, point of origin, delay, etc.

Structure is 925,405 observations with 35 separate attributes.  1 extra column will be removed as it is unnamed.  There are many numeric based values related to time or duration.  There are also categorical values related to identifiying point of origin, destination, flight, and carrier.

More details on columns and their values can be found [HERE](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236)

## Summary of Findings

It appears the outbreak of coronavirus and the global pandemic has reduced flight count around the United States when comparing April 2019 to April 2020.

However, since the amount of airport infrastructure has not decreased, the overall number of resources available to each flight on average has increased.  Because of this, delays are occurring less frequently than they did previously.  The distribution of these delays is the same though.


## Plots

Flight Count in April 2019 vs 2020
States Flight Count
Change in Departure Delays
Departure Delays per Day of the Week at SFO