![citibike](https://user-images.githubusercontent.com/119648166/230016217-686cef51-f7f5-4a03-a83d-2145807eded1.jpg)

## Project Overview

### Purpose

I am developing a project that involves utilizing Tableau to generate data visualizations for New York City's bike sharing program. The objective is to scrutinize the data to understand the workings of the business and gain insights into the mechanics of the system in NYC to convince investors that a bike-sharing program in Des Moines is a solid business proposal. This initial phase is crucial to the expansion of the idea to other urban areas.

The Tableau Story can be found in the following link : [Tableau_Story NYC_Citibike](https://public.tableau.com/app/profile/smita.singh8343/viz/CityRides_NYC_twbx/NYCCitibikeStory)

### Background
For this analysis,  **Pandas**  is used to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, a set of visualizations are created to:

-   Show the length of time that bikes are checked out for all riders and genders
-   Show the number of bike trips for all riders and genders for each hour of each day of the week
-   Show the number of bike trips for each type of user and gender for each day of the week.

Finally, all these  visualizations are created into story using **Tableau** for presentation and analysis to pitch to investors.
### Results

 1. #### Checkout Times for Users
 ![Checkout_Times_by_Users](https://user-images.githubusercontent.com/119648166/230016353-78fe9022-cdc6-427e-ada1-bba5a4386795.png)

The data represents the count of NYC Citibike trips based on the duration of the trip in minutes and the hour and minute of the start time. The graph indicates that the most frequent trips occur between 0 and 20 minutes and during peak hours of the day. The highest counts are recorded between 6:00 PM and 7:00 PM with over 145,000 trips in this time frame, followed by the morning rush hour between 8:00 AM and 9:00 AM with around 128,000 trips.

 2. #### Checkout Times by Gender

![Checkout_Times_by_Gender](https://user-images.githubusercontent.com/119648166/230016408-034f122a-8e17-43b0-bb4b-5fd94296d064.png)

The graph contains hourly data on Citibike trips in New York City, broken down by gender into three categories: UNKNOWN, MALE, and FEMALE.This dataset seems to be a record of bike trips taken in New York City using the Citi Bike program. The data is organized by hour and minute of the day, and each row includes the count of trips taken during that time period. The gender of some of the riders is unknown. 

 3. #### Trips by Weekday for Each Hour
 ![Trips_by_Weekend_for_Each_Hour](https://user-images.githubusercontent.com/119648166/230016480-4f0c7df9-c0dc-4fd4-ab40-1918dfdc2f34.png)

 
This graph shows the count of Citibike trips during each hour of the day, broken down by weekday, for New York City. The data suggests that the number of trips peaks during the evening rush hour on weekdays, whereas on weekends, the peak is in the afternoon. Additionally, the data indicates that more trips are taken during the weekdays compared to weekends, with the highest number of trips recorded on Thursdays.

 4. #### Trips by Gender (Weekday per Hour)
![Trips_by_Gender_(Weekday_per_Hour)](https://user-images.githubusercontent.com/119648166/230016550-cd581427-26c2-4483-b350-165ef954f87b.png)


This graph represent the count of trips taken on NYC Citibike by hour, gender, and weekday. Each row corresponds to a different combination of the three categories and lists the count of trips taken for that combination.Darker color indicates more trips, while lighter color indicates less trips. Additionally, the graph is divided by gender (UNKNOWN, MALE, and FEMALE)

 5. #### User Trips by Gender by Weekday 
![User_Trips_by_Gender_by_Weekday](https://user-images.githubusercontent.com/119648166/230016600-516c0ce7-7816-4899-8143-5849273d9014.png)


The depicted graph displays the count of trips categorized by weekday, user type (subscribers and customers), and gender. The y-axis denotes weekdays and user type, while the x-axis represents gender. Among subscribers, males exhibit the highest number of trips, particularly on Thursdays and Fridays, followed by Monday and Tuesday. Females have a comparable distribution of trips but with considerably fewer trips than males. The unknown gender group displays an even distribution of trips throughout the week. Upon examining the customer data, it is evident that all genders take fewer trips, with a slight increase in the unknown gender category on Saturdays and Sundays.

 6. #### Bike Utilization
  ![Bike_Utilization_NYC](https://user-images.githubusercontent.com/119648166/230016643-566dd262-4ad8-497a-a2e9-c24e4fa97c9c.png)

  
  The chart presented here depicts the utilization of all bikes in terms of time used (represented as integers for ease of calculation). Hovering over the chart reveals the bike ID and corresponding time units for each bike. Based on the chart, we can group the bikes into four rough categories: small bubble , medium-small bubble , medium bubble , and large bubble . Using this information, we can classify the bikes into different groups and develop a plan for their maintenance, rotation, and distribution across the stations.
  
7. ####  End Locations
![End_Locations](https://user-images.githubusercontent.com/119648166/230016685-6d5b2fe2-8073-4c4b-8880-dbe4c0ae1e63.png)


The graph illustrates the number of trips ending at each station. The size of the bubbles represents the frequency of trips, with larger bubbles indicating more trips and smaller bubbles indicating fewer trips. By examining the graph, we can determine which stations are most frequently used as end points for trips. This information can be used to identify patterns in user behavior and to make decisions about bike maintenance and distribution in different areas.

### Summary
In conclusion, the NYC CitiBike program provides a wealth of data for analysis. By examining the data on bike maintenance, customers and subscribers, gender, and trip duration, we can gain insights into various aspects of the bike-sharing business. The data suggests that there is potential to attract more female riders and that planning ahead for maintenance and station stocking during peak times is essential for a good customer experience. The bike-share program is a relatively inexpensive and easy-to-implement transportation option that can deliver a variety of benefits for both the business and the city.
