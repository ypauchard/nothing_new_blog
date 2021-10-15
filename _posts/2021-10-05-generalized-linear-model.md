---
toc: true
layout: post
description: A journey from linear regression to glms 
hide: true
search_exclude: true
categories: [machinelearning, statistics]
title: Generalized Linear Models
---
#  Generalized Linear Models
## Linear regression: least-squares vs maximum likelihood view

What I am familiar with is the least-squares interpretation of linear regression:

$$
\underset{w}{\operatorname{min}} \underset{i}{\sum} \left(y_i - (w_0 + w_1x_i)\right)^2
$$

maximum likelihood view, the y's are distributed normally:
$$
y_i \sim N(\mu_i, \sigma)\\
$$
the mean $\mu_i$ for a given $y_i$ is obtained from a linear model using $x_i$ and slope and intercept:
$$
\mu_i = w_0 + w_1x_i\\
$$
