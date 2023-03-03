# Data-Visualization

This project centers around building data visualizations and a data dashboard in Tableau. The data used in this project comes from a Kaggle dataset; it tracks the on-time performance of US domestic flights operated by large air carriers in 2015.

The goal of the dashboard is to create a way for the user to easily use the delay data to make an educated choice on airline choices based upon historical data for delays.

## What is the average duration of each delay type?
![Avg Time for Delays](https://user-images.githubusercontent.com/119750131/222784147-6a90acbd-3310-42c2-8aa6-343f058f9e08.png)

This visualization provides the average duration of each type of delay to understand which are generally the longest and have the most impact on flights.

https://public.tableau.com/app/profile/jesse.daugherty/viz/FlightDelaysandCancellations_16778467986700/AvgTimeforDelays?publish=yes

## Delays by Airline
![Total Delays](https://user-images.githubusercontent.com/119750131/222784898-0319cc61-1f89-4078-a0a3-22cc294c445f.png)

This visualization shows the total minutes delayed in our dataset and the average of all delays in our dataset by each airline. This visualization allows the user to see the average delay you could expect for each individual airline and includes the average delay per delay category for the airline when you hover over a bar.

https://public.tableau.com/app/profile/jesse.daugherty/viz/TotalDelaysbyAirline_16778644859870/TotalDelays?publish=yes

## Airline Sizes
![Airline Sizes](https://user-images.githubusercontent.com/119750131/222785358-874c97cc-a445-4074-bf56-231b54d975d0.png)

I used a calculated field to break up the airlines into size categories: 'small’, ‘medium', and 'large’. This visualization displays the total flight count for each airline in the data. Shapes will display the different categories for this and the following visualization.

https://public.tableau.com/app/profile/jesse.daugherty/viz/AirlineSizes/AirlineSizes?publish=yes

## Counts of Flights vs. Average Delays
![Count of Flights vs Average Delays](https://user-images.githubusercontent.com/119750131/222785622-6eb73cf2-8e51-434d-af42-3177a7c7ce22.png)

This visualization wraps up the information that was found and should be the best tool to allow a user to decide on an airline based on delay and airline size. It gives insight into a few interesting facts about our data. It seems there is a significant variance in the average delay in small airlines, and medium airlines generally have a longer average delay. Large airlines tend to fall between the groups concerning their average delay duration.

https://public.tableau.com/app/profile/jesse.daugherty/viz/cvsd/CountofFlightsvsAverageDelays?publish=yes

## Flight Delays Dashboard
![Flight Delays Dashboard](https://user-images.githubusercontent.com/119750131/222785918-7e7d7063-58ff-4d53-b37d-864be42ee59f.png)

Finally, the dashboard brings all our visualizations together and allows the user to filter by both the airlines and by the three size categories that were created. The user could review the data quickly on their favorite airlines and make an educated decision if they were worried about running into delays on their trip.

https://public.tableau.com/app/profile/jesse.daugherty/viz/FlightDelaysDashboard_16778646664830/FlightDelaysDashboard?publish=yes
