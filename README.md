# Insights from City Supply and Demand Data

## Objective:  Using the data, solve for the following questions

### Data Description

Rows in dataset:

+ Date: Day of Year
+ Time (Local): Local time in 24 Hour Clock (Ie. 2 PM is 14:00)
+ Eyeballs: Number of people who opened the Uber App
+ Zeroes: Number of Customers who did NOT see a car
+ Completed Trips: Total number of completed trips from the Customer requests
+ Requests: Number of Customer Requests asking to be picked up
+ Unique Drivers: Total number of unique driver online
  - Should instances where there are no drivers available count?

### Questions

#### Section 1: Completed Trips

1. Which date had the most completed trips during the two week period?
2. What was the highest number of completed trips within a 24 hour period?
3. What is the weighted average ratio of completed trips per driver during the two week period?

#### Section 2: Requests and Zeroes
1. Which hour of the day had the most requests during the two week period?
2. What percentages of all zeroes during the two week period occurred on weekend (Friday at 5 pm to Sunday at 3 am)? 
3. In drafting a driver schedule in terms of 8 hours shifts, when are the busiest 8 consecutive hours over the two week period in terms of unique requests? A new shift          starts in every 8 hours. Assume that a driver will work same shift each day.

#### Section 3: Supply & Demand + True or False
1. Looking at the data from all two weeks, which time might make the most sense to consider a true "end day" instead of midnight? (i.e when are supply and demand at both        their natural minimums)
2. In which 72 hour period is the ratio of Zeroes to Eyeballs the highest?
3. If you could add 5 drivers to any single hour of every day during the two week period, which hour should you add them to? 
4. True or False: There is exactly two weeks of data in this analysis
5. True or False: Driver supply always increases when demand increases during the two week period.
