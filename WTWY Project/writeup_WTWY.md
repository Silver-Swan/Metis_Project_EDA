WTWY_WriteUp.md

# Optimal Placement for WomenTechWoemnYes Street Teams.

Edward Kerr

## Abstract
The goal of this project was to present the optimal station entrances to place the WTWY street teams to gather the most signatures. I will provide data that will show stations with the highest turnstile count. Using the same information, I will present at what time of day has the highest turnstile count. The idea behind why I chose these datasets was that the highest turnstil count can be associated with how many people are going through the turnstile. Which would translate into having a large group of people present for the street team to apporach. I have found that the top five stations with the largest turnstile count were either trains going into Jersey City, NJ or stations that has every line going through them. For example, the station with the largest count is 34 ST and Harold SQ which has majority of the lines going through it. Since WTWY are looking for people that can attend their gala as well as help contribute to their cause, the information gathered at the stations going into Jersey City has a higher chance of the passengers being local. Which means that they can attend the galas. I will first show the top five stations with the highest turnstile count. Afterwords, I will present graphs from midnight to 8 pm of those stations. The purpose for this was to place the street teams at these locations with the highest count of turnstile use. 

## Design
 To help present my ideas, I had to filter through the data to narrow down details needed to help me find the optimal stations for the placement of the street teams. I used datetime to create a column combining the date and time column. This help me aggregate the turnstile counts data to daily usage. Using this data, I reasoned that the higher count of people using the turnstiles can represent higher foot traffic. The same reasoning was used on the data to find the stations with the highest count of people going through the turnstiles. I used aggregation to get the count of entries over a daily period. The purpose for providing this data is to illustrate the time of day to place the street teams at those turnstiles.  

## Data
The data analyzed for this project was the NYC MTA turnstile collected from their website link http://web.mta.info/developers/turnstile.html. The dates quered from the MTA data was from June 2021 to August 2021.   

## Algorithms
The first step was to aquire the data. I used SQLite to select narrow the data to the months of June 2021 to Auguest 2021. Afterwords I used cleaned the data to allow for an easier analysis. I used pandas to create a dataframe of the orignial data then further create sub-dataframes that were group by only the catagorizes I need to help present my ideas. Afterward, I used matplotlib to create a bar and line graph.   

## Tools
- SQLAlchemy was used to select the three months for the data analysis.
- Pandas and Numpy were used to create a data frame and perform calculations on the data.
- For the graphs, matplotlib libray was sourced.
