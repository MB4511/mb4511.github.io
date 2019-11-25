---
layout: post
published: true
title: Marketing Analytics -Survey Data Analysis
---
## Marketing

[Analyzing a survey data to generate interesting insights for a marketing team](https://github.com/MB4511/Marketing-Analytics-on-Survey-Data-.git). 


Analyzing a survey data on mobile products
This file will go through my appraoch in handling a detailed survey responses to get some interesting insights for a marketing team.

Description
We have information on customers based on their demographics, personality traits etc. Also we have data on each product and its characterstics ranging from how stylish it is to how user friendly it is.

Data format
The data is in melted format i.e. each user response on each product is a row. This is a typical format of survey responses

Approach
Exploratory Data Analysis
1) Know Your Audience
Some analysis on how users of different age groups, income levels, regions, personas have taken the survey since the first step in analyzing survey results is to know your audience.

2) Know Your Product in terms of different KPIs
Analysis is performed to get a feel of how each product is doing in terms of awareness, advocacy, conversion etc.

3) Overall Brand perception analysis
Tricky part as here we evaluate the overall sentiment with each product and since survey has questions which are negative as well as positive in nature, it is imperative to consider the tone of each question and accordingly evaluate the responses to get a overall sense of each product.

4) Analyzing products based on different customer engagement metrics (funnel analysis)
This step is most important when it comes to get granular analysis of each product. The marketing team wants to know which products are able to reach users with awareness scores but at the same time the focus is also on to know if the aware users and getting converted to consume/use the product. So this step allows us to dive deeper into the customer funnel analysis for each product which can help marketing team to create campaigns accordingly.

Modeling (Logistic Regression and linear regression)
I use logistic regression to get the impact of each feature in our dataset which affects the awareness of a product. The idea is to get the reasons how user's demographics and responses lead to awareness of a product and if there is any statistical significance on how a product gets more awareness. Also I aim to find if awareness of other products impacts the results.

I use linear regression to get the impact of each feature in our dataset which affects the satisfaction of a product. The idea is to get the reasons how user's demographics and responses lead to satisfaction of a product and if there is any statistical significance on how a product gets more satisfaction. Also I aim to find if metrics of other products impact the results.

This analysis would be helpful in generating marketing campaigns. The results are useful in allocating marketing resources accordingly. For example age group contributes to raise awareness of a product so based on coefficients of our logistic regression model, we can customize the campaigns for the audience which might be interested in a particular product.
