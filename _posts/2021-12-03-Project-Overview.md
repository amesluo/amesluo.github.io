---
layout: post
title: Overview
---

### Improving Educational Equity

#### Motivation
There is no denying the importance of education. At the individual level, a strong education is important for personal growth, acquiring knowledge, and developing critical thinking skills. At the societal level, educational outcomes are highly correlated to better health and higher earnings. However, in the United States, there are many factors that can influence the quality of education and student’s educational success. Understanding how these socioeconomic and political factors affect academic achievement outcomes can better inform future educational policies and programs.  

Our group was inspired to pursue this project after many of us took a statistics course at Harvard Graduate School of Education during the Spring of 2021. For this class we often applied the methods we were learning to data from The Education Opportunity Project at Stanford University. This dataset, referred to as the Stanford Education Data Archive (SEDA) provides detailed information on educational outcomes by various levels (school, district, county, community, and state). We were motivated to use this first national database of academic performance to ask questions about predictors of academic achievement and school funding between states and at the national level. 

#### Objectives
Specifically we are aiming to answer the following questions:

- What are some of the most important predictors of academic achievement at the national level?
- How is unemployment, poverty, and socioeconomic status associated with academic achievement in Massachusetts, Washington, Nebraska, and California? 
- How is percent free or reduced lunch associated with academic achievement in districts at the national level? 
- How is constituent ideology (right-leaning or conservative vs. left-leaning or liberal) associated with congressional district expenditure per pupil and per instructor?


#### Our Approach
We approached these questions using a variety of methods. To determine the most important predictors of academic achievement, we first used exploratory visualization of the correlations between various predictors and academic achievement. We then used a Random Forest model to determine the relative importance of these predictors as demonstrated by their Gini coefficient.  

To explore the relationship between unemployment, poverty, and socioeconomic status and academic achievement we create plots of association to see how these variables are correlated. Moreover, to estimate the effect of percent free or reduced lunch on academic achievement in districts we use a regression model, controlling for socioeconomic status and geography (urban vs. rural).  

To look at how spending on education varies by political leaning within each congressional district, we create an interactive map that shows pupil expenditure in a district by political leaning. Lastly, we create a Shiny app to select predictors and visualize how they map to academic achievement.



### Analysis
Analyses can be found in **two parts**

* **Part I:** Predicting District Academic Acheivement
* **Part II:** Political Ideology & Education Funding


For a video walkthrough
{% include youtubePlayer.html id="v=wI15aI_ytdw" %}

