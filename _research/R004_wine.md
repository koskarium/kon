---
title: "Analyzing Wine Auction Data for Price Anomaly (2015)"
excerpt: "We look at wine auction data from 2014-2015 and test if the declining price anomaly is still present. We will investigate what factors have an
affect on the winning bid price in the sequential period. <br>
***Keywords:*** *acutions, price anomaly, regression, R, stata, graduate*" #add this to add an image inside the "" <br/><img src='R001_padic/500x300.png'>
collection: research
permalink: /research/NumAnl_Pen
---

This was my research project for CSU Fullerton’s Econ 595 Reseach Capstone. In this project we look at wine auction data from 2014-2015 and test if the declining price anomaly is still present using R and Stata. To test, this I developed a model 
$$\log{Bid750}_{t+1}=\alpha+\beta_0{Size}_{t+1}+\beta_1{High Estimate750}_{t+1}+\beta_3 Qty_{t+1}$$
$$+\beta_4 Year_{t+1}+\beta_2{Low Estimate750}_{t+1}+\beta_5 Order_{t+1}+\epsilon_t$$
$$\quad+\beta_4 Year_{t+1}+\beta_2{Low Estimate750}_{t+1}+\beta_5 Order_{t+1}+\epsilon_t$$
$$\qquad+\beta_4 Year_{t+1}+\beta_2{Low Estimate750}_{t+1}+\beta_5 Order_{t+1}+\epsilon_t$$
$$\; +\beta_4 Year_{t+1}+\beta_2{Low Estimate750}_{t+1}+\beta_5 Order_{t+1}+\epsilon_t$$


[Econ 595 Term Project](R004_wine/Econ_595_Project.pdf)
