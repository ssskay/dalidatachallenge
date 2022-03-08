# Sara Kay DALI Data Challenge 22W
## Part 1
For this challenge I made 4 different types of graphs. For the map graphs, I used geopandas which is powered by matplotlib. All other graphs were done using altair. 

When I intially saw the data, my first instinct was to try and put it on a map since the data set has lots of global representation and I wanted to convey the global nature of the data. The most informative metric to me seemed to be the income inequality as noted in the gini_reported score. In my first visual, I wanted to show the changes of income inequality over time, since the higher the gini index is, the greater the inequality is. I filtered the data and decided to compare the gini index of countries in the 1980s and 2000s to see how inequality has changed over time. 

![plot1](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/Income%20Inequality.jpg?raw=true)


For my next plot, I wanted to use the countries that were the most represented in the data and thought population growth would be an interesting metric to track. However, one thing I found was that certain countries, such as China and India, had exponentially larger population growths. I tried experimenting with log, but ultimately made my plot interactive through altair, which allowed me to insert the specific country name if someone zoomed in and hovered over it. While this still made it harder to show the population growth of the other countries, I think the narrative of China's explosive population growth is cool to see in this visual. 

![plot2](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/Popgrowth1.png?raw=true)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/Popgrowth2.png?raw=true)

As mentioned before, income inequality seemed to be a main factor in this data, so I wanted my visuals to reflect that across different countries and continents. After looking up more details about this data, I found that the recently added 'gdp_ppp_pc_usd2011' variable could be another useful indicator of inequality and wanted to look at the scores of the poorest countries compared to the richest countries and see which continents were the most represented in both graphs. Unsurprisingly, European countries were the richest and countries in Africa and Asia were the poorest.

![plot2](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/TopPoorest.png?raw=true)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/TopRichest.png?raw=true!)

Finally, I wanted to visualize the simplified metric that was provided of overall income level of the different countries by continent in the pie chart, which could show at a glance which continents had the lowest income levels by a percentage. This visual is a more general view compared to the bar charts above since it doesn't specify which countries are the poorest and emphasizes the continents instead.  

![plot2](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/IncomeOceania.png?raw=true)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/IncomeAmericas.png?raw=true!)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/IncomeAfrica.png?raw=true!)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/IncomeEurope.png?raw=true!)
![plot3](https://github.com/ssskay/dalidatachallenge/blob/main/part1viz/IncomeAsia.png?raw=true!)
