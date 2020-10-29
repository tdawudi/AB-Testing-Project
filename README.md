# AB-Testing-Project

## Introduction
This is short project that I completed as part of a requirement for the Udacity Data Analyst Nanodegree Program.
The aim of the project was to analyze the click through rate (and other statistics) for two different landing pages, and to run an A/B test using Python to determine whether an e-commerce website should keep their old page, or move forward with a new landing page based on the results.

**H0**: The null hypothesis: The new landing page will do worse or equal to the new landing page (P𝑛𝑒𝑤 - P𝑜𝑙𝑑 <= 0).

**H1**: The alternative hypothesis: The new landing page will do better than the old landing page (P𝑛𝑒𝑤 - P𝑜𝑙𝑑 > 0).

The project also aims to explore the difference in click-through rate depending on country (USA, UK, Canada).

## Main Challenges
The entire project outline is avaialble in the ipynb file attached, as is the code used to answer the questions. I overcame the issue of multicolinearity when  adding additional variables by calculating VIF. 

## Findings
The most profound findings in my study are as follows:

1. We have enough evidence to fail to reject the null. The new page does in fact have a lower conversion rate than the old landing page.
2. Compared to users in Canada who viewed the new landing page:
  a. UK users were 1.067 times less likely to convert
  b. US users were 1.019 times more likely to convert

