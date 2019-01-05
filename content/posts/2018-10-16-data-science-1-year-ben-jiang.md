---
title: "n=1 year in data: Ben Jiang"
author: Chris Hua
date: '2019-01-04'
slug: data-science-1-year-ben-jiang
categories: [interviews]
tags: [data science, college]
---

Interviewed 16 October 2018. Lightly edited.

<center><a href="https://www.linkedin.com/in/benjamin-jiang-1bb247b4/"><img src="/static/2018-12-30-ben.jpg"/></a> </center>

If you're interested in being profiled, drop me a line! I'm interested in speaking to early-mid career data scientists (hence, n=1 year).

**What do you do?**

I'm a [data scientist at KeyMe](https://www.linkedin.com/in/benjamin-jiang-1bb247b4/).

Our key value prop is in the tech, e.g. deep learning, which we use to scan keys and model what the output should be.

**What did you study in school?**

I studied mechanical engineering and physics at Penn.

**What made you want to do data science?**

On suggestion of a friend, I applied to data science internship, which was code heavy but seemed more interesting than software. The problems were open-ended and cool: what's the problem, how can we solve the problem, flexible on which techniques to use to solve the problem.

**What did you expect to do as a data scientist?**

* strategy
* looking for trends
* correlations that others weren't finding
* predictive modeling
* a lot of communicating results to management and arguing for a path.

**What do you actually do?**

At first, I was the second hire on the team, with various transitions, that meant a lot of ETL / pipeline firefighting and small asks at first.

Now, it's more more like independent research, into some optimization models, but not a lot of ML.
Another big element is data evangelism, trying to bring people up to speed with data / share data more broadly. An example is the marketing analytics team:

* teaching SQL and aggregating data in a given way to help them
* walking them through some data analysis questions
* recognizing common pitfalls (e.g. causation vs correlation)

**What tools do you use?**

Python, TensorFlow and Keras, Pandas/Numpy, FB Prophet, Redshift / SQL, Luigi for ETL, Tableau for visualization, Excel for everything which goes into PowerPoint

**Which teams or roles do you work the most with?**

Analytics is centralized - we work with marketing (campaign performance), engineering (data integrity, infrastructure), as well as ops (supply chain optimization, scheduling).

Information flows through analytics and it's hard to scale that to all teams - no single source of truth, need to define ground truth metrics and statistics, making sure everyone can make good decisions. A centralized approach is good in the short run.

**How did you have impact on the organization?**

Lot of different areas:

* Revamped store selection model from third-party to in-house model.
* Utilized new data sources and engineered new model which is 2x as good at predicting store usage.
* Inventory utilization: each machine can only have a certain number of slots for key molds, which ones will have the most usage. We made this 50% better.
* Refund rates are down drastically because of improvements in error rate, by understanding the purchase and refund funnel.
* Dynamic pricing - increased core revenue by 25%.

**How do you do experimentation?**

We typically set up user segmentation and assign users to a given experiment. This requires coordination with our front end engineers and product team.

**What's the most important thing you learned?**

It doesn't matter what you find unless you convince others to take action on your results.

**Any other advice you have?**

The difficulty of data science code is overhyped: concepts are more difficult than most practice. In the real world, cutting-edge ML isn't that important, it's not Kaggle where we're going from 95→99%. It's more about problem solving and ability to independently learn and research. most peoples' problems are not 100% unique, you can find research that's gets you 80% of the way there, your value is in knowing what to do and how to apply the existing research.