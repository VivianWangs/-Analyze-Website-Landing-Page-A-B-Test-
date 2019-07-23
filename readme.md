# New Web Landing Page A/B Test 



A ecommerce website designed a new web landing page aming to receie higher user conversion rate. In this work, it include three main parts:

I. Probability analysis

II. A/B test

III. Probability analysis 


The analysis was perfomred with pandas and visulization by matplotlib. Regression analysis was performed by two methods: 1) Use loop to similate 10,000 experiment using numpy.random.choice() function; 2) Use StatsModel package to run logistic regression model.

In the end,  a new dataset was formed to study country factor interaction. By adding interaction between country and new page received, the P value for 'ab_page','US', 'UK' and two new interaction terms ('UK_newpage', 'US_newpage') are all higher than 0.05. These results indicate they are not statistically significant for conversion rate.






