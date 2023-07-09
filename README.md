# Module 18 - Tableau Challenge
Given Below the link to my tableau public workbook

https://public.tableau.com/views/Module18Challenge_16885645285930/Dashboard4?:language=en-US&:display_count=n&:origin=viz_share_link

My Story has 4 slides
  1.Introduction.
  2. Peak Hours.
  3. Start Station.
  4. User Type.
I have derived few chats and map to showcase some of the interesting phenomena. Following are the analysis made from the charts and map

## Peak Hours

### 1.Ride Count by Hour of the day

X-axis - Hour of the day
Y-axis - Count of rides

This showcases the total number of rides by hour of the day. On initial analysis-
It makes sense that the lowest number of rides in a given day is between 12am & 4am. 5am is the point of inflection where the number of rides start to rise. There is a sharp rise in the number of rides between 6 to 8am. This can be attributed to the school goers & office goers' usage. The second peak of the day seems to be between 3pm and 7pm. In fact, this peak records  the highest number of rides in a given day. This can be attributed to return trips that were started in the day or users booking to bike around for fun after a long day at school / college / work. Post 7pm, the number of rides steadily goes down until the point of inflection, 5am, the next day.
Interactive features
What is interesting is that the trend / pattern of ride count vs hour of the day is pretty consistent across the 3 months- March, April & May. However, the number of rides seems to increase month on month. This can be due to the fact that NYC is moving into Spring and more people are willing to go out on these bikes
Based on user type
It is evident that casual users prefer to book rides in the evenings while members are more keen on using it around mornings and evenings. Member users may be a mix of school, college and office goers as it makes sense for them to become a member for their daily usage. Since both user types book rides in the evening, there seems to be a peak around the 3pm to 7pm timeframe.


### 2.Peak Hours in Spring by Days of the week.
The parameters used are:
 Y-axis - Ride Count 
 X-axis - Hour of the day 
The overall ride count by hour of the day shows a fixed pattern. Of peak hours early in the morning and in the evening. This pattern holds true for weekdays across the 3 months. However, during weekends, the pattern is different. The peak is more spread from 8am to 9pm. This can be attributed to hobbying and sightseeing. It will be good to get insights into the nature of users - locals, tourists, etc. This will throw some light into the usage and utilisation of bikes by user types.

An interactive filter provided for this visualisation is weekdays - Sunday, Monday, ….. , Saturday.

## Start Stations

### 1.Top 10 Start Stations by Ride Count
The parameters used are:
Start station name - y axis
Count of rides - x axis

It is evident from initial analysis that Grove Street Path has the highest count of rides with >11K rides booked. This is followed by Hoboken Terminal at 10,775 and South Waterfront Walkway at 8,539. These numbers are valid across 3 months - March, April and May.

Had the dataset provided bike ids along with booking id mapping, it would help understand the utilisation of bikes at each of these stations. This will help optimize the number of bikes and provide an improved customer experience in terms of availability.

###  2. Bottom 10 Start Stations by Ride Count
The parameters used are:
Start station name - y axis
Count of rides - x axis

All 10 of these stations have only 1 booking across the 3 months of March, April and May. With data on utilisation, it will be a beneficial exercise to optimise the number of bikes available per station. This has the potential to improve overall revenue as an outcome of this optimisation technique.

Available interactions for the 2nd visualisation is: Ride Count slider ranging from 1 to 100.

### 3.Popular Start Stations by Ride Count
This visualisation is plotted on the geographical map that marks the start stations by count of rides. Higher the ride count for a start station, bigger the size of the marking and lower the ride count for a start station, smaller the size of the marking.

Example: Size of Liberty Light Rail marking is larger than size of Union St marking owing to the ride counts: 4,091 vs 438.

## User Type
Ride counts for members vs casuals
This shows the data for 3 months separately. For all 3 months, the total number of rides is greater by members compared to casual users. As the months progress, the number of rides from member users and casual users increase steadily. 

### 1.Ride IDs vs Ride Duration
This shows the duration of each ride ID in the system. Provided we know that member users count for more ride duration compared to casual users. 

An interactive filter available for this visualisation is user type: member, casual.

With information about the user id, we will be able to further slice and dice this information on multiple levels. An interesting use case this can open up to is- top member users and top casual users. Using this list, a dedicated marketing campaign can be carried out to provide discounts to the loyal customers in the system.

### 2.User type by Bike type
 It is evident that member users prefer the classic bike and docked bikes are not used by this user type.However, with casual users, the usage of classic bikes is still higher compared to others. However, electric bikes are relatively used better by casual users compared to members.

With this analysis, it can be concluded that classic bikes are the most sought after bike by both types of users. Using this information along with the optimisation techniques will be beneficial for the organisation revenue.

A total of 49.2K miles is the ride distance for casual users compared to 122.4K miles by member users. 

