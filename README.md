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
The original CitiBike csv file had the trip duration taken down by seconds. So, in Python, with the help of Pandas, I added a new column and converted the tripduration to a datetime data type. After this conversion I begin making my visualization in Tableau. 

### Checkout Times for Users
![Checkout_times_for_users](https://user-images.githubusercontent.com/105755095/189006779-41892c69-36ad-4f09-8b25-f5057a318f20.png)

This line graph broke down the number of bikes that were used and the length of each ride per hour. From this visualization we can see that most users ride the bikes for longer times from 4 AM to 7 AM. It also seems like throughout the day, the highest peaks are during the 20- 40 minute marks. That means that users ride mostly for an average of 20-40 minutes.

### Checkout Times by Gender
![Checkout_times_by_gender](https://user-images.githubusercontent.com/105755095/189007160-726bd4dd-5630-4f5a-b910-034fdf07bc3d.png)



## Summary
I think it is important to compare this set to data from Iowa. 
