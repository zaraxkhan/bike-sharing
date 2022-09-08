# Bike-Sharing
With the use of Tableau Public and Python, I created data visualizations that share information regarding the usage of Citi bikes in NYC.

## Overview

With my business partner Kate, we have decided to start a bike-sharing program in our hometown of Des Moines,Iowa just like the Citi bikes in NYC. It is a convienent way to travel around the city quickly. So, we will need to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. We use the data from August of 2019 from the Citi Bike system data page. We'll use data from August because there is likely more traffic during the summer months

For this analysis, I’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Finally, I’ll add these new visualizations to the two I created in this module for my final presentation and analysis to pitch to investors. The two other visualizations will be:
- Show which gender uses the bikes more
- Show which type of users use the bike more
- The peak hours that the bikes are used

## Results
The original CitiBike csv file had the trip duration taken down by seconds. So, in Python, with the help of Pandas, I added a new column and converted the tripduration to a datetime data type. After this conversion I began making my visualization in Tableau. The following visuals will be showing the data for August, 2019. 

### Checkout Times for Users
![Checkout_times_for_users](https://user-images.githubusercontent.com/105755095/189006779-41892c69-36ad-4f09-8b25-f5057a318f20.png)

This line graph broke down the number of bikes that were used and the length of each ride per hour. From this visualization we can see that most users ride the bikes for longer times from 4 AM to 7 AM. It also seems like throughout the day, the highest peaks are during the 20- 40 minute marks. That means that users ride mostly for an average of 20-40 minutes.

### Checkout Times by Gender
![Checkout_times_by_gender](https://user-images.githubusercontent.com/105755095/189007160-726bd4dd-5630-4f5a-b910-034fdf07bc3d.png)

This chart shows similar to the previous line graph, however it is broken up by gender. On the far right side of this image, we can see that corresponding colors to each gender. Unknown is for the customers that decided no to include their gender. Fromthis line graph we can see that mostly the men are the ones using the citibikes more. During the peak hours from 4AM  to 7 AM most of these men are riding between the 40 to 60 minute mark. The is different than the average shown in the previous line graph. Throughout the day the peak points stays at around 0-20 minutes. For the females however, it looks as though it is pretty steady. There are more users around 4 AM to 7 AM, however the peak minute time that they are on the trip is pretty vast and the data points for 0 to 60 minutes are about the same.

### Trips by Weekday per Hour
![Trips_by_weekday_per_hour](https://user-images.githubusercontent.com/105755095/189007864-367b889c-4bf7-495f-ac2c-e1ed7125f0a7.png)

This heatmap shares what time of day is most popular each day of the week. The darker the color of red, the more trips on the citibikes that were taken. The busiest time for the bikes would be 8 AM and 5 to 7 PM. This would make sense as this is usually when people are going to work and coming back. However, on the weekends, the busiest times are from about 10 AM to 4 PM. Especially on Saturdays which is probably due to the fact that this is when families and friends are hanging out together. 

### Trips by Gender by Weekday per Hour
![Trips_by_gender_by_weekday_per_hour](https://user-images.githubusercontent.com/105755095/189008151-bf7a5c75-dc73-40c0-b3c5-10620fa5019b.png)

This is a similar heatmap to the last, but also includes a map for each gender. The data seems to follow the same pattern as the last heatmap, however it is more apparent here that men are using the bikes more than the women. 

### User Trips by Gender each Weekday
![User_trips_by_Gender_by_weekday](https://user-images.githubusercontent.com/105755095/189008348-f4464f12-44a9-4ac9-9a69-33d9e7e29af7.png)

This heatmap breaks down the bike usage per gender for each day of the week. It also shares whether the user is just a customer or a subscriber. Fromthis heatmap we can see the same pattern of the men using the bikes more frequently. The peak days also seem to be Thursday and Friday. Additionally, this heatmap also shows that most of the users are subscribers. That is important information as we can make sure to push that to the investors. Subscribers usualy means steady income and frequent usage. 

### Customer Type by Gender
![Customer_type_by_gender](https://user-images.githubusercontent.com/105755095/189009716-463d7417-fa7e-40ce-9fea-93c4f62bc5bb.png)

This simple pie chart shows the gender of the bike users. With the labels it is clear to see that more than 65% are males and a quarter are females. The rest decided not to disclose that information.

### User Type
![Usertype](https://user-images.githubusercontent.com/105755095/189009851-a8e001c2-ac1a-41a4-89c6-684156d2aa23.png)

This pie chart shows that most of the users of the Citi bikes are subscribers. About 81% are steady users of the bikes and probably use them regularly for their everyday commutes. 

### August Peak Hours
![August_peak_hours](https://user-images.githubusercontent.com/105755095/189010018-7dd36719-2b6f-4bd2-9ded-0d76e01c8bb7.png)

This bar graph shows what time of day are the bikes ridden the most. From this graph it seems like the peak hours are 8 AM and 5-6 PM. Similar to the what the heatmaps had shared. 

### Peak Days by Users
![Peak_weekdays_by_users](https://user-images.githubusercontent.com/105755095/189010170-7f92048e-72af-4d36-a7e1-554ade920f2d.png)

This bar graph breaks down what days each type of users ride the bikes. It looks like the customers use them most on the weekends and the subscribers use them more during the work week. For some reason, however, Wednesday is a slow day for both subscribers and customers. 

## Summary
From these visualizations, it is safe to assume that males are using the bikes more. Subscribers would be the target to market towards as they are using these bikes more for every workday use. More than what we would assume tourists are as most are used by subscribers that will be using the bikes more frequently and during commute times of 8 AM and 4 to 5 PM. 

I created a dashboard of customer breakdown for the rides. This shares all the information regarding the breakdown of types of customers using the bikes.
![Customer_Breakdown_DB](https://user-images.githubusercontent.com/105755095/189010690-bf104fc2-5ca5-4e64-acb1-dc4e49dceed5.png)



I created another dashboard which contains all the graphs that had inforamtion sharing the peak days and times for rides. 
![Peak_Time_Usage_DB](https://user-images.githubusercontent.com/105755095/189011001-046d5549-25a9-4fca-8079-280d9bfbff45.png)



The last dashboard had all the information brokendown according to gender. 
![Usage_By_Gender_DB](https://user-images.githubusercontent.com/105755095/189011108-ea9ccfd6-dfc6-460e-b0d6-f7dce82c6dcc.png)


### Future Analysis
For future analysis, I think it is important to add the following points:
- Show which age groups are using the bikes as subscribers.
- Show which age groups are using the bikes during peak times.
- Show how this data can relate back to Iowa as NYC is a much busier and touristy city than Des Moines

### Links
I have created a story on tableau sharing this information in a more visually appealing format:
[NYC CitiBike Story](https://public.tableau.com/authoring/NYC_CitiBike_16625778141000/Sheet1/NYC%20CitiBike#1)

