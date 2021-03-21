# Module 14 | Assignment
# NYC Citi Bike - Des Moines

Analyzing NYC Citi Bike-Sharing data using Tableau.

# Lets Ride

Module 14 Citibank Bikes
Using Tableau, Panda, Jupyter

![bikeclipart](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/bikeclipart.png)

Tableau Story, NYC Bike Rental Details for the August 2019. [NYC Bike Rental Details, Click Here](https://public.tableau.com/profile/jimmy.jordan#!/vizhome/UpdatedChallengeModule14/NYCBikeDetails?publish=yes)

## Overview and Parameters

In this module we are asked to build a dynamic story for starting a bike-sharing business in Des Moines. We will use captured data from a New York City bike-sharing company to provide key stakeholders with analysis data.

## Results:
New York City bike sharing data from August 2019 visualized. 


![Checkouttimesforusers](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/checkouttimesforusers.png)  Duration of Checkout Times for Users; over 140K units had a trip duration that exceeded 5 minutes. 

![CheckouttimesbyGenders](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/CheckouttimesbyGenders.png) Duration of utilization by Gender, Male utilization is 3 times greater than female. 

![BreakdownofRiders](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/BreakdownofRiders.png) Gender Breakdown of Riders, Male riders out number female riders by a 3to1 ratio. 

![WeekdayHours](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/WeekdayHours.png) Weekday Hours, Examining the HeatMap 5pm to 6pm is the most utilized time slot for renting bikes. 

![PopularDaystoRent](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/PopularDaystoRent.png) Weekdays, The most popular days to rent are Thursday and Friday. 

![Count](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/Count.png) Count, Using the HeatMap 7AM to 8AM and 5PM to 6PM accounts for the largest numbers or rental durning the Weekday.

![BikeID](https://github.com/JimmyJ-D/BikeSharing/blob/main/images/BikeID.png) Bike ID utilization, The Bike ID Utilization spot grid is a useful map to help manage asset location. 


## Summary:
Des Monies and New York City share many similar patterns, especially with weather. With a bike sharing business weather will be a key factory. For the month of August, both cities share a near identical average temperatures; Des Moines 84/63 and New York City 83/68. Additionally, both cities averages only 9 rainy days for the month of August. https://www.bestplaces.net/climate/?c1=51921000&c2=53651000

The current dataset could provide two additionally decision points by using the lat/long from the dataframe.  I would use the lat/long to overlay the locations against current tourist points of interest. By using the current point of interests you could capitalized on established traffic patterns.  Additionally, using the start and stop lat/long and Bike ID I would track each ID for total distance travel to adjust inventory locations and develop a preventative maintenance plan for bikes.
