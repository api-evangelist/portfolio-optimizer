---
title: "Mean-Variance Optimization in Practice: Reverse Optimization and Implied Expected Returns"
url: "https://portfoliooptimizer.io/blog/mean-variance-optimization-in-practice-reverse-optimization-and-implied-expected-returns/"
date: "2026-04-19"
author: "Roman R."
feed_url: "https://portfoliooptimizer.io/feed.xml"
---
The fact that mean-variance optimizers are highly sensitive to changes in expected returns […] is well known in investment practice 1 , with a couple of practical solutions already described in this blog, for example using near efficient portfolios or subset resampling-based efficient portfolios . In this blog post, I will introduce another approach originally described in Sharpe 2 and known as reverse optimization 3 , which consists in trying to improve the robustness of expected returns estimates by turning the mean-variance optimization problem around. In more detail, instead of optimizing 
