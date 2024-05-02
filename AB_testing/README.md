# Project - A/B testing
##  Project description
###  Project's objective

We had a list of hypotheses that may help to boost revenue for a big online store. The goal of the project was  to prioritize these hypotheses, launch an A/B test, and analyze the results.

###  Overview of the data

**I had three csv files with:**

- **hypotheses datase**t with brief descriptions of the hypotheses, scales of user reach, impact on users, confidence in the hypothesis and the resources required to test a hypothesis;

- **orders dataset** with orders identifiers, identifiers of the users who placed the order, dates of the orders, revenue from the order, the A/B test group that the user belongs to;

- **visits dataset** with dates, A/B test group and the number of visits on the date specified in the A/B test group specified

 
###  Expected outcomes or results
- Prioritize Hypotheses (by using ICE and RICE frameworks)
- A/B Test Analysis 
  
Analyze:

- cumulative revenue by group;
- cumulative average order size by group;
- relative difference in cumulative average order size for group B compared with group A;
- each group's conversion rate as the ratio of orders to the number of visits for each day;
- the number of orders per user;
- the 95th and 99th percentiles for the number of orders per user;
order prices.

Find the statistical significance of the difference in conversion between the groups, the statistical significance of the difference in average order size between the groups.

Make a decision based on the test results to stop the test or to continue the test.

### The Process

First of all I made a full data overview, data preprocessing: changed headers styles, checked data for duplicates and missing values, removed rows with visitors who belong to both groups at the same time. When the data was clean I prioritized the hypotheses using ICE and RICE frameworks and analyzed the A/B test results by  by the following criterias: cumulative revenue by group, cumulative average order size by group, relative difference in cumulative average order size for group B compared with group A, each group's conversion rate as the ratio of orders to the number of visits for each day, number of orders per user, the 95th and 99th percentiles for the number of orders per user, order prices, the 95th and 99th percentiles of order prices, the statistical significance of the difference in conversion between the groups, the statistical significance of the difference in average order size between the groups. Afterwards I removed outliers and checked the statistical significance again. To make my analysis full and comprehensive I ploted necessary graphs and made conclusions and conjectures.


### Results

On each step of my analysis I left comments about my findings and at the end of my project I resumed everything and wrote recommendations based on the test results to stop the test or to continue the test.

Please have a look at the Jupyter Notebook **full version** of [A/B testing project](https://nbviewer.org/github/AnnaMogilevskiy/TripleTen_projects/blob/main/AB_testing/AB_testing_project.ipynb).



