# 2019 Week 18: Let's Compare Quarterly Sales Performance

- **Published:** May 1, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-18-lets-compare-quarterly-sales-performance/
- **Author:** Ann Jackson

## Introduction

Have you ever been asked to make a tool that allows end users to dynamically select two periods and compare them? The challenge this week takes inspiration from this all too likely to be asked request. At surface level it can be an easy ask, but how can you add on additional context along with a responsive and intuitive design that allows for a good user experience.

In this challenge you'll be creating 3 often used chart types: a line chart, bar chart, and BAN (big ass number). The twist? You'll be adding on custom axes that reference color identifiers throughout the dashboard and ensuring that the most recent quarter selected is always highlighted. And what happens if someone accidentally selects the same quarter and tries to compare it to itself? Well you've got that covered too with some nice flavor text to help them along.

## Requirements

- Dashboard size: 1500 x 900; maximum of 3 sheets; No text boxes!
- Create a line chart that does the following after a user selects 2 different quarters:
  - Shows the running total of sales by day
  - The older quarter is gray, newer quarter is blue
  - The axis at the top displays dates related to the newer quarter
  - The axis at the bottom displays dates related to the older quarter
  - The tooltip references the order date, # of days into the quarter and the running total sales amount
- Create a BAN that shows the percentage difference
  - The older quarter is always the "compared to" or prior value
  - When the quarters are the same, text displays "Change Comparisons"
- Create a bar chart that shows total sales for each selected quarter
  - Bars should always have the blue bar on the right (newer quarter)
- Create a dynamic title that always shows the newer quarter first and in blue
- Match all tooltips, labels, and formatting (including axes). Blue: #2cb5c0, Gray: #b4b7b7

## Dataset

This week uses the superstore dataset for Tableau 2019.1.
