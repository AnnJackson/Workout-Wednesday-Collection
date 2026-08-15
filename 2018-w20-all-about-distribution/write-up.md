# Week 20: All About Distribution

- **Published:** May 14, 2018
- **Original post:** https://www.workout-wednesday.com/week-20-all-about-distribution/
- **Author:** Ann Jackson

## Introduction

This week I was cleaning up my desk and found some old notes where I had been jotting down ideas around visualizing distributions. At the time I was working with a data set where data points were concentrated around specific numbers and I was exploring ways to visually capture the concentration. I love looking at distributions and they are a go-to tool when I do exploratory data analysis or data profiling. Traditionally the box plot (or box and whisker plot) and the histogram are great ways to deal with this type of data. Box plots take key statistical components of your data set and summarize them. Histograms use binning to show the distribution of a numeric value. Despite their high value, people can be turned off when they read things like IQR or when describing a histogram (they are always a mouthful!). When that happens I've found that using a dot plot of the individual data points and adding jitter (so dots aren't stacked) can be a more comfortable way to view distributions.

So with that intro, I'm hoping your brain is now stuck on different ways to visualize distributions! This workout will look at combining box and whisker plots, histograms, and applying jitter to display different types of distributions. There's also some fun formatting thrown in for good measure. As you build out the solution, pay close attention to calculated bins – I think these are secret powerful creatures in Tableau.

Viz inspiration shout outs: Joshua Milligan & Alexander Mou.

**Primary Question:** What is the distribution of products by quantity sold? Or as it is named in the title, how many products sold X quantity?
**Secondary Question:** What is the distribution in average unit price of the products?
**Tertiary Question:** What is the distribution of how these products were discounted?

## Requirements

- Dashboard size: 1200 x 650, 3 sheets – TILED
- Dashboard is limited to Furniture subcategories
- Create a histogram with boxplot combination chart using distribution of products by quantity
- A product is defined by its product name (use this when counting products and building aggregations)
- Average unit price is considered (sum sales per product)/(quantity sold per product)
- Build in dashboard actions:
  - Clicking on bar(s) in histogram will highlight dots and filter discount histogram
  - The discount histogram always takes up the same amount of space, even when filtered
- Match formatting & tooltips; pay attention to labels and seamless banding

## Dataset

This week uses the superstore dataset. [Get it here](https://github.com/Workout-Wednesday/data/blob/main/2021/Sample%20-%20Superstore.xls/workspace/file?filename=Sample+-+Superstore.xls).

## Hints & Detail

- Pink #ff007f; 60%
- Blue #17becf; 60%
- Orange #2f28e2b; 60%
- Boxplot: Very Dark Gray; 20%
- Used 'show empty rows' for the discount histogram
- 2 LODs & 2 bins
- Jitter uses INDEX() – your jitter may vary
