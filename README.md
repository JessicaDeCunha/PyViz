# Toronto Real Estate Analysis with Pyviz

## Background

This dashboard's goal is to provide charts, maps, and interactive visualizations that help customers explore Toronto Real Estate data and determine if they want to invest in rental properties in Toronto.


The data provided was retrieved from the following websites:

* [Toronro Open Data](https://open.toronto.ca/)

* [Census Profile, 2016 Census - Toronto Metropolitan Area, Ontario and Canada](https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CMACA&Code1=535&Geo2=PR&Code2=01&SearchText=toronto&SearchType=Begins&SearchPR=01&B1=All&TABID=1&type=0)

---
## Notebooks

### Rental Analysis

You will find all of the calculations and visualizations in the rental analysis notebook.

#### Dwelling Types Per Year

In this section, I have calculated the number of dwelling types per year and visualized the results as a bar chart using the Pandas plot function.

#### Average Monthly Shelter Costs in Toronto Per Year

In this section, I have visualized the average monthly shelter costs per year to understand rental income trends over time. The average (mean) shelter cost for owned and rented dwellings per year has been visualized with multiple line charts.

#### Average House Value per Year

In this section I have determined the average house value per year. An investor may want to understand better the sales price of the rental property over time. For example, a customer will want to know if they should expect an increase or decrease in the property value over time so they can determine how long to hold the rental property.

#### Average Prices By Neighbourhood

In this section we compare the house value by neighbourhood.

#### Number of Dwelling Types per Year

In this section, I have visualized the number of dwelling types per year in each neighbourhood. There is a tool provided for investors to understand the evolution of dwelling types over the years.

#### Top 10 Most Expensive Neighbourhoods

In this section, we figure out which neighbourhoods are the most expensive. The mean house value for each neighbourhood is calculated, we then sort the values to obtain the top 10 most expensive neighbourhoods on average. Results are plotted as a bar chart.

#### Neighbourhood Map

In this final section, you will read in neighbourhood location data and build an interactive map with the average prices per neighbourhood. Use a scatter Mapbox object from Plotly express to create the visualization. Remember, you will need your Mapbox API key for this.

Remember that to create maps visualizations using Plotly Express, you will need to create an account at [mapbox](https://www.mapbox.com/) and [create an access token](https://docs.mapbox.com/help/how-mapbox-works/access-tokens/#creating-and-managing-access-tokens).

  ![neighbourhood-map.png](Images/neighbourhood-map.png)

#### Cost Analysis (Optional Challenge)

Plotly express offers a broad selection of interactive plots. In this optional challenge section, you will use Plotly express to a couple of plots that investors can interactively filter and explore various factors related to the house value of Toronto's neighbourhoods.

1. Create a bar chart row facet to plot the average house values for all Toronto neighbourhoods per year. (+ 5 pts)

    **Hint:** You can learn more about facet plots in Plotly Express in [this link](https://plotly.com/python/facet-plots/).

   ![bar_chart_row](Images/bar_chart_row.png)

2. Create a sunburst chart to conduct a cost analysis of the most expensive neighbourhoods in Toronto per year. (+ 5 pts)

    **Hint:** You can learn more about sunburst charts in Plotly Express in [this link](https://plotly.com/python/sunburst-charts/).

    ![sunburst](Images/sunburst.png)

### Dashboard

Now that you have worked out all of the code and analysis, you will use the Panel library to build an interactive dashboard for all of the visualizations. There are no hard requirements for the layout of this dashboard, so use your imagination and creativity!

Use the `dashboard.ipynb` starter notebook for your dashboard code. Copy over the code for each visualization and place this into separate functions (1 function per visualization). This will make it easier to build and modify the layout later. Each function should return the plot figure in a format that Panel can use to plot the visualization.

Sample Dashboard:

  ![dashboard-demo.gif](Images/dashboard-demo.gif)

---

### Submission

* Create separate notebooks for the analysis and the dashboard and upload these to Github.

* Write a README file to explain how to run and use your dashboard.

* Submit the Github URL repository to Bootcampspot.

* **Important Note:** You should not submit your Mapbox access token to Github!

---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
