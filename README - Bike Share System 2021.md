# Exploring the Bike-Sharing Systems (San Fransico Bay Area & Chicago) - 2021

## by Folasade Adeyanju

## Dataset

The Datasets used consist of information regarding bike sharing systems for two different companies located in different cities.
>- Baywheels Bike Sharing System in San Francisco Bay Area
>- Divvy Bike Sharing system in Chicago.
The Datasets consist of multiple csv zipfiles (one per month) and can be found in the system data repository for both bike sharing systems;
>- Baywheels files can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data),
>- Divvy files can be found [here](https://ride.divvybikes.com/system-data)

The Datasetes were downloaded programmatically seperately into 2 folders. All the zipped csv files were then unzipped and read into two dataframes. Each dataset was explored visually and programmatically to clean up and tidy the structural integrity and contents of the datasets. Null values, incorrect datatypes, incorrect values and additional information were all taken care of in the Data Cleaning steps.


## Summary of Findings

I observed that, the Divvy dataset had a lot more bike trips in the year 2021 than the Baywheels bike sharing system.
This however did not necessarily mean a clear difference in patterns and trends between the two systems. The high record of bike trips observed in the Divvy dataset is not surprising as Chicago is known to be the third-most populous city in the United States following New York and Los Angeles and as such may be a contributing factor to the high record of bike trips in the area. 

An interesting observation upon comparison of both datasets is that for most of the explorations done on the two datasets, the similarities between trends observed between the Divvy Bike sharing system and Baywheels Bike sharing system are profound. As seen in both datasets and there are more casual customers than members in both datasets. 
However in terms of most preferred bike type, most bike trips are embarked on using **electric bikes** in Baywheels Bike share system while for Divvy Bike share system, most bike trips are embarked on with **classic bikes**.

In addition, looking at the frequency of trips in both datasets by week-days and months; most trips are embarked on during the weekends and in the spring/summer time. Also, the most bike trips are taken at 5pm, 6pm and 4pm in both datasets. All of these observations are relatable and might suggest that bike trips might be used for a more recreational purpose (although this is not conclusive)

I was also interested in exploring the correlation between the distance covered and duration, however, upon exploration I found that there was a very weak relationship between the Distance covered and Duration of bike trips. The bike type seem to be a factor that influences the bike trips, we could see some type of relationships between Number of bike trips and bike types. Most of the trips are taken in Baywheels bike share system use the electric bike type while the classic bikes are the most used fo Divvy bike share system. This suggests that there are features of these bike types that may influence bike trips.


## Key Insights for Presentation

In the Presentation, I focused on comparing the two datasets based on a few variables. This is to establish the similarities and differences between bike trips in the Divvy Biskeshare system of Chicago and Baywheels Bikeshare system of San Francisco Bay Area. I start by introducing the two datasets comparing the number of bike trips taken in the year 2021.
Following this, I introduce the duration and distance variables comparing their distributions for both bikeshare systems. I then use multiple barcharts to introduce some of the other variables such as weekdays, hours and bike type. The aim was to show if both bikeshare systems share any similarities or differences across these variables. Finally, I use a scatter plot to determine if there is a relationship or correlation between the distance in km and duration in seconds for both bike share systems.
