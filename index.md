# Checks and Cities

![](/ChecksandCities.jpg)

## Project Overview

### Motivation

As we look ahead to our professional lives post-graduation, many of us will be searching for our very first jobs. This process can be both incredibly exciting yet nerve-wracking (!) and fraught with many considerations such as:

- What is the average salary offered to someone in my industry?
- Will I be able afford rent in New York City on my salary?
- Does it make financial sense for me to move back to sunny Southern California?

All these variables can be overwhelming and for those fortunate to have competing job offers in different cities, synthesizing all the relevant data to be able to make this important life decision can be just plain paralyzing. While information on salary and cost of living is available online through existing sites, there does not exist a single interface that combines these data.

To help users pick the best job offer for them, we created an interface that will allow job searchers to be able to easily compare salaries and cost of living across different cities. Using our [dashboard](https://nonajiang.github.io/Checks-and-Cities/shiny.html), job searchers will be able to comprehensively compare their job offers and aid them to make some of their most important career decisions - all with just a few clicks!

### Objectives

The primary objectives of our project are two-fold:

1. To put together salary data for various job titles in 50 US cities and include the important cost of living measures (apartment costs, meal costs, utilities, etc.) in a [Shiny App](https://nonajiang.github.io/Checks-and-Cities/shiny.html)
2. To include [visualizations](https://nonajiang.github.io/Checks-and-Cities/pages/vis.html) and analyses that will help to assess the salaries needed for the cost of living across our 50 cities
 
### Approach
We first conduced some web-scraping to extract the cost of living data, followed by some data cleaning and string processing to clean the cost of living dataset and wages dataset before merging them together. We then going to performed regression analyses and do several graphs and visuals to help answer our questions of what variables predict cost of an apartment and salary. Finally, we then put this data together in a user-friendly shiny dashboard.


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nonajiang/260-Project/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
