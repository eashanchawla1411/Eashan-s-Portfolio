# Telling Stories with Data Assignment 2

### Part 1: Adding a pre-built visual from [data.oecd.org]( https://data.oecd.org/)

**The graph below shows general government debt to GDP ratio for various countries.** This is a key indicator for the sustainability of government finance. 

<iframe src="https://data.oecd.org/chart/69BF" width="900" height="525" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/69BF" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

Even though the visual itself is simple and easily understandable, we can do a few changes to improve clarity:
1. Remove the background color to ensure that no focus is taken away from the data being represented. 
2. Chart title could be more clear. 

In the next section, I visualized the same data, but in a different way. 

### Part 2: Visualizing the same data using [Flourish](flourish.studio)

**Iteration 1:**

The first iteration shows a grid line of charts with one time series chart for each country. However, here, it's difficult to compare the ratios for all countries at a glance and judge how the countries do compared to each other over the years. 

<div class="flourish-embed flourish-chart" data-src="visualisation/4276039"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


**I visualized the same data using [Flourish](flourish.studio).**
Here, I tried multiple types of visualizations, each of which had their own pros and cons. 

**Iteration 2:** 

In this iteration, I created a bar chart with a filter for year. This would allow someone to understand the Debt to GDP ratio for different countries (for a particular year). The data was ordered in descending order to draw attention to high values of debt to GDP ratio. Ideally, I would have wanted to have a sequential color scheme throughout the bars, with darker colors indicating higher ratio values and lighter colors indicating low values. But, this was not possible to achieve in Flourish.  

<div class="flourish-embed flourish-chart" data-src="visualisation/4280910"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This iteration allows a user to filter on the year and compare the values for different countries together. Due to the presence of multiple columns/ bars, a certain shimmer effect is created that can be distracting. 

**Iteration 3:**

In this iteration, giving a filter for countries instead of year allowed for the creation of a time series graph (one for each country). 

<div class="flourish-embed flourish-chart" data-src="visualisation/4280878"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The idea was initially to have multiple lines indicating various countries in grey, and one country in color (the one that is selected). But, Flourish didn't allow me to do that. 

### Part 3: Visualizing the same data using Tableau

In this part, we will visualize the same data using Tableau. Here, I tried creating a sort of beeswarm plot/ heatmap, showing the same data in the easiest way possible. I chose this visual since it is very easy to understand by a quick glance, and the presence of diverging colors indicating a high / low ratio also help. 

<iframe src="https://public.tableau.com/views/DebttoGDPRatio/Year-over-YearDebttoGDPRatio?:showVizHome=no&:embed=true" width="100%" height="500" seamless frameborder="0" scrolling="no"></iframe>

##### [Back to the Telling Stories with Data Page](TSWD.md)
##### [Back to the portfolio home page](README.md)
