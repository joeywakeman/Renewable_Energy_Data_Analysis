# Exploratory Data Analysis of Renewable Energy Since 2000
In this project, I clean, explore, and visualize a dataset of global renewable energy metrics since the year 2000. 


## Goals
- gain an understanding of renewable energy metrics across countries and continents in the modern-day
- discover how financial aid for renewable energy development has affected renewable energy metrics since 2000


## Major Takeaways
- there is a negative correlation between the productivity/wealth of a nation and the clean energy share of their energy consumed
- financial aid for renewables strongly correlates with access to electricity, GDP per capita, and renewable energy production capacity
- African nations dominantly lead the world in clean energy share
  
## A Few of the Visualizations
![output_28_0](https://github.com/joeywakeman/renewables/assets/144757059/acb082fd-7a67-4483-9ebb-377d54ac5721)

The bar chart above displays the top 50 countries in the world with the highest clean energy share of energy consumed in the most recent full year of our dataset. Africa clearly dominates the world in the percentage of energy consumed from clean sources. For this visualization, I cleaned the data, sorted it by clean energy share, joined it with a continents dataset, and then plotted it using seaborn and matplotlib.


![output_40_0](https://github.com/joeywakeman/renewables/assets/144757059/6a487763-a444-475d-b3c6-b780f01e7ea0)


The jointplot above shows scattered points that each represent data from one country in 2019. It shows that higher GDP per capita is correlated with higher energy consumption per capita. This implies that either high energy use leads to high productivity and wealth, or high productivity and wealth leads to high energy use. For this visualization, I used seaborn and matplotlib to overlay a regplot on a jointplot.

![output_36_0](https://github.com/joeywakeman/renewables/assets/144757059/900704f1-3956-45d9-9324-d82367ca69f4)

The correlations plot above shows correlations between various renewable energy metrics in our dataset. Wealthy nations seemingly have widespread access to electricity, use a high amount of energy, generate a high amount of energy, and rely mostly on unclean energy. Less wealthy nations have less access to electricity, use less energy, generate less energy, and rely more on renewable energy.

## See my code
Don't forget to click the tab, "Renewable_Energy_EDA.ipynb," to view my code and full, in-depth data analysis project!
