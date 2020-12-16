# Surfs Up!

## Overview 
In the pursuit of opening a Surf and Ice cream shop in Oahu, Hawaii, it is imperative to understand the weather on the island year-round. Bad weather means bad business.

### Introduction 
To get a better understanding of weather patterns on the island of Oahu, this analysis presents a comparative look at the weather on Oahu in June and December of 2017 using Python, Pandas, and SQLAlchemy.

## Results

### June Temperatures

![image](https://github.com/juberr/surfs-up/blob/main/Resources/June.png?raw=true)

* The mean temperature on Oahu in June was about 75 degrees fahrenheit with a minimum of 64. 

* With a standard deviation of about 3 degrees fahrenheit, it appears that for temperatures in June on Oahu one can expect many days of appropriate weather for surfing and ice cream!


### December Temperatures

![image](https://github.com/juberr/surfs-up/blob/main/Resources/Dec.png?raw=true)

* The mean temperature on Oahu in December was about 71 degrees which is 4 degrees less than June, but still relatively warm.

*  The minimum temperature drops to 56 degrees in December. This drastic drop in the minimum temperature when compared to June suggests that the business should expect demand to be slower in December.

* With a standard deviation of about 4 degrees, temperatures in December can still be expected to serve up days of surfing and ice cream, but not to the extent and consistency of temperatures in June! 

## Summary 

Temperatures in June and December  on the Island of Oahu both appear to offer a healthy environment for the Surf and Ice Cream shop to thrive year-round. While there is a dip in temperatures for December, it wouldn't be severe enough to halt business alone. 

### More Queries to Consider

An important query to consider on the health of the Surf and Ice cream shop is precipitation levels in June and December. While the temperatures could be appropriate for surfing and ice cream in June and December, rainy conditions will keep people inside and away from the Surf and Ice cream shop.

![image](https://github.com/juberr/surfs-up/blob/main/Resources/june%20prcp.png?raw=true) 
![image](https://github.com/juberr/surfs-up/blob/main/Resources/dec%20prcp.png?raw=true)

Following the trend of December being a worse month for business, December has the higher average and maximum precipitation levels in Oahu when compared to June. This means one can expect a lot more rainfall in December on Oahu, which disincentivizes individuals from wanting to go surfing or eat ice cream. The disparity in precipitation could have an averse affect on business in December.


Another query to consider would be a "by station" view of the June and December data. Knowing which weather stations are more aversely affected by the changes in weather, can inform the business where they should specifically set up shop on Oahu to optimize the chances of success.

![image](https://github.com/juberr/surfs-up/blob/main/Resources/june%20grpby.png?raw=true)
![image](https://github.com/juberr/surfs-up/blob/main/Resources/dec%20grpby.png?raw=true)

It looks like our data is not specific enough for this query as all stations have the same average in June and December. Should the business want to explore this question further, they should look into other data sources to supplement the current database.

