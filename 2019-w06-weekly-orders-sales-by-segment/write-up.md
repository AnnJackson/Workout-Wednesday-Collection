# 2019 Week 6: Weekly Orders & Sales by Segment

- **Published:** February 6, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-6-weekly-orders-sales-by-segment/
- **Author:** Ann Jackson

## Introduction

Those of you who know me well know that I like to create visualizations that include both detail and aggregate in the same view. I have a particular interest in showing how the smaller components contribute to the overall. When there's one major chart on a dashboard I think it works out particularly well – keeping high level attention focused on the macro data shapes, but providing exploratory capabilities in the micro.

This week's workout is also a little more on the arty side. The original inspiration for this comes from something I built at work, but once I retooled it using Superstore I was struck by how the result looked like trees. To add to the whimsy, I've included tree trunks which contribute to the overall look/feel and provide the macro details.

But don't be fooled, although this viz looks pretty, it's packed with some real takeaways that I'm confident you'll be able to take back and implement at work. You'll want to pay close attention to the viz in tooltip.

## Requirements

- Dashboard size: 1300 x 800, 2 sheets – one for the main viz and one for the VIT
- Create a tree plot that shows individual orders by week
  - Size of order = sales
  - Circles sorted by sales
  - Make trunk that is the # of orders for the week/segment
- Create a highlight table VIT with an order summary
  - Sales and quantity by subcategory
  - Sales should have more orange = more sales
  - No color for quantity
- Include a Region filter (to see the beautiful forests change)
- Match any additional formatting and tooltip language

## Dataset

This week uses the superstore dataset for Tableau 2018.3.
