# bikesharing

## Overview of the analysis

This is my link to my Tableau story. [[Link]](https://public.tableau.com/app/profile/eric.cheuk.him.ng/viz/Module_14_challenge_16541184852790/Storyforanalysis)

The purpose of the project is that We want to convince investors that a bike-sharing program in New York City is a solid business proposal. We performed some analysis on the bike trip for August 2019.

First of all We converted the trip duration to datetime format from Integer, and created a new csv file through Jupyter notebook for further analysis in Tableau.

We created five charts for the analysis: line Chart of Checkout Times for Users, a line chart of Checkout Times by Gender, Trips by Weekday for Each Hour in heat map, Trips by Gender in heat map, and User Trips by Gender by weekday in heat map.

Having the visualization, it provides better understanding of the relationship between the variables and the details of the data so we can pitch the report to investors

## Result

![checkout_user](https://user-images.githubusercontent.com/100378319/171763221-0f2d9bca-5096-4360-b468-dde828f4fa7d.png)

1. The picture above is the checkout times for user. We can tell from the chart averagely the trip duration for most of the user is about 5 minutes.


![checkout_gender](https://user-images.githubusercontent.com/100378319/171763231-7fcff93f-5553-49be-8097-3eea57b8596f.png)

2. This is the checkout time by gender. Although the counts of male are much higher than Female user, their checkout time are basically the same which is about 5 minutes.


![trsps_weekday](https://user-images.githubusercontent.com/100378319/171763243-fd714344-5088-45a6-857b-4bdeca5fe4e5.png)

3. This is a heat map showing count of trips based on day and hour. We can tell most of the usage are on the weekday 8am to 9am and 5pm to 6pm as expected because this is the rush hour.


![trip_gender](https://user-images.githubusercontent.com/100378319/171763252-1780767a-84cb-4bb7-9ef7-b5157d6daa82.png)

4. This is a similar heat map as previous chart, but it is filtered by gender. We can see most of the user are male and the busiest time is similar to previous chart which are 8am and 5pm.


![trip_gender_weekday](https://user-images.githubusercontent.com/100378319/171763267-a5086f1d-f29b-4008-96bd-89a475be4bc2.png)

5. This is a heat map chart showing relationship between user type and gender based on weekday. We can see the male subscriber are the main user type.


![gender](https://user-images.githubusercontent.com/100378319/171763285-80e21107-01ae-4f1e-86f4-f482f500280d.png)

6. This is the trips counter by gender. We can see male is the main gender of users which is 1.53m versus Female user 588k 


![trips_age](https://user-images.githubusercontent.com/100378319/171763292-d56c39ce-ff38-48a0-8548-895d77596964.png)

7. This is a line chart showing the age factor to the report. We can see most of the user's age is from 1969 which is 237k and 1988 to 1992. Therefore, we know that the age group is tend to younger generation, so that we can have different marketing strategy approach



![start_map](https://user-images.githubusercontent.com/100378319/171763308-eeebfb13-e034-4b61-90d3-23176c732237.png)

8. This is the start time station map with the bubble showing the number of users. The Circle in blue is the busiest location so we can tell which station needs more inventory, repairs and maintenance.


## Summary 

We have performed a deep analysis for the NYC bike-sharing program in August 2019. As the result of the analysis, we found that most of the user type is Male Subscriber. there are 1.53m male subscriber using the bike-sharing program during August. In addition, the peak hour for the service is the morning 8am to 9am and 5pm to 6pm which are the rush hour of the day. The age of most users is tended to the young generation which is around year of 1990. The busiest location is Manhattan Northwest so we can deploy more inventory and resources in these locations for maintenance services.

There are three additional visualizations that I would perform:

1. Competitor:

There are a lot of other transportation options for people to choose such as subway, scooter, skateboard, car, uber, etc. We can have another survey and analysis to compare the counts of the different type of transportation methods in order to have more understanding what people like most to travel to work.

2. Data accuracy

There are about couple hundred of users between age of 1885 to 1934 which are older than 85 years old in the year of 2019. That maybe happened because some of the user did not enter the correct information by mistake or in purpose.

3. Start station location and End station location based on hour. We will find out additional information about the relationship between time period vs location.




