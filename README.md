<h1 align="center">VAST 2019 - Mini Challenge 1</h1>
  
This Project deals about Crowdsourcing for Situational Awareness which is a part of VAST 2019 - Mini Challenge 1 dataset.
[Link : https://vast-challenge.github.io/2019/MC1.html]
  
## INTRODUCTION
  
St. Himark has been hit by an earthquake, leaving officials scrambling to determine the extent of the damage and dispatch limited resources to the areas in most need. They quickly receive seismic readings and use those for an initial deployment but realize they need more information to make sure they have a realistic understanding of the true conditions throughout the city.

<p align="center">
  <img src="https://github.com/AshiniAnantharaman/Visual_Analytics_Project/blob/main/St.Himark_Map.png" />
</p>

In a prescient move of community engagement, the city had released a new damage reporting mobile application shortly before the earthquake. This app allows citizens to provide more timely information to the city to help them understand damage and prioritize their response. In this mini-challenge, app responses are used in conjunction with shake maps of the earthquake strength to identify areas of concern and advise emergency planners. 

## OVERVIEW
The main objective of the project is to analyze the situation in St.Himark and decide using various factors like the damage ratings on *roads and bridges*,  *power*, *medical*, *buildings*, *sewer and water* and *shake intensity* on various locations which needs immediate assistance. Also since it is an application used by the public there are chances of uncertainity in the data which also needs to be verified.

The dataset contains a location number, date and ratings of each fields mentioned below starting from 1 - 10 based on the amount of damage.

## TOOLS USED
1. Python 
2. Tableau
3. Google chart

## STEPS INVOLVED IN THE PROJECT
1.  Data Pre-Processing
2.  Data Exploration
4.  Data Visualization
5.  Data Analysis
6.  Conclusion
7.  Future Work

### 1. Data Pre-Processing
This steps is where the dataset is taken and the count of records and number of missing values were recorded. It also deals with basic correlation and the five point summary statistics of all the categories.
    
### 2. Data Exploration
The data was further explored by generating a report using Python Sweetviz which will explain the statistics of each category and the data distribution in each field. The highest number of ratings were calculated with respect to the dates and also with respect to different locations. A box plot was plotted for all the categories and it was figured that there were some outliers. Also, heatmaps were plotted for all the null values in each category.
    
### 3. Data Visualization
 - The data was further visualized using Bubble Chart which explaints the distribution of ratings in each day and hour in the lowest and highest response region: Wilson Forest and Scenic Vista.
 - Heatmaps were generated for each category using filters on days and time in tableau to get a quick understanding of how the regions are affected. Few anomolies were noticed in the shake intensity map.
 - To further analyze the anomoly, a google chart was used to plot the Location vs these five categories to get a comparative study. It further confirmed the difference in shake intensity.
 - A tabular chart was used to give a detailed report of three neighboring places like safetown, oldtown and easton and this confirms the unreliability in the data.
 - Videos were created (like a time temporal in QGIS) using various dates and hours using a python code for all the category.

### 4. Data Analysis
Below are the questions which are answered after the visualization and alaysis  
 - How to prioritize the neighborhood
 - Which parts are most affected
 - Uncertainity in the data.
 - Reliability in neighborbhood reports
 - Change of conditions over time

## CONCLUSION
Based on the above analysis, at specific time period it was possible to determine which area was most impacted by the earthquake for these categories but it was also evident that there can be instances of uncertainty in the data. The above questions were answered using various visualizations and tools.

## FUTURE WORKS
To enhance the geographical analysis, tools like QGIS can be used to create a time temporal for the entire time period of this earthquake in a real time basis with a heatmap that depicts an alert based on the ratings provided by the citizens. Also, models like Bayesian time series can be use for efficient statistical analysis of the given features which will be reliable and not time consuming.


  
