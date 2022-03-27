# Bikesharing

## Overview

Last summer me and my friend Kate took the trip of a lifetime.New York City for two full weeks exploring historic landmarks like Centrel Park,the Statue of Liberty, and Empire State Building.It was a megical expirience and as we flew home together you looked through our vacation photos and has a realization.One of the key ingredients to had a realization.One of the key ingredients to the magic was an unlikely suspect,Citi Bike.Myself and Kate had biked everywhere which allowed me to really get to know the city and intract with the people who live in there and who are using bikes for their commutes.

A gem of an idea starts to form in my mind.what if I could starta similar bike share buasiness for our hometown of Des Monies lowa.Me and Kate start brainstroming and few weeks later she calls me with some incredible news She has a potential angel investor who might be intrested in providing seed funding to explore a bike-share program in Des Moines.This is an exciting prospect but I know I have to think realistically.

The mechanism of making this bussiness work might be queite different in Des Moines than in New York City. I decide that the first step is to figure out how the bike-share bussiness actually works in New York City.From there I'll create proposal on how it might work in Des Moines. How ever I have data analytics expirience and I can take the lead on figuring out how this project might actually work.

## Data Source:

For this project, we'll use data from the Citi Bike program in New York City. This data includes a variety of fields, which we'll get to shortly. The data you'll download will be contained in a flat file, a CSV.

## Visualization:
[link to storyBook](https://public.tableau.com/views/BikeAnalysis_16475417477350/BikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Results
### Top starting Locations

This graph shows top starting locations name with count of city bikes start from this location.


![Top starting Locations](https://github.com/helanga/bikesharing/blob/main/images/TopstrtingLoc.PNG)


### Top ending Locations

This graph shows top startingending locations name with count of city bikes end  from this location.

![Top ending Locations](https://github.com/helanga/bikesharing/blob/main/images/TopendingLoc.PNG)

- The size of the circles and darkness of the blue/orange indicate the relative number of trips started at those locations. 

- It seems like with highest count of rides bikes are starting/ending with Manhan Island.

### Peak Riding Hours

![Peak Riding Hours](https://github.com/helanga/bikesharing/blob/main/images/peakridinghours.PNG)

- Highest activity hours are from 5.00 PM to 7.00 PM and in this hours required most resources (bikes).

- Relatively low bike usage during Wednesday's end-of-day

- Low-usage hours  arevbetween 2 AM and 5 AM. These hours would be the best times to conduct bike repairs
### Trips by Gender 

![Trips by Gender](https://github.com/helanga/bikesharing/blob/main/images/TripsbyGender.PNG)

- Male city bike users has the highest count of trips on Thursday 5PM to 7PM

### User Trips by Gender by week day

![T=User Trips by Gender by week day](./bikesharing/images/usertripsbyGender.PNG)

- Male subscribers has hieghest city bike usage on Thursdays.


### Trips by Weekday per Hour

![Trips by Weekday per Hour](https://github.com/helanga/bikesharing/blob/main/images/Tripsbyhour.PNG),

- It seems most of the people in NY city prefered to use citybikes 8 AM to 9AM in the morning and 5PM to 7PM in the evening.

### Bikes due for Repair
![Bikes due for Repair](./bikesharing/images/BikesRepair.PNG)

- This Graph shows each bike id's total number of trips.
    - dark blue for highest trip count
    - light blue/white for less trip counts
- So the bike id's with hiest trip count need most recent repairs.


### Checkout times

![checkout times](./bikesharing/images/checkouttimes.PNG)

- NYC Bikes most of the trips taken on under an hour length.


### Checkout Times by Gender

![checkout by gender](./bikesharing/images/checkouttimesGender.PNG)

- This breakdown shows ride duration by gender.

- Hieghest number of rides are taken by males.


## Summery

Acording to statistical analysis highest number of bike rides starting and ending from Manhatten Island renting by male subscribers during morning and evening office rush hours.

So this implicit in momth of August most of NYC bikes rides taken by office staff working in NYC.

Two additional visualizations that I would perform with the given dataset.

Top 15 Start Locations

![Bikes due for Repair](./bikesharing/images/top15Strat.PNG)

Number of Trips by Birth Year(Age)

![Bikes due for Repair](./bikesharing/images/birthyear.PNG)
 
