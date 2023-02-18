# Ford GoBike Exploration
## by Chukwuebuka Ifechukwu


## Dataset
The dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area, information such as duration, start and end time as well as start and end station are recorded. The data can be gotten from this link:
https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1666177627493246&usg=AOvVaw1bhpRPIOMywHwmM3RGem7L 

Data wrangling was done on the data to prepare it for analysis. This included converting the date columns from object/string to datetime columns and creating new columns for month and weekday. Also, created a new column called age to depict the age of each individual at that time since their birth year was provided.


## Summary of Findings

During the exploration, found out the stations most users used to start and end their journey and would be interesting to see if this was because these stations are near residential areas where most users live. Also, looked at the distribution of the duration seconds and saw that most people journeyed between 4 and 6 hours throughout the month, I changed the axis to a logarithmic scale where a bell curve if formed. There is a very high amount of subscribers to customer type users and only a few users would agree to bike share of which none is a customer type user.Despite the disparity between the number of subscribers and customers, it was noteworthy to find out using the box plot that on average the customer type users would go on longer trips/durations in comparison to the subscribers. For weekdays, it could be seen that majority of people start and end their journey on thursday however when you look at the duration, the highest amount can be found on Sunday during the weekends.


## Key Insights for Presentation

For my presentation, I will be looking at Age, gender, user type and weekdays as I believe these are attributes that can be used to predict just how long a customer might go on a trip for. I start by depicting the duration distribution and showing how majority of customer journeyed between 3 and 12 hours. Then I would go on to show the age distribution and its correlation with duration using a scatter plot. This will show that the ages below 60 are able to do long durations going beyond 20000 seconds. Afterwards, I'd move onto the categorical variables and use a box plot to show their relationship with duration.