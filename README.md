# NYC_CitiBike_Challenge

## Overview of the analysis
A bike-sharing program can be a great way to get around and explore a city. New York City already successfully uses a bike-sharing program called CitiBike, and this was the inspiration for potentially bringing a similar program to Des Moines, IA. Since we already have the dataset from New York, this was analyzed to project what a potential bike-sharing program would look like in Des Moines, IA.

The different aspects of the data that were analyzed included times that users checked bikes out and the duration of their trips, bike checkout times by gender, trips taken per hour on weekdays, trips taken on weekdays per hour by gender of user, and user trips by gender by weekday.

## Results

When looking at the results of the data for biksharing in New York City, we first look at the number of bike trips in the dataset, so we know the scale of the data we are viewing:

<img width="61" alt="number_of_trips_nyc" src="https://user-images.githubusercontent.com/114960958/215206171-5387b3e3-1854-45d9-9e64-4f453ba8b74c.png">

Then, we can see a breakdown of the customers vs subscribers, as well as the gender breakdown in the following images:

<img width="175" alt="customers_nyc" src="https://user-images.githubusercontent.com/114960958/215206948-f6b38369-0af7-46d6-bbb4-5d5386ca1a97.png">

<img width="193" alt="gender_breakdown" src="https://user-images.githubusercontent.com/114960958/215206978-4893b62a-3302-44cd-883f-86fad1f58586.png">

These images show that the majority (over 75%) customers are subscribers to the CitiBike service. In the gender breakdown, we see that people who identify as female make up about 25% of the dataset, people who identify as males make up around 65% of the dataset, and people with an unknown gender make up around 5-10% of the people in the dataset. 

When looking at the locations where bike trips start and end in New York City, we can see that there are higher concentrations in certrain areas of the city. These areas are coded by color shade variants, with the darker shades showing the higher concentrations of the strating or ending locations, and the lighter shades showing the lower concentrations of starting and ending locations. 

<img width="446" alt="top_starting_locations_nyc" src="https://user-images.githubusercontent.com/114960958/215211436-266bb37f-3d52-4749-ab9f-e677f329dfa5.png">

<img width="445" alt="top_ending_locations_nyc" src="https://user-images.githubusercontent.com/114960958/215211461-3c02021f-0ede-4b51-8574-ab1f731baaf3.png">

Starting and ending locations have higher counts in Manhattan, specifically in Midtown and lower, and particularly on the West side and center of the island. This is helpful in understanding where the most maintainence would need to be in a big city, because of the proximity of the high volume locations to popular tourist and commuter sites. 

Speaking of commuter bike-share needs versus recreational needs, the weekday trip data was analyzed, specifically when looking at trips taken throughout the week and the concentration of trips taken at different hours throughout the day, as shown in the below image:

<img width="403" alt="trips_by_weekday_per_hour" src="https://user-images.githubusercontent.com/114960958/215216594-01deeddd-2466-471d-b4ec-4a918a492c44.png">

This shows that most trips on Mondays through Fridays are taken in the morning between 7am and 9am, and then in the evening between 4pm and 7pm. There is some variation to be noted for Wednesday evenings, where fewer evening trips were taken, Thursday evenings and mornings, where more trips were taken than the average, and Fridays where more trips were spread out throughout the afternoon. Saturdays and Sundays show that most trips are spread almost evenly from 9am to 7pm.

The data showing trips by weekday per hour by gender, shows a similar spread of data, but highlights that most of the rides are completed by male users compared to female users or those with unknown gender, as shown in the image below:

<img width="779" alt="trips_by_gender_weekday_per_hour" src="https://user-images.githubusercontent.com/114960958/215217840-fadd5d51-9ec9-464e-80b7-e5241b6df19b.png">

Lastly, looking at a breakdown of trips taken by customers versus subscribers on different weekdays and broken down by gender, show another deep dive into this data, as shown in the below image:

<img width="295" alt="user_trips_by_gender_by_weekday" src="https://user-images.githubusercontent.com/114960958/215218278-3144fc29-7aac-4e54-97ce-9faeb74b4c61.png">

One other visualization created for this analysis was showing the checkout times for bikes both per user, and then by gender. See images below:

<img width="995" alt="checkout_times_per_user" src="https://user-images.githubusercontent.com/114960958/215239288-e166d958-2d44-4afe-900b-15d48eca82a8.png">

<img width="1087" alt="checkout_times_by_gender" src="https://user-images.githubusercontent.com/114960958/215239292-49604d05-2dc0-4df3-9828-7e63d6729b67.png">

## Summary
When using this data to determine next steps for opening a bike share business in another city such as Des Moines, there are a few key pieces of information that stand out for potential business owners. Location of bike pick up and pick up times can be helpful in understanding usage. The data shows that bikes were more likely to be picked up in areas close to important tourist and business sites in Manhattan. When looking at where to place bike pick up points in Des Moines, it is advised to first look at the most visited areas by tourists as well as the business district for commuters. It is visible in the data that subscribers use the service more than other customers, which could mean that locals and therefore commuters are using this type of service more than tourists. The data also shows that rides are most common during commuter hours, which supports the idea that commuters are among the leaders in higher rates of usage. This leads us to believe that placing pick up points near business centers and districts where commuters would more frequently work. The times when users are picking up bikes can also help prospective business owners understand what times are lower traffic times when scheduled maintenance can happen. Lastly, for marketing purposes, it could be helpful to know the gender of the customers who are using the bikes and when they are riding. The data shows that in New York, the majority of riders are men, which can help with predicting that it could be mostly men riding in Des Moines as well. Perhaps men are more prone to commuting by bike to work or biking in a city in general. Further research should be done on this spread of data to understand if this is how it would work in Des Moines, but also to understand why women and other people who do not identify as men are not using the service as much. This is a section of the market that could be advertised to but needs more research before doing so. 


[
Link to CitiBike Challenge WorkBook](https://prod-useast-a.online.tableau.com/#/site/bootcamptestsite/workbooks/837254/views)

[Link to CitiBike Story](https://prod-useast-a.online.tableau.com/#/site/bootcamptestsite/views/NYCCitibikeChallengeStory/NYCCitiBikeStory?:iid=1)
