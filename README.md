# Interactive NYC Accidents Shiny Application

### EDAV Final Project
### Author: Xiaochun Ma
### Date: April 20, 2018
### Interactive Shiny App: https://xiaochunma.shinyapps.io/NYPD_accidents_shiny/

## Introduction

The NYPD adds and updates new records each month for the NYPD Motor Vehicle Collisions dataset(https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95). Each record in the data represents a collision in NYC by city, borough, precinct and cross street. 

The objective was to make this data interactively visiable to the audience so that the users are able to explore patterns with respect to accidents/injuries/death. 

For this final project, a Shiny application was developed that allows users to work with an interactive map and see accidents, injuries and death locations and relative number which match a users-specified selection of criteria. In developing the interactive application, the data was selected by specifying the latest 10,000 records in 2018 for quick rendering and use of the map. Details of instructions, proposed analysis and hypothesis are provided in this final summary.

## Proposed Analysis and Hypothesis

### Task 1: Visualize the accidents/injuries/death on the map:

Users can choose the index in the Accidents Explorer:
* Accidents
* Injuries
* Death

And the corresponding dots representing the index would show up on the map. With legend on the bottom left corner, users can easily find the dots with different color representing corresponding number of accidents/injuries/death.
Users can also choose “Add Cluster” to visualize the clustering effects of the accidents/injuries/death on the map.

### Hypothesis 1: Buiser areas(midtown, downtown and harlem) have more accidents

It can be seen from the picture that these three areas have more accidents than other areas. So this hypothesis is tested to be true.

<img src="https://github.com/mxc19912008/readme_pics/raw/master/image/cluster.png">  

### Hypothesis 2: Large scale injuries tend not to happen in Manhattan since the speed limits are lower and this district has more traffic lights.

It can be seen from the picture that large scale injuries(marked by red arrow) tend to happen in other district. So this hypothesis is also tested to be true.

<img src="https://github.com/mxc19912008/readme_pics/raw/master/image/injuries.png">  

### Task 2: Visualize the accidents/injuries/death regarding each type of vehicles on the map:
Other than choosing All Vehicles, users can choose one of these vehicles to visualize:
* Ambulance
* Bicycle
* Bus
* Fire Truck
* Large Commercial Vehicle
* Livery Vehicle
* Motorcycle
* Passenger
* Pick-up Truck
* Scooter
* Small Commercial Vehicle
* Sport Utility/Station Wagon
* Taxi
* Van

<img src="https://github.com/mxc19912008/readme_pics/raw/master/image/choose.png">  

### Task 3: Visualize the accidents/injuries/death across time(hour) on the map:

Users can also visualize the number of accidents/injuries/death across time(hour) on the side column. In this way, users are able to check the distributions of accidents/injuries/death over time.

### Hypothesis 3: More accidents happen during rush hours(7-9,16-18) than other time.

It can be seen from the barchart that there are more accidents which happened during rush hours(7-9,16-18) than other time slots. So this hypothesis is also tested to be true.

<img src="https://github.com/mxc19912008/readme_pics/raw/master/image/time.png">  

## What can be done with our analysis?

* Send more police to the busier areas;
* Send more police during rush hours;
* Reduce speed limit for spots that have more injuries.

## Future work

Due to the limit of time, we did not incorporate weather data. If we can incorporate weather data, the exploration of snow/rain vs accidents/injuries/death can be done.

We could have incorporate events and activities to see if the accidents are related to events and activities.

We could also have made time interactively be chosen so that we can get to know where to send more police at what time periods.

If we have bigger RAM, we would have input more data, which would give more robust analysis.

