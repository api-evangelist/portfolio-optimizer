---
title: "Value-at-Risk Estimation: Improved Historical and Simulation-based Estimates with the Harrell-Davis Quantile Estimator"
url: "https://portfoliooptimizer.io/blog/value-at-risk-estimation-improved-historical-and-simulation-based-estimates-with-the-harrell-davis-quantile-estimator/"
date: "2026-06-16"
author: "Roman R."
feed_url: "https://portfoliooptimizer.io/feed.xml"
---
In a previous blog post of this series , the main univariate Value-at-Risk (VaR) estimation methods were described. Among these, and for scenario-based VaR estimation like historical VaR or Monte Carlo VaR, the most widely used [non-parametric] estimator is the corresponding order statistic of the empirical quantile of the portfolio return distribution, or a linear combination of two subsequent order statistics 1 . Problem is, because they use too few sample elements 1 , these estimators exhibit high variability and provides little information about the distribution of losses around the tail 2
