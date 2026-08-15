# 2019 Week 14: Can you build a line chart with dynamic highlight and comparison?

- **Published:** April 3, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-14-can-you-build-a-line-chart-with-dynamic-highlight-and-comparison/
- **Author:** Ann Jackson

## Introduction

Care to join me on an adventure to the dark side? The workout this week combines a few concepts inspired by a recent work project someone shared with me. The inspired ask was to create a way to have more user-driven comparisons while retaining other peer information in the background. The end user experience was to be very direct – the user should know what has been clicked and more supporting information should appear in context. The resultant dashboard serves up a fun (and colorful) way to dynamically highlight subcategories for comparison while revealing their monthly averages.

## Requirements

- Dashboard size: 1300 x 1000; no more than 3 sheets
- Limit data to 2018, Office Supplies
- Create a line chart that does the following:
  - When clicking on a subcategory at the top, the chosen subcategory will highlight teal and an average line will appear
  - The chosen subcategory will disappear from the bottom selections
  - The chosen subcategory will move to the far left and be teal (remaining sort is ascending by sales)
  - When clicking on a subcategory at the bottom, the next chosen category will highlight hot pink and an average line will appear
  - The bottom chosen subcategory will disappear from the top selections
  - The chosen subcategory will move to the far left and be hot pink
- When one or more lines is highlighted, the non-highlighted subcategories will change to a darker gray
- Dark mode colors: Background #555555, Teal #00c0c6, Hot Pink #f0007b, Gray 1 #959595, Gray 2 #757575
- Match all tooltips, labels, and formatting

## Dataset

This week uses the superstore dataset for Tableau 2019.1.
