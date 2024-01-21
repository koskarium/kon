---
title: "[4] Analyzing Wine Auction Data for Price Anomaly (2015)"
excerpt: "We look at wine auction data from 2014-2015 and test if the declining price anomaly is still present. We will investigate what factors have an
affect on the winning bid price in the sequential period. <br>
***Keywords:*** *auctions, declining price anomaly, regression, R, Stata, economics, data analysis, graduate*" #add this to add an image inside the "" <br/><img src='R001_padic/500x300.png'>
collection: research
permalink: /research/wine
---

This was my research project for CSU Fullerton’s Econ 595 Reseach Capstone. In this project we look at wine auction data from 2014-2015 and test if the declining price anomaly is still present using R and Stata. The declining price anomaly is concern with the obsercation that in multi-item acutions of identical object, the price tends to decresease over time. Effectivly, we are testing to see if there is a premium for buying the item early given that there might not be more as time progresses. To test, this we developed a model 
$$\log{Bid750}_{t+1}=\alpha+\beta_0{Size}_{t+1}+\beta_1{High Estimate750}_{t+1}+\beta_3 Qty_{t+1}$$
$$\qquad\qquad\qquad+\beta_4 Year_{t+1}+\beta_2{Low Estimate750}_{t+1}+\beta_5 Order_{t+1}+\epsilon_t$$

where $$Bid750_{t+1}$$ is the hammer price per 750ml at time $$t+1$$, $$Bid750_{t}$$ is the hammer price per 750ml at time $$t$$, $$Size_{t+1}$$ is the size of the lot at time $$t+1$$, $$High Estimate750_{t+1}$$ is the high estimate per 750ml at time $$t+1$$, $$Low Estimate750_{t+1}$$ is the low estimate per 750ml at time $$t+1$$, and $$Qty_{t+1}$$ is the quantity in the lot at time $$t+1$$. We found that in this particular wine action, prices did decline more so that increased when the price did change. 

### [Click here to open the paper in a new browser](R004_wine/Econ_595_Project.pdf)
<object data="R004_wine/Econ_595_Project.pdf#view=fitH" width="1000" height="1000" type='application/pdf'></object>
