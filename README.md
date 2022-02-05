# bikesharing

## Background

Kate suggests that you use Citi Bike data that has been released to the public for your analysis. You agree, but then remind her that you must be cautious when looking at the data, as it applies specifically to New York City—Des Moines is quite different!

You're excited to find out which data will and will not apply to Des Moines, drawing on both your data expertise and critical thinking skills. You'll also need to rely on Kate's salesmanship during the investor conversations. Kate can sell almost anything, but it's up to you to make sure she's selling something viable.

This zip file contains all the August 2019 data. We'll use data from August because there is likely more traffic during the summer months.

You know that you want to use Tableau to create effective visualizations from the Citi Bike data, which Kate can then use to impress potential investors. You also know that the key to getting a good visualization—and, really, any good data analysis—is to start with a question. But what is the right question to ask and how do you portray the answer accurately?

## Overview of Project

The core issue we need to think about is what we absolutely need to know in order to create our bike-sharing program in Des Moines.

Once you know the questions you want to ask, the next thing you need to think about is how your audience will perceive the data you present. You want to share your findings in a way that reduces your personal bias and accurately represents what the data is saying.

Honesty and integrity in regard to your data is an important concept in data science. A person's opinion can be swayed based on how the data is represented, so you need to consider how your audience will perceive and interpret the results and visualization that you show them.

What's the total bike trips in August? Another piece of data you'll want to look into is the number of short-term customers and annual subscribers to the Citi Bike service. This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines. Specifically, you want to find out how the proportion of short-term customers to annual subscribers has changed. Next we want to explore the types of customers. In particular, we want to find the proportion of short-term customers of the bike service to the annual subscribers. Within the Usertype dimension, you'll notice that there are two types of users: subscribers and customers. "Subscribers" refers to annual subscribers of the bike-sharing service, while "customers" are the short-term riders. We now know the breakdown of rider types in New York City, which will help us predict the customer breakdown in Des Moines and, in turn, propose a business model to investors.

A key piece of data we need is the peak usage hours for the month of August. This will help us get a better idea of how many bikes we might need in Des Moines, as well as figure out during which parts of the day we'll need the most bikes. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that.

What are the highest-traffic locations? Understanding both when and where people use Citi Bike will help you plan your pilot in Des Moines. We'll be creating a basic symbol map to visualize the top 10 starting locations. A symbol map is a map with symbols that correlate to the numeric value of the map location. The most popular starting locations will be marked by larger symbols on the map.

Another question we have for the data—beyond the where and when—is the who. What can the data tell us about the riders themselves? Often, the first place we start when understanding a population is gender.

You've unpacked the when, the where, and the who, but what about "how long"? You need to determine the average ride duration. We know the breakdown of riders by gender, but learning other details about the riders will further assist our analysis. Let's take a look at the average duration of a bike ride, by age. This will help us set expectations for trip duration in Des Moines.

What might the key costs be in a bike-share business? You mull over this question until inspiration strikes: beyond the initial setup, bike maintenance will likely be one of the biggest expenses. So, what can the data tell us about the upkeep bikes might need? A likely concern of investors is the cost of bike upkeep. The bikes used most frequently will probably be the ones that require the most maintenance, so we'll need to determine which bikes have the highest sum of "Number of Rides."

Your investors are curious about the bike utilization during the month of August. You'll need to show the utilization of each Citi Bike in New York City. This will continue to help you understand the needs of a bike-sharing business in Des Moines. Now that we've found the number of trips per bike during the month of August, we should figure out how long those rides are and if there are bikes that need more attention than others. We'll use the bike ID as a metric for this part of the analysis and create a packed bubbles visualization.



### Purpose

1. How many bike trips were recorded during the month of August? Since August is a beautiful time of the year to rent a bike, we want to use this data as a starting point to determine how many rides we could expect in the city of Des Moines.
2. How does ridership grow over time? What is the proportion of short-term customers to annual subscribers?
3. What are the peak riding hours in the month of August?
4. What are the top bike stations in the city for Starting a journey?
5. What are the top bike stations in the city for Ending a journey?
6. What is the gender breakdown of active riders? Citi Bike tells us that 0 represents "Unknown," 1 represents "Male," and 2 represents "Female."
7. What is the average trip duration by age? In general, the later the birth year, the longer the ride duration.
8. Which bikes are most likely de for repair?
9. How variable is bike utilisation?










## Analysis And Challenges

## Methodology: Analytics Paradigm

#### 1. Decomposing the Ask

[Purpose](#purpose)

#### 2. Identify the Datasource
From https://ride.citibikenyc.com/system-data.
August 2019 data: 201908-citibike-tripdata.csv.zip

### 3. Define Strategy & Metrics
**Resource:** Tableau

#### 4. Data Retrieval Plan
Stated in [2. Identify the Datasource](#2-identify-the-datasource)

#### 5. Assemble & Clean the Data

#### 6. Analyse for Trends

#### 7. Acknowledging Limitations

#### 8. Making the Call:
The "Proper" Conclusion is indicated below on [Summary](#summary)

## Analysis

>Deliverable 3: Dark Mode

![Dark Mode](resources/dark.png)

## Summary


## Appendix

Leaflet Quickstart Guide: https://leafletjs.com/examples/quick-start/

Changing the map's style

```
mapbox/streets-v11
mapbox/outdoors-v11
mapbox/light-v10
mapbox/dark-v10
mapbox/satellite-v9
mapbox/satellite-streets-v11
```

Setup push to branch with the command below and later work as usual in this branch
```
git push --set-upstream origin Simple_Leaflet_Map
```

---
Git Learning Lab: https://lab.github.com/
Git Branching & Merging: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
