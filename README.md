# NY Citibike with Tableau
## Module 14 

## Project Overview 
### Purpose of Module 14 
In this module, we were introduced to Tableau. We used Tableau to create powerful and professional analytic dashboards that are easy to understand and that tell a story. The purpose of this module was to explore Tableau and successfully import data and use the data to create and style worksheets, dashboards, and stories to visualize the data. 

### Overview of Assignment 
For this assignment, we were tasked to create a story that explains why, given the data, starting a bike sharing company in Des Moines, Iowa is a good idea. The data we collected is from New York City’s Citi Bike data from August of 2019 which contains the trip duration, start and stop time, start and stop station ID and name, start and stop latitude and longitude, bike ID, user type, and the user's birth year and gender. We utilized this data to create a series of visualizations that answer questions an investor in the company may want to know— such as, “what are the peak usage hours?”. 
To further analyze our data and create proper visualizations, we first had to use Pandas to change the “trip duration” column from an integer to a datetime datatype in a new DataFrame and export the data as a new CSV file. With correct datatypes, we were able to create a set of visualizations that: show the length of time bikes were checked out for all riders and genders, show the number of bike trips for all riders and genders for each hour of each day of the week, and show the number of bike trips for each type of user and gender for each day of the week. 

### Resources 
- Tableau Desktop- public edition (2021.4.3)
- Python 3.7.10
- Jupyter Notebook 6.3.0
- Pandas 1.2.4
- [Citibike Data](https://ride.citibikenyc.com/system-data) 
- 201908-citibike-tripdata.csv 

## Results 

### [Click here to go to Tableau Story](https://public.tableau.com/app/profile/kelly.kindla/viz/Module14_Challenge_16434951235880/NYC_CitiBikie_Analysis#1) 

Walking through the Tableau story created from NYC's Citibike data, you will first see an introduction page with a link returning to this GitHub page. 
The first set of visualizations come from the module. They display the start and end locations for each bike. The markers on the map vary in accordance to the number of records where red dots represent less frequent rides and green dots are more frequent. Furthermore, the larger the marker, the more frequent the ride. One may further filter either map by selecting a marker to see where a bike from that start or end location typically travels to. 
### Image A
<img width="929" alt="startstoplocations" src="https://user-images.githubusercontent.com/92558842/151681904-2ddc6d4d-d397-43ad-8a8d-019d62218754.png">

The next visualization also comes from the module. This visualization shows the number of bike repairs for each bike ID and the percentage that bike is repaired compared to the total number of rides. The larger and deeper blue the marker is, the more frequently it is repaired. 
### Image B
<img width="602" alt="repairs" src="https://user-images.githubusercontent.com/92558842/151681906-bf81acd8-a373-4b60-a42c-15da01c3e068.png">

Following this visualization is the distribution of rides per hour for the month of August which was created in the module. 
### Image C
<img width="998" alt="time" src="https://user-images.githubusercontent.com/92558842/151681911-f34fdd3f-5a6a-48a4-ac9e-6835f3dc2fb2.png">

Next, we dive into the challenge creations. The first set of challenge visualizations show the length of time each bike was used for all riders and genders. Each graph can be filtered by hour to show the length of time in minutes the graph was used. One of the graphs can further be filtered by the identified gender of the user to aid in one's analysis. 
### Image D
<img width="938" alt="usage" src="https://user-images.githubusercontent.com/92558842/151681918-8c3200ff-fea8-4744-a341-1515a539b0ec.png">

Next, a heat map was created to show the number of bike trips broken down by gender and user type for each day of the week. This heat map can be filtered by desired gender and user type one may want for their analysis. The darker red the marker, the more frequent a ride for the search criteria. 
### Image E
<img width="366" alt="users" src="https://user-images.githubusercontent.com/92558842/151681924-4c37fbe7-11a3-47e6-9bfe-fc5ecf303cfd.png">

This data is then broken into the next two heat map visualizations which demonstrate the number of bike trips by weekday for each hour of the day and the number of bike trips by gender for each hour of each day of the week. One may filter the gender heat map by desired gender for further analysis and a filter was created for the trips by weekday map so one may select a marker to see correlated occurrences on the gender heat map. 
### Image F
<img width="1007" alt="weekdayandgender" src="https://user-images.githubusercontent.com/92558842/151681927-c4ce0919-5128-4ad7-a0c9-bed06989a598.png">


In total, there are five visualizations from the module and five visualizations from the challenge that can be used in a proposal to potential investors. 

## Summary 
The visualizations of this module were created with stakeholders in mind and aim to answer any questions one may have in regard to the success of a bike-sharing company. The start and stop location visualizations (Image A) not only demonstrate the highest traffic locations of bikes but also how far and frequently used the bikes are across the city. One may gather from this visualization that the closer to the heart of the city or the more populated the location, the more frequent one may use a bike. The next visualization (Image B) is also important to investors as it shows the frequency of repairs which is potentially where a large portion of investments may be distributed towards. One may gather from this visualization that repairs are common but very frequent in relation to the total number of rides or the total number of bikes so there is a high chance one may always find a bike to use. The peak ride time bar graph (Image C) shows the distribution of rides over time. This data can be used to show the peak usage hours to gauge what time is best for potential repair or sanitization. One can find that 8AM and 6-7PM are the most common times a user takes advantage of bike-sharing. The check out time visualizations (Image D) gives insight on the duration of rides and further give insight on who uses the bikes. Based on the visualizations, we can see that trips are typically no longer than an hour and males typically use the bikes more than females or undisclosed genders. The heat maps offer further analysis on bike usage. We can see from the first heat map (Image E) that males use the bikes more frequently than others and that there are more subscriber records than single use customers. From the next two heat maps (Image F), we can see a unique distribution of bike rides by each hour of each weekday. From the heat maps, we can gather that there are peak usage hours on weekdays- typically 6AM to 9AM and 5PM to 7PM. We can also see that bike usage is fairly evenly distributed on Saturday and Sunday from 9AM to 8PM. Visualizing the heat map by gender shows again that males typically use the bikes more frequently than others. In essence, this data can be used to determine where to set up bikes, when to repair or sanitize bikes, who to target, and suggests that a subscription program is generally successful. However, additional visualizations could aid in the business proposal. Amidst a global pandemic, I would suggest to recreate the visualizations showing the data of bike-sharing in 2020 or 2021. I would also add a graph showing sanitation frequency for each bike. It would also be interesting to visualize the path taken for each bike based on the bike trip ID. Lastly, it may be advantageous to add population distribution and area codes to the bike start and end locations to determine if there is a correlation between more densely populated areas and number of bike rides in an area. This data could be used to map where to place maps in any city. 

