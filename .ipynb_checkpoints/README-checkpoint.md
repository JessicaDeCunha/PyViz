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

In this final section, we used neighbourhood location data and build an interactive map with the average prices per neighbourhood. Then we used a scatter Mapbox object from Plotly express to create the visualization with the help of Mapbox API key.

#### Cost Analysis 

Plotly express offers a broad selection of interactive plots. In this section, I have used Plotly express on a few of the.plots that investors can interactively filter and explore various factors related to the house value of Toronto's neighbourhoods.

### Dashboard

Now that the code and analysis has been completed, I have used the Panel library to build an interactive dashboard for all of the visualizations. You can view a non-interactive preview of everything on the rental_analysis_preview.png

---

