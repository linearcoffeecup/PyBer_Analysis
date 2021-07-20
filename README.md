# PyBer_Analysis

## Overview of the analysis

In this analysis, it was required to gather key data for evaluation.  The calculated data supports a comparison across different driving-areas and considers the number of rides, the number of drivers, and fares as input.  The results of the analysis are used to gain insights on PyBer business in cities located in urban, suburban, and rural areas.  The figures of merit chosen are the total number of rides, fares, and drivers, as well as the average fare per ride and per driver for each city which Pyber serves.  The input data is from [city_data.csv](https://github.com/linearcoffeecup/PyBer_Analysis/blob/main/Resources/city_data.csv) and [ride_data.csv](), and are presented in DataFrame and Pandas plot formats.

The general steps in this analysis were:

- Read the input files and create two data frames
- Merge the two data frames
- Use Pandas methods to find the total number of rides and fares
- Create a separate data frame to find the number of drivers because of multiple entries in the first data frame causing over counting
- Calculate the average fares per ride and per driver
- Present the results in a formatted data frame
- Present results of raw data in a line plot

## Results:






## Summary:

business recommendations to the CEO for addressing any disparities among the city types

The average fare per driver is much greater that average fare per ride in rural areas.  This suggests that drivers are making more than one trip.  The number of trips could be decreased by adding more drivers.

The average fare per driver is lower than the average fare per ride in urban areas.  One solution is to increase the fares for urban city drivers, especially during the busy time of the year which could be defined fares in months relative to the month of January.

The average fare per driver is greater than the average fare per ride for suburban areas.  The two averages could be made closer by sharing drivers between urban and rural cities during the year.
