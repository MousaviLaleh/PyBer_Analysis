# PyBer Analysis
Analyzing and visualizing ridesharing data using Python, Pandas, Numpy and Matplolib.

### Softwares

  - &#160; Python 3.6.1 (64-bit) : &#160;  [Python 3.6.1](https://www.python.org/downloads/windows/) <br/>
  - &#160; Anaconda3 : &#160;  [Anaconda 64-Bit Graphical Installer](https://www.anaconda.com/products/distribution)<br/>

## Overview

The purpose of this project is to perform exploratory analysis of PyBer ride sharing data in order to gain an understanding of ridership and fare metrics by the type of cities in which Pyber operates, and also Creating visualizations of rideshare data for PyBer to help improve ride-sharing services and determine affordability for underserved neighborhoods.
<br/>

## Ride-sharing Summary by City Type
There is three city type in the dataset: 
  -  Rural
  -  Suburban
  -  Urban

  

By taking the [following steps](images/03.png):
  - Calculate the total number of rides for each city type
  - Calculate the total number of drivers for each city type
  - Calculate the sum of the fares for each city type
  - Calculate the average fare per ride for each city type
  - Calculate the average fare per driver for each city type

  The PyBer summary DataFrame is formatted as shown

  ![02.png](images/02.png)
 
By reviewing the summary we can see that there are several key findings including:
  - Urban cities have the highest ridership demand while rural cities have the least.
  - Urban cities have 4x+ more drivers than suburban cities.
  - Suburban cities have 6x+ drivers than rural with almost 4.5x the revenue.
  - Rural cities have the highest average fare per ride and driver.
<br/>   
   
## A multiple-line Chart of Total Fares for each City Type
Using Pandas and two new functions, pivot() and resample(), by two steps:
  - Create a new DataFrame to show the total fare amount for each date
  - Resampled DataFrame using the object-oriented interface method and make a graph

![04.png](images/04.png)

<br/>


## Summary
The business recommendation to PyBer :
Increasing the number of drivers in Rural areas to ensure there are enough drivers to meet ride demands.<br/>
Data for rural cities shows that the average fare per ride and the average fare per driver is much higher than suburban and urban cities.This can indicate that rural area based riders are taking trips over a longer distance. This can result in a majority of drivers being occupied with current trips and loss in potential revenue when there are peaks in business.

