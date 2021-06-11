# Google Data Analytics Program on Coursera

## Case Study 1: Cyclistic Full Year Analysis

### Introduction

This R markdown notebook is an analysis is for Case Study 1 as part of the Google Data Analytics Certificate on Coursera.  Its originally based on the case study "'Sophisticated, Clear, and Polished’: Divvy and Data Visualization" written by Kevin Hartman found [here](https://artscience.blog/home/divvy-dataviz-case-study). 

I will be using the Divvy data set for the case study found [here](https://divvy-tripdata.s3.amazonaws.com/index.html), between the dates of 2020-05-01 and 2021-04-30. 

The purpose of the R markdown is to consolidate the downloaded Divvy data into a single dataframe, then conduct an exploratory data analysis, and produce some visualizations to help answer the key question: “In what ways do members and casual riders use bikes differently?”

### Background

The following is taken from the background information on the fictional company in the case study:

A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, the Marketing Manager believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, the Marketing Manager believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

The Marketing Manager has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. The Marketing Manager and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

The Marketing Manager has assigned us the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?
