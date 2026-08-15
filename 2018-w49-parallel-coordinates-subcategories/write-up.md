# Week 49: Where Do Sub-Categories Succeed?

- **Published:** December 5, 2018
- **Original post:** https://www.workout-wednesday.com/week-49-where-do-sub-categories-succeed/
- **Author:** Ann Jackson

## Introduction

Last week I had the honor of attending Tapestry Conference in Miami. While I was there Jon Schwabish gave a quick 6 minute talk that connected every chart to every other chart. This along with some of Elijah Meek's keynote mentioning that data viz is getting more custom and funky got me curious about some neglected chart types. Combine this with a recent interest in how clustering works in Tableau and you've arrived at the genesis for this week's challenge. Your goal is to create a Parallel Coordinates chart.

This chart is perfect for multivariate analysis and seeing relationships among more than 2 measures (in this case 3). It can also be useful for finding commonalities among things. Traditionally I think most people may shy away from implementing this in Tableau because quite often different measures have different scales, so as part of the challenge, you'll have to figure out how to overcome that obstacle to present a parallel coordinate chart with 3 measures of different magnitudes.

Also to help reinforce some recent challenges using table calculations – you are not allowed to use LODs and must only use table calculations and regular calcs.

## Requirements

- Dashboard size: 1200 x 850; you choose # of sheets
- Create a parallel coordinate chart that shows Sales, Profit Ratio, and # Customers (CountD Customer Name) per sub-category
- Do not use LODs, use table calculations (and normal calculated fields)
- Each sub-category should be positioned based on its value, but all measures should be on one sheet
- Ensure there is a dark gray vertical line for each measure
- Label the top and bottom of each vertical line with the measure name and respective minimum or maximum
- Color the lines based on which measure the sub-categories have the highest value in
- Colors are based off of the Viridis color palette
- Create a color legend that has a hover action based on the newly defined colors (high sales, high profit ratio, high customers)
- Match formatting & tooltips

## Dataset

This week uses the superstore dataset for Tableau 2018.3.
