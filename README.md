## PyBer Rideshare Data Analysis

## Overview

### Purpose of Project
The purpose of this new analysis was to combine different data sets into one and analyze and compare the ride sharing data between the different city types. Creating a dataframe using Pandas we were able to easily create and calculate summary statistics across the Urban, Suburban, and Rural city types.  Using Matplotlib we were able to provide helpful visual representations of the data weekly revenues. The visual representations provide a powerful symbol to summarize the data and help us detect trends and make inferences from the data.

### Project Resources
- The data that was used in this project can be found within the [Resources Folder](https://github.com/bbinvt/PyBer_Analysis/tree/main/Resources).
- The analysis of the data was performed within a Jupyter Notebook and can be [found here](https://github.com/bbinvt/PyBer_Analysis/blob/a7bbba06dacfb2d198e50bbdcf68517497371b6e/PyBer_Challenge.ipynb).
- The analysis included outputs that were saved as images; the images can be found within the [analysis folder](https://github.com/bbinvt/PyBer_Analysis/tree/main/analysis)

## Results

### Summary of the data
![image](https://github.com/bbinvt/PyBer_Analysis/blob/3081b37f14c48a3378610aea66dc163a50c2ff8d/analysis/summary_df.png)

![image](https://github.com/bbinvt/PyBer_Analysis/blob/3081b37f14c48a3378610aea66dc163a50c2ff8d/analysis/PyBer_fare_summary.png)

#### Analysis of Total Rides
It is interesting, though not entirely surpising, that the Urban city types record 13 times more rides than the Rural cities and 2.6 times more rides than the suburban cities. 

#### Analysis of Total Drivers
Like the Total Rides there are similar multiples when comparing the total number of drivers for each city type. The Urban cities experience 30.8 and 4.9 times more drivers than their Rural and Suburban counterparts respectively. 

#### Analysis of Total Fares
Given what we know about the total number of rides and the total number of drivers the differences between the total fares are expected. The Urban city types collect 9.2 and 2.05 times more fares than their Rural and Suburban counterparts respectively. 

Additionally, from the second image we can see that on a week to week basis the fares collected remain fairly stable for each of the cohorts - ie there are not wild swings from one week to the next. 

#### Analysis of Average Fares per Ride
When it comes to the average fare per city type, it is not suprising to see that the Rural city types have the highest average fare, followed by the Suburban and then the Urban city types. Given the differences in frequency one can easily imaginge that the a Rural rides are longer but far less in frequency. Urban rides collect the least amount of fares per ride, perhaps because they are short in duration though much more frequent. 

#### Analysis of Average Fares per Driver
On a per trip basis the Rural drivers can expect to earn 1.4 and 3.34 times more than their Suburban and Urban counterparts respectively. 

## Summary
### Business Recommendations
1. To better understand the ride data, there is another piece of criteria we should examine the average fare collected per mile (or KM) within each the city types. 
2. Collecting and calculating the average amount a driver could expect on a per mile (or per KM) basis could help with driver recruitment. 
3. As it stands it is most likely that we should be optimizing for the urban city centers however by collecting and calculating additional aspects of the ride share data we can figure out where to optimize our services to maximize revenues, or maximize margins per ride. 
