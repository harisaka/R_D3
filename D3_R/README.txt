# Data Journalism and D3
## Background

Analyze the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand findings.

The news paper needs to run a series of feature stories about the health risks facing particular demographics. Our task is to comb through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml), but you are free to investigate a different data set. The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."


## Your Task

### 1: D3 Dabbler

Create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3, create a scatter plot that represents each state with circle elements. 
Will code this graphic in the `app.js` file of said directory—making sure to pull in the data from `data.csv` by using the `d3.csv` function. 
The scatter plot should ultimately appear like the image at the top of this section.

* Include state abbreviations in the circles.

* Create and situate  axes and labels to the left and bottom of the chart.

* Need to use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in web browser.

- - -

### 2: Interactive portion

Lets make interactive page for our data!

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

Lets include more demographics and more risk factors. Place additional labels in  scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.


#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. 
Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. 
Add tooltips to circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.




- - -