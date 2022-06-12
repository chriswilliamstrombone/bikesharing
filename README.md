# bikesharing

# NYC CitiBike

## Overview

### Purpose

- The purpose of this project is to create a data visualization with Tableau for bike sharing program in New York City.

- Starting with only a .csv file, we can create a visual story for audiences to absorb with clear graphics and informative text.

- With this, one could easily create a business proposal substantiated by our data.

The Tableau story of the NYC CitiBike can be found in the following link:
[https://public.tableau.com/app/profile/chris.williams8057/viz/NYCCitiBikeStory_16550670127240/NYCStory](https://public.tableau.com/app/profile/chris.williams8057/viz/NYCCitiBikeStory_16550670127240/NYCStory "link to dashboard")

## Results

### General Information

![1.png](Resources/1.png)

- The general information dashboard gives the viewer quick access to some key data regarding our story.

- Number of rides: 2,344,224.

- Customer type, and a respective pie chart.

- Peak hours for August.



### Checkout Time for Users

![2.png](Resources/2.png)


- This graph shows us the average trip duration based on users.

- The graph has time on the x-axis in minutes, and number of rides on the y-axis.

- We can see the average duration of a trip is 5 minutes.

### Checkout Time per Gender

![3.png](Resources/3.png)


- This graph shows us the average trip duration based on users.

- The graph has time on the x-axis in minutes, and number of rides on the y-axis.

- This graph divides users based on gender type.

- We can see the average duration of a trip is still 5 minutes between men and women, and becomes less clear in the 'unknown' group.

### Trips by Weekday per Hour

![4.png](Resources/4.png)

- This graph tells us the number of trips per hour and per weekday.

- The graph uses hours on the y-axis and weekdays on the x axis.

- The variation in color represents the number of trips in that specific time slot. (lighter is less frequent and darker is more frequent)

- We can see the bikes are used the most from 6 to 9 A.M. in the mornings and 5 to 7 P.M. in the afternoon on weekdays.

- Saturday and Sunday see higher frequency between 10 A.M. and 6 P.M. approximately.

### Trips by Gender (Weekday per Hour)

![5.png](Resources/5.png)


- This graph tells us the number of trips per hour and per weekday.

- The graph uses hours on the y-axis and weekdays on the x axis.

- The variation in color represents the number of trips in that specific time slot. (lighter is less frequent and darker is more frequent)

- This graph is also divided by gender groups.

- We can see that males have the highest trip frequency, especially from 6 to 9 A.M. in the mornings and 5 to 7 P.M. in the afternoon.

### User Trips by Gender by Weekday

![6.png](Resources/6.png)

- This graph tells us the number of trips by weekday, comparing subscribers and customers, as well as comparing gender.

- The graph has weekdays and user type on y-axis and gender on x-axis.

- Females have a similar distribution of trips when compared to makes, but show significantly lower number of trips than males.

- Amongst subscribers, males have the highest number of trips especially on Thursdays and Fridays.


### Bike Repairs

![7.png](Resources/7.png)

- This treemap represents bikes that may need repair soon.

- The dark color indicates bikes that are in need of repair, and the lighter color reflects the opposite.

### Gender Breakdown

![8.png](Resources/8.png)

- This pie chart shows us a gender breakdown.

- We can see males make up the majority of the userbase.

## Summary

Tableau gave us a simple and effective way to generate meaningful statistics from one .csv file with only a few hours of time to manipulate said data.  The team at CitiBike can now make crucial desicions for the company based on key metrics, in an effort to drive the group forward.  We also used pandas to convert the values of the trip duration column from the original file into date and time. With just these few lines of code, and a new dataframe, we can clearly represent the length of most trip durations, the genders of the people who are renting these bikes, a comparison of user types, the most popular times of day that these bikes are being utilized, and so on.

Two potential visulizations to add:

1. Users based on location.  Similar to comparing starting and ending locations, it would be nice to visualize what areas see the highest use of CitiBike based on where the users live.  With this information the team could better determin what part of the city needs more bikes to help increase profits.

2. Age: We have already divided the users into gender classes. Another good grouping technique would be taking the age of the users to try to isolate the key demographic of CitiBike, or attempt to branch out and appeal to other generations (older or younger).