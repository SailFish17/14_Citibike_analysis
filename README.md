# 14_Bikesharing
**Disclaimer:**
*This analysis was prepared for the express use of to fund a bikesharing program in Des Moines IA.  Unintended use of or by anyone else is expressly forbidden under the terms of the NDA executed on Feb 4, 2021.*

## Overview:
This project is an incomplete analysis of the Citibike bike sharing program in NY as an entre to funding a comparable bike sharing program in Des Moines IA.   This is only one part of the analysis that full funding would be based on.   This analysis will cover the program in New York City based on data from August 2019.    


## Results:
The check out duration of bikes was fairly short.   Whilst the graph does not clearly represent the information, most bike rides were under one hour.

Women and Men showed similar behavior in ride duration.  (Please note; Unfortunately,  Tableau Public has been unwilling to accept linkages to this paper, so while there are click thru buttons to the Tableau, all graphs are also reproduced from locally stored .png files stored in the resource directory of this repository.)

![Check Out Time](https://public.tableau.com/profile/phil.fishman#!/vizhome/14_CheckOutDuration/CheckOutDuration?publish=yes)


![Checkout Time](https://github.com/SailFish17/14_Citibike_analysis/blob/main/Resources/Checkout%20Times.png)


The Check out by Gender visualization did not work as well as expected.   The graph should show a variation of the above the data with 2 lines showing the same distribution in time.  However, due to some unknown issue, the following visualization was rendered.

![Check Out by Gender](https://public.tableau.com/profile/phil.fishman#!/vizhome/14_CheckOutbyGender/CheckOutbyGender?publish=yes)

![Check Out by Gender](https://github.com/SailFish17/14_Citibike_analysis/blob/main/Resources/checkout%20by%20gender.png)



Heat maps were used to visualize hourly use over the course of the week.   New York is a commuter town with many transportation modalities available. It is clear from the heat maps that bikes were used to commute to and from work on Monday, Tuesday and Thursday.    Interestingly Wednesday did not show the same commuting pattern as other nights of the week.

![Trips by Weekday per Hour](https://public.tableau.com/profile/phil.fishman#!/vizhome/14_TripsbyWeekdayperHour/TripsbyWeekdayperHour)

![Trips by Weekday per hour](https://github.com/SailFish17/14_Citibike_analysis/blob/main/Resources/weekday%20trips%20per%20hour.png)

Bike use by gender shows where the 2 main groups diverge in bike use.   While men seem to use the bike to get to and mostly from work, women seem to use Citibike mostly on Saturdays during the day.  Showing this may be more a form of entertainment for them rather than a communication modality.

![Weekday Trips by Gender](https://public.tableau.com/profile/phil.fishman#!/vizhome/14_WeekdayTripsbyGender/WeekdayTripsbyGender?publish=yes)


![Weekday Trips by Gender](/Resources/Weeekday trips by gender & Customer type.png)
![Weekday Trips by Gender](https://github.com/SailFish17/14_Citibike_analysis/blob/main/Resources/Weekday%20trips%20by%20gender.png)

The review of Trips by Weekday by Gender shows another dimension that includes differences in spot customer and subscriber use.   Clearly we see several trends within this greyscale chart.  Men’s use on Weekdays is well shown again, and those men are typically subscribers, meaning they rely on this modality and are willing to pay for it as a prefunded transportation option.  Women subscribers show a similar use pattern at a lower volume that correlates with earlier charts on Check out by gender above.  

![Trips by Gender and Customer Type](https://public.tableau.com/profile/phil.fishman#!/vizhome/14_CitiBike_Challenge/TripsbyWeekdaybyGender?publish=yes)

![Trips by Gender and Customer Type](https://github.com/SailFish17/14_Citibike_analysis/blob/main/Resources/Weeekday%20trips%20by%20gender%20%26%20Customer%20type.png)


## Follow up:
Additional data should be reviewed for a complete analysis for funding purposes.   
Additional reviews would include:

- Trip duration by BikeID to show usage stats that would indicate bike wear over the fleet.   
- Point to Point tracking of BikeID would be interesting to show bike movement throughout the city, 
- Top ending locations by time of day to show commuting patterns within the city.

Please note, this analysis would only be one part of a more complete picture detailing use of this system in Des Moines IA and the ability of bike sharing program to work in a city as vastly different as Des Moines is from NYC.

