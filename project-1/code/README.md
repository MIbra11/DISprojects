# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference

### Overview

my first module in DSI covers:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA
- working with Jupyter notebooks for development and reporting

## Problem Statment
For my first project, i'm going to take a look at the number of traffic accidents and driving licenses issued in Saudi Arabia. I'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia.
in this project , i will try to verify of increase the driving licenses and traffic accidents , and what's the region and year have the maximum numbers of driving licenses issued and the region and year have the minmum numbers of driving licenses issued and the same thing withe traffic accident which region and year have the maximum numer of accident and and i try to compare between the two datasets and explain what i notes and what we achieve frome each one and i also apply what i study in my cours .

## Executive Summary
first i have description for the datasete then i have to load and display it and detect which data need to clean then clean the corrupted data and additional features then rename the features to lower case and replace the spaces with underscore to make it easy to access and deal with it when i coding . also i create a data dictionary which contain all features and description for them then visualization the data and descripe it staticaly .

## Datasets

#### Datasets Description

[Driving Licenses](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets)
This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

[Traffic Accidents and Casualties](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period)
This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.

#### Data Dctionary 
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**	                        | integer  |Driving_Licenses| the year of  the licenses issuance | 
|**region**                   	| object   |Driving_Licenses| the region where the licenses issuance| 
|**driving_licenses**            	| int      |Driving_Licenses| Number of Driving Licenses| 
|**y**                          	| float    |Driving_Licenses| the longitude of the region | 
|**x**                         	| float    |Driving_Licenses| latitude of the region| 
|**year**                           | int      |Traffic_Accidents| the year of traffic accidents and casualties |
|**region**	                        | object   |Traffic_Accidents| the region wher traffic accidents and casualties |
|**indicator**                      | object   |Traffic_Accidents| contain the description of  value featur numbers there is two description in it 'No. of Casualties - Injured' , 'No. of Casualties - Dead' and No. of Accident |
|**value**                          | int      |Traffic_Accidents| contain the numberd which was descripted in indictor |
|**y**                          	| float    |Traffic_Accidents| the longitude of the region | 
|**x**                         	| float    |Traffic_Accidents| latitude of the region| 


## Outside Research
in my blog i write a research about
[ traffic accidents](https://modhi-almannaa.blogspot.com/2020/12/accidents-definition-of-traffic.html)

 
## Conclusions and Recommendations
 by analyzing the data i notes that evrey year the number of Driving Licenses issued are increase especially in the big cityes which make the number of car accidents is increasing also . I suggest placing more surveillance cameras and increasing the value of fines to deter violators of the regulations and impose more penalties on them and increase traffic signals at intersections to regulate traffic and distribute the start and end times of the employees to reduce traffic congestion

