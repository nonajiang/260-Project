---
layout: page
title: Visualize
sitetime: display
permalink: /vis.html
---

## Visualizations

We conducted several analyses and create visualizations to help users with their job search.

### How does average salary relate with average living expenses in each city?

![](/SalaryvExpenses.png){:width="500"}

The plot shows a relationship that did not surprise us: the higher the living expenses, the higher the salary.

### What factors predict average salary in a given city?

Are there particular variables that could tell us how much the average salary is in a given city? We ran a linear regression model to answer this question and found that there are correlations between the price of an apartment (both in the city center and outside the center) and the tuition for 1 child at an international primary school. We found:

- For a $100 increase in the price of an apartment in the center, the average monthly net salary in a city increases by $84.4 on average, keeping the other two covariates constant.

- For a $100 increase in the price of an apartment outside of the center, the average monthly net salary in a city increases by $82.5 on average, keeping the other two covariates constant. 

- For a $1000 increase in the yearly tuition for 1 child at an international primary school, the average monthly net salary in a city increases by $22.6 on average, keeping the other two covariates constant.

We also built a Decision Tree to predict the average monthly net salary based on variables of interest. The tree suggested that the **price of an apartment outside of the center, the price of an apartment in the center, and the cost of the internet**, are the most important predictors in predicting the average monthly net salary.

## What factors predict my cost of rent?

Our second focus is the apartment price in city center since it would best reflect the standard of living. When considering job offers, many people would prefer to live near the city center for convenience, and the price may deviate a lot in different cities.

Here is a graphical representation of the average price of an apartment price in the city center of the 50 cities we looked at:

![](/AptCenter.png)

From our regression model, only "apartment prices out of city center" and "meal price for 2" have significant influence on the apartment price in city center. 

![](/AptCenterRegression.png)

The regression model shows following relationship:

- For a $100 increase in the apartment price outside city center, the estimated price for apartment price in city center will increase 106 dollar on average, holding all other covariates constant

- For a $1 increase in the meal for two, the estimated price for apartment price in city center will increase 9.5 dollar on average, holding all other covariates constant

We also used a machine learning method based on gradient boosting trees algorithm to predict apartment price in city center using variables of interest. The top two influential factors are **apartment price outside of the center and average monthly net salary**.

### What are the highest paying occupations in various cities?

To answer this question and display it in a visually appealing way, we created several word clouds from professions that had salaries in the top 5th percentile. We did this first for all 50 cities and then for several cities to see if there are any differences between cities.

![](/total.png)

It looks like professions in medicine, engineering, and computer-related fields are high-paying fields as a whole.

Now let's take a look at Boston specifically:

![](/boston.png)

In Boston, where there is great emphasis on the healthcare industry, once again we see a strong representation of physicians. Similar to the word cloud nationally, computer-related fields and engineering also offer high-paying salaries in Boston.

What about on the West Coast in San Francisco?

![](/San Francisco.png)

In the Bay Area, we can see that there are more high-paying jobs in the computer science industry with the words "computer" and "engineer" appearing the most frequently.


