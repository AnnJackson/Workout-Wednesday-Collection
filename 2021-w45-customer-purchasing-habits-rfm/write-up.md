# 2021 Week 45 | Tableau: Customer Purchasing Habits (RFM Analysis)

- **Published:** November 10, 2021
- **Original post:** https://www.workout-wednesday.com/2021w45tab/
- **Author:** Ann Jackson

## Introduction

Published during Tableau's annual conference week (#data21, virtual again that year). For this week's challenge, Ann decided to go a different route and viz the workout live on Twitch — with TC being virtual again, it seemed appropriate to do some on-the-fly vizzing.

The challenge itself: a popular analysis often performed in retail or other product-based environments — an RFM analysis. RFM stands for Recency, Frequency, and Monetary. This viz does just that.

Since Ann live-streamed the build, the build and the solution can both be watched on Twitch (linked below).

## Requirements

- Dashboard Size: 1600px by 900px
- # of Sheets – up to you
- Construct an RFM dashboard that displays the following metrics:
  - Time since last purchase (expressed in days if less than 1 year and years if more than one year)
  - Total Orders
  - Total Revenue
  - Average Order Value
  - Total # of Products (quantity) and Unique # of products
- Add on sorting for each of the metrics — matching the parameter to know the direction asc/desc for how the metric will be sorted
- Add a configurable flag for setting a customer as active/inactive based on days since last purchase
- Build out a viz on the Total Products that has the top 10 products by Sales/Revenue

FYI: Ann used 1/1/2022 as "Today" since the version of data goes up to 12/30/21.

## Dataset

This week uses the superstore dataset for Tableau 2021.3.
