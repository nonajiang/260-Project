# Checks and Cities

![](/avatar/ChecksandCitiesCrop.jpg){:width="700"}

## Project Overview

### Motivation

As we look ahead to our professional lives post-graduation, many of us will be searching for our very first jobs. This process can be both incredibly exciting yet nerve-wracking (!) and fraught with many considerations such as:

- What is the average salary offered to someone in my industry?
- Will I be able afford rent in New York City on my salary?
- Does it make financial sense for me to move back to sunny San Diego?

All these variables can be overwhelming and for those fortunate to have competing job offers in different cities, synthesizing all the relevant data to be able to make this important life decision can be just plain paralyzing. While information on salary and cost of living is available online through existing sites, there does not exist a single interface that combines these data.

To help users pick the best job offer for them, we created an interface that will allow job searchers to be able to easily compare salaries and cost of living across different cities. Using our [dashboard](https://nonajiang.github.io/Checks-and-Cities/shiny.html), job searchers will be able to comprehensively compare their job offers to help hem to make important career decisions - all with just a few clicks!

### Objectives

The primary objectives of our project are two-fold:

1. To put together salary data for various job titles in 50 U.S. cities and include the important cost of living measures (apartment costs, meal costs, utilities, etc.) in a [Shiny App](https://nonajiang.github.io/Checks-and-Cities/shiny.html)
2. To include [visualizations](https://nonajiang.github.io/Checks-and-Cities/pages/vis.html) and analyses that will help to assess the salaries needed for the cost of living across our 50 cities
 
### Approach
We first conduced web-scraping to extract the cost of living data from numbeo.com and average wages from the Bureau of Labor Statistics (BLS). We then performed regression analyses and created several graphs and visuals to help answer our questions of what is the relationship between salary and living expenses across cities, which variables predict cost of an apartment and salary, and what high-paying jobs are (>95th percentile) in various cities. We then put this data together in a user-friendly shiny dashboard!

