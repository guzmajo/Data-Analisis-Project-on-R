# Giovanni Guzman Portfolio
Data Analysis Portfolio

## Cyclistic Bike-Share

### Table of Content
<ul>
  <li><a href="#ask">A clear statement of the business task</a></li>
  <li><a href="#prepare">A description of all data sources used</a></li>
  <li><a href="#process">Documentation of any cleaning or manipulation of data</a></li>
  <li><a href="#analyze">A summary of your analysis</a></li>
  <li><a href="#share">Supporting visualizations and key findings</a></li>
  <li><a href="#act">Top recommendations based on your analysis</a></li>
</ul>

## Introduction

This is a capstone project as a part of my Google Data Analytics Professional Certificade course, Using Tools like RStudio for IDE and other such as SQL and Tableau Public to do the analysis and vizualization process. 

## For this project following data analysis steps will be followed :

- Ask
- Prepare
- Process
- Analyze
- Share
- Act

## Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand **how casual riders and annual members use Cyclistic bikes differently.** From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

#### Characters and Teams

- **Cyclistic**: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.
- **Lily Moreno**: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.
- **Cyclistic marketing analytics team**: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.
- **Cyclistic executive team**: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

## Ask <div id="ask"></div>

Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

Moreno has assigned you the first question to answer: **How do annual members and casual riders use Cyclistic bikes differently?**

### Key tasks 

1. Identify the business task 

Maximizing the number of annual members on Cyclistic Bike-Share: To achieve this goal is necessary to know the behavior and characteristics of casual riders and annual members to know How to do annual members and casual riders use Cyclistic bikes differently, why would casual riders buy Cyclistic annual memberships and How can Cyclistic use digital media to influence casual riders to become members.

To do that make a data analysis is a must in order to analyze the Cyclistic historical bike trip data to identify patterns that help the Cyclistic Executive Team to make a decision about the marketing program.


2. Consider key stakeholders


![Stake-Holders](https://github.com/guzmajo/Giovanni_Portfolio/blob/main/StakeHolders.png)


## Prepare <div id="prepare"></div>

### Key tasks 

1. Download data and store it appropriately. 
2. Identify how it’s organized. 
3. Sort and filter the data. 
4. Determine the credibility of the data.

### Data sources

I will use Cyclistic’s historical trip data to analyze and identify trends. [Download the previous 4 quarters of Cyclistic trip data here](https://divvy-tripdata.s3.amazonaws.com/index.html). The data has been made available by Motivate International Inc. under [license](https://ride.divvybikes.com/data-license-agreement), The data set is public and contain details about the type of bike that the members are using and information such the start and end station, the start and end date and the time that the users spend on each Ride. 

in order to sort and filter the data, the first step was storing the databases in a new folder and renaming the folder with the company’s name, for the process of filtering the data the tool was Excel and each database was sorted by the started date of the riding.

In the column below there is a description of each column:

![Column_info](https://github.com/guzmajo/Giovanni_Portfolio/blob/main/description_column.png)

The data source is:

- Reliable
- Original
- Comprehensive
- Current
- Cited

## Process <div id="process"></div>

### Key tasks 

1. Check the data for errors. 
2. Choose your tools. 
3. Transform the data so you can work with it effectively. 
4. Document the cleaning process.



Here is the [Documentation](https://github.com/greyisbetter/Cyclistic-Bike-Share/blob/main/data-process.md) for each step of **Data Process**.

## Summary of analysis
<div id="analyze"></div>
1. In the top 15 most traffic stations, we have a higher number of casual riders than annual members and the order deficit ratio seems to be inverted.
![Top-stations-usertype-proportion](./charts/Top-stations-usertype-proportion.png)

2. Despite the casual riders being only 43.68%, their average time and distance is higher than the annual members.
**Casual riders and Annual Members distribution**
![usertype-distribution](./charts/usertype-distribution.png)

**Average Time and Distance of Casual and Annual Members**
![time-and-distance](./charts/time-and-distance.png)

3. Casual riders use only a few stations in the city of Chicago, while annual members use stations across the city.
**Top 50 Casual Rider's Home Stations**
![top-50-casual-home-stations](./charts/top-50-casual-home-stations.png)

**Top 50 Annual Members's Home Stations**
![top-50-annual-home-stations](./charts/top-50-member-home-stations.png)

4. A major difference that shows that 13.55% of casual riders use docked bikes in place of classic bikes, but this is not the case with the annual members.
**Bike Choice of Casual Riders**
![casual-rider-bike-priority](./charts/casual-rider-bike-priority.png)

**Bike Choice of Annual Members**
![annual-rider-bike-priority](./charts/annual-rider-bike-priority.png)

5. Casual riders mostly use bikes on weekends while annual members have more bike usage than casual riders in the long run.
**The average traffic of Casual and Annual members in a Week**
![weekly-traffic](./charts/weekly-traffic.png)

**The average traffic of Casual and Annual members in a Month**
![daily-traffic](./charts/daily-traffic.png)

**The average traffic of Casual and Annual members in a Year**
![monthly-traffic](./charts/monthly-traffic.png)

## Supporting visualizations and key findings <div id="share"></div>
The visualizations should clearly communicate your high-level insights and recommendations. 
[Link of the Visualization Dashboard](https://github.com/greyisbetter/Cyclistic-Bike-Share/blob/main/Dashboard.pdf)

## Recommendations based on your analysis
<div id="act"></div>
1. As we can see, casual riders use Cyclistic-bikes at specific stations where we have a high number of bikes usage.
2. We can show the ease of use of docked bikes for annual members in that specific area.
3. How can being an annual member be more rewarding for using Cyclistic-Bikes on weekends.
4. How can being an annual member be of more helpful when using Cyclistic-bikes for longer routes.
