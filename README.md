# Project 1: NC Real Estate Market

ABOUT THE PROJECT
------------

In this project we will be analyzing the North Carolina housing market over the past 20 months using housing data provided by Zillow to conduct our research as it breaks down properties via single family housing prices from a nationwide pool of data that can be narrowed down to a specific metropolitan area within the state if needed. 

BUILDING THE PROJECT
------------
This project has two core programs that were used for its completion:
hvplot
Pandas 

This project began by taking a CSV file of the average home prices in over 100 cities across the countries and narrowing those cities to just ones in North Carolina. 

This lead to largest problem that was faced when building this project which was the formatting of the CSV file provided. It provided the information on housing prices that were needed, however, the dates for the average selling price in each city was a column header and not part of the data values. Therefore, this created a few struggles in attempting to slice the information to where it just showed North Carolina cities as well as getting the correct picture in the graph. 

To aliviate this problem created different values that only included the title headers I wanted across the board like so:

<img width="688" alt="Screen Shot 2021-10-28 at 2 56 14 PM" src="https://user-images.githubusercontent.com/89325129/139318225-6368e10d-8d20-4274-8351-23326d34e75f.png">

Then using the .loc function called on "State_names" under "NC" to get my NC cities. 

Once the cities were isolated, created for loops to only show housing data that came from certain time frames because the dates were under headers and not values within the dataset. 

<img width="535" alt="Screen Shot 2021-10-28 at 3 00 02 PM" src="https://user-images.githubusercontent.com/89325129/139318764-5c6c8e1b-96c5-4bb6-afb5-549cfb2488e6.png">

After creating variables that sliced the information to certain 12 month incraments, I combined the two, to create a dataset that only shows housing prices from the years 2020 & 2021. 

The final step was creating an hvPlot that showed the values over that two year span. Ran into trouble getting my tables to work together until I utiliced the .T function to transpose the two datasets which solved the issue. 

CONCLUSION
------------
After putting together the data it is clear that due to a multitude of exterior factors that the housing market in North Carolina has seen a significant increase in housing prices over the past 2 years. 

CONTACT
------------
Andrew Trease - amtrease@gmail.com
Project Link - https://github.com/amtrease/project_1
