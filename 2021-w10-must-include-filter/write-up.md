# 2021 Week 10 | Tableau: Can you build a must include filter?

- **Published:** March 9, 2021
- **Original post:** https://www.workout-wednesday.com/2021w10tab/
- **Author:** Ann Jackson

## Introduction

This week's challenge is pulled directly from a work challenge Ann encountered recently. The ask was to build a filtering system that would allow the user to initially filter data and then add a secondary requirement of inclusion.

Using the Superstore data set, the functionality wanted was:

1. Allow user to filter to orders with specific products specified
2. Then allow the user to require that an order must also include an additional product they specify

This type of analysis is useful to find out common product pairings, or to do market basket analysis, or to find out what else is "commonly purchased" with certain products.

It's especially useful when you're showing a visualization at a higher data grain than the underlying data set. In the case of Superstore we're showing Order level detail, but mining data at the product (or line item) level.

## Requirements

- Dashboard Size: 1200px by 900px
- # of Sheets – up to you
- Create functionality that allows the user to filter to products and then require another product to be a part of the order
- Create a bar chart that shows Order ID, Customer, Sales, and Quantity total
  - Should show detail of what was included in the order within tooltip
- Create a set of BANs that shows:
  - Total orders that meet the filter requirements
  - % of total orders that meet the filter requirements
  - Average order amount of those that meet the filter requirements
  - Average order quantity of those that meet the filter requirements
- Match formatting and tooltips:
  - Font = Tableau Regular
  - Colors = Nuriel Stone

PS: No data modeling or restructuring required. You do need version 2020.2 or greater!

## Dataset

This week uses the superstore dataset for Tableau 2020.4.
