# bikesharing
# Overview
The purpose of the project was to create a pitch for a bike-sharing (citi bike) solid business proposal to convince investors to fund the program. To solidify the buisness proposal, the goal of the challenge was to analyse the bike-sharing (citi bike) data in New York City in the month of August. I also analysed how the bike-sharing business operates in the peak summer period.
The first page of the Tableau story contains basic information about the data provided in the csv dataset. 
This page contains the following information: 
* Peak Rides by Gender;
* Number of Rides;
* Customer type.
![OVERVIEW](https://user-images.githubusercontent.com/104453593/184251725-ff2fa9ee-4826-48dd-84c1-4d4e917454cf.PNG)


# Resources
* Dataset
 
 Download the 201908-citibike-tripdata.csv.zip from [Citibike data](https://s3.amazonaws.com/tripdata/index.html)
 
* Softwares used:
1) Tableau Public
2) Pandas Library
3) Jupyter Notebook
4) Python

# Results
* Checkout Times for Users

The line graph shows the number of bikes (citi_bikedata.csv data) on the y-axis and trip duration (divided into hours and minutes) on the x-axis. It is filtered to show 0-2 hours.

![Checkout Times for users'](https://user-images.githubusercontent.com/104453593/184048587-f1f4462d-f1a2-4909-9d21-e52b1d1fa1a7.PNG)

* Checkout Times by Gender

The line graph shows the number of bikes (citi_bikedata.csv data) on the y-axis and trip duration (divided into hours and minutes) on the x-axis. Accoridng to the filter on the line graph, the orange represents the male, blue represnts the female and red represents the unknown. The line graph shows that males checkout bikes more than the all other genders (i.e. female and unknown) especially in the first hour.

![Checkout Time by Gender](https://user-images.githubusercontent.com/104453593/184065252-0ebc482b-80a6-426c-9b46-0ab4da8e5063.PNG)

* Trip by Weekday per Hour

According to the heatmap below, the most used and peak hours was between 5-6pm and 8am. The heatmap also shows that Thursday is a very busy day, and Saturday and Sunday afternoons are also busy.

![Heatmap for Trips by weekday](https://user-images.githubusercontent.com/104453593/184047397-4eabed57-2e8e-4ce2-8b98-cec267894e36.PNG)

* Trip by Gender(Weekday per hour)

The heatmap shows the relationship between the starttime in hours on the y-axis and stoptime in weekday on the x-axis. According to the heatmap, the busiest time was within the hours 6-9am in the morining and between 5-7pm in the evening during weekdays. This shows that people utilize in the movement to and from their jobs. Also, weekends are also busy during the day (between the hours of 10am - 6pm). The heatmap also shows that males are the most frequent users.

![Trips by Gender by weekday](https://user-images.githubusercontent.com/104453593/184067310-86bad445-109b-40c5-b549-d7a6026c31bd.PNG)

* User Trips by Gender by Weekday

The heatmap below shows the number of trips per weekday that bikes were checked out by gender (male, female and unknown) on the x-axis and by usertype(i.e. subscribers and customers) on the y-axis. According to the heatmap, male subscribers has the highest number of trips especialy on Thursday and Friday.

![usertrip by gender](https://user-images.githubusercontent.com/104453593/184068265-d021c7a5-3229-42e3-951e-b64660d8d772.PNG)


* Bike Utilization

The graph with bubbles shows the levels of bike utilization by bike id. The higher the bike utilization, the larger the bubble and the lower the  bike utilization, the smaller the bubble.

![bike utilization](https://user-images.githubusercontent.com/104453593/184245033-1406e84e-63d9-41bd-b80e-2e1a1f84ca6a.PNG)


* Staring and Ending Locatgions

The two graphs show the top start and end locations in New York City. According to the graph, the larger and darker the bubbles, the higher the number of bike users.

![start and end locations](https://user-images.githubusercontent.com/104453593/184068902-5ad80b20-4469-4fad-80b6-6bc03085af76.PNG)

# Summary
An additional visualization that can be added will be analyzing the bike checkout times by age.

https://public.tableau.com/app/profile/faith.emenike/viz/Module14Challengenew/NYCCitibike?publish=yes
