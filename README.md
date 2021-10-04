# Uber_Data_Analysis
Uber Data Analysis using Python


Case study - Uber Data Analysis

We have the uber drive data for a driver which captures the differnet aspects of driving behavior. We are going to grill this data and report the important findings from the grilling and drilling exercise. We will also provide some useful insights about the trip behaviour of a Uber driver. Let us try to dive into the data with pandas and numpy by our side!

Dataset -
There are two datasets to be used here. The dataset contains-

Uberdrive.csv

- Trip_Id - Id for the trip
- Start Date - the date and time of the start of the trip
- End Date - the date and time of the end of the trip
- Start Location - staring location of the trip
- End Location - location where the trip ended
- Purpose of drive - Purpose of the trip (Business, Personal, Meals, Errands, Meetings, Customer Support etc.)

Uberdrive_Miles.csv

- Trip_Id - Id for the trip
- Miles Driven - Total miles driven between the start and the end of the trip


Objective-
The aim is to create a driver profile based on the below aspects on driving behavior -

- Name and number of all the unique start and stop points
- Popular start and stop points
- Rides with same start and stop points
- Starting point from which most miles have been driven
- Start- stop pairs that are most travelled in terms of distance
- busiest month in terms of number of drives and miles driven
- busiest day of the week
- peak hours
- most frequent trip category
- most frequent trip purpose
- miles driven per category and purpose
- percent composition of business miles vs personal miles
- time spent per category and purpose
