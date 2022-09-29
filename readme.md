# (Ford GoBike System Explanatory Data Analysis(EDA)
## by (Hany Osman)


## Dataset

> Ford Go-Bike dataset created by a bike-sharing system covering the greater San Francisco Bay area for February of 2019, contains information about individual bike ridder like duration (sec) of trips, member information, station information.
>
>The raw dataset contains 183412 rows(trips or observations) and 16 columns(features)
>
>As the data was not tidy and has a poor structure, most of the variables were cleaned, engineered, and converted several variables to a correct datatype.
>
>The final dataset after applying data Wrangling contains 174952 rows and 15 columns. Data type in columns included 2 are numerical, 2 are datetime,1 is boolean, 1 is category, and 9 are object type.



## Summary of Findings

> I observed that though the number of trips duration (sec) is higher in percentage for male for female and other gender, also other gender has a peak at nearly the age of 55 years for the higher duration(sec).

>Relation between Duration (sec) of Bike Trips and Age is an inverse relationship between both variables. As duration(sec) decreased, age increases. The most frequent bike riders have ages between 20 and 45( youth members). Youth members (between 20 and 45) achieved higher trips duration

>During all days of week the median of trip duration_sec for customer user type is higher than that for subscriber user type.Customer Users have high trip duration than Subscriber.

>Other gender >female >male in Ave. Duration (sec) in weekends rather than weekdays.

>Subscribers mainly hire a bike during weekdays, but a significantly higher trip duration during weekend days by Customers.

>During all days of week the median of trip duration_sec for customer user type is higher than that for subscriber user type.Customer Users have high trip duration than Subscriber.

>Sunday and Thursday have the most bikers than other days of week. Thursday 2 AM has the most trip duration(sec).

>the duration of biking is longer, for customer user @ 2 AM and 3 AM, than any hour and than subscriber user.The duration of biking is longer than any hour for subscriber user@ 2 AM, 3 AM .

A bike ridding is very popular among subscriber user rather than customer user which may point to special ponus or free rides for user subscribed in bike share system.

>It is appeared that Bike with id above 4000 is frequent used.


## Key Insights for Presentation

> >Distribution of bike trip duration (sec),
>
>Distribution of  age,
>
>Distribution of member gender and user type,
>
>The trrafic distribution per  hour of the day and per day ofthe weeks,
>
>Distribution of Bike Trip per  start_day of the week and start_hour of the day.
>
>Distribution of Bike Trip per start station name and end station name.
>
>Effect of bike trip duration(sec) by  age, start hour, days of the week ,member gender and user type,
>
>Distribution of bike share for all trip