# **Overview of NY Citi Bike Analysis**
For this analysis, we reviewed New York City Citi Bike data to inform the creation of a bike ride-sharing program in Des Moines. Using data pulled from Citi Bike System Data, we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we created a set of visualizations to show the following information:

* **Length of time that bikes are checked out for all riders and genders**
* **Number of bike trips for all riders and genders for each hour of each day of the week**
* **Number of bike trips for each type of user and gender for each day of the week**

**Results**
[Top Starting Stations](https://public.tableau.com/app/profile/pa.lor/viz/TopStartingStations_16486124235240/TopStartingStations)
###### *Top stations where bikes are checked out by users.*
![](Resources/Checkout%20Times%20for%20Users.png)

[Top Ending Stations](https://public.tableau.com/app/profile/pa.lor/viz/TopEndingStations/TopEndingStations)
###### *Top stations where bikes are returned to by users.*
![](Resources/Top%20Ending%20Stations.png)

[Checkout Times for Users](https://public.tableau.com/app/profile/pa.lor/viz/CheckoutTimesforUsers_16486112912370/CheckoutTimesforUsers)
###### *Bike check out times for all users.*
![](Resources/Checkout%20Times%20for%20Users.png)

[Checkout Times by Gender](https://public.tableau.com/app/profile/pa.lor/viz/CheckoutTimesforUsers_16486112912370/CheckoutTimesbyGender?publish=yes)
###### *Bike check out times by gender.*
![](Resources/Checkout%20Times%20by%20Gender.png)

[Trips by Weekday per Hour](https://public.tableau.com/app/profile/pa.lor/viz/TripsbyWeekdayperHour_16486116101220/TripsbyWeekdayperHour)
###### *Heat map of trips by weekday per hour of day.*
![](Resources/Trips%20by%20Weekday%20per%20Hour.png)

[Trips by Gender by Weekday per Hour](https://public.tableau.com/app/profile/pa.lor/viz/TripsbyGenderWeekdayperHour_16486117571900/TripsbyGenderWeekdayperHour)
###### *Heat map of trips by weekday per hour of day broken down by gender.*
![](Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

[Trips by Gender by Weekday](https://public.tableau.com/app/profile/pa.lor/viz/CitiBikeChallenge_16486105928040/TripsbyGenderbyWeekday)
###### *Heat map of trips by weekday broken down by gender.*
![](Resources/Trips%20by%20Gender%20by%20Weekday.png)

**[Link to NYC Citi Bike User Story](https://public.tableau.com/app/profile/pa.lor/viz/NYCCitiBikeUserStory/NYCCitiBikeUserStory?publish=yes)**

**Summary**

The results we can draw from our analysis and visualizations are:
* **Most trips last less than 1 hour**
* **Men check out more bikes than women and are more likely to be subscribers**
* **Men make more trips than women, with the heaviest use before and after work hours (7am - 9am and 5pm - 7pm)**
* **Bike use on weekends are heaviest during the day (9am - 4pm) whereas weekday bike use is heaviest during the hours before and after work (8am - 9am and 5pm - 6pm)**
* **Subscribers make more trips and are frequent users of bike ride sharing compared to non-subscribers**

Two additional analysis and visualizations to review could be looking at a heatmap of age breakdown of subscribers and starting and ending locations by gender.
