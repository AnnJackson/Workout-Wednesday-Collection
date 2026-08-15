# Week 24: Do customers spend more on their first or second purchase?

- **Published:** June 12, 2018
- **Original post:** https://www.workout-wednesday.com/week-24-do-customers-spend-more-on-their-first-or-second-purchase/
- **Author:** Ann Jackson
- **Note:** Uses Tableau Prep

## Introduction

This week I'm taking Workout Wednesday to the next level by including Tableau Prep in the equation! If you don't have Tableau Prep, go get the 30 day trial from [here](https://www.tableau.com/products/prep/download).

Prep was released just over a month ago, so it's the perfect opportunity for us to ensure we're strengthening our visualization skills and including all pieces of the Tableau platform. Prep adds capability to do aggregations, joining, and cleansing all before data reaches Tableau Desktop – so let's take advantage of it!

This week's workout starts with the base Superstore set, but focuses a significant portion on developing a custom hyper extract for the final visualization. If you're using Tableau Public, you can output the final table from Prep into a CSV instead of a hyper file.

The final visualization this week compares buying habits of Superstore customers between the first purchase date (all orders accumulated on that day) vs. the second purchase date (all orders accumulated on that day). The main comparison is between the total sales, but I've also added in the number of unique categories and unique products for additional effort.

I've chosen to use a scatterplot and accompanying strip plots to demonstrate the spread of each individual metric and the two of them in combination. Strip plots can be effective when you're trying to look at dense data. It also helps the end user to quickly see the minimum and maximums of the scatterplot on each axis without having to navigate across the entire view. A line with a slope of 1 through 0 has also been added to quickly dissect customers into 2 categories (habits): those who purchase more the second time and those who purchased more the first time.

## Requirements

- Create a data set in Tableau Prep with:
  - Customer ID
  - Date of First Purchase (minimum order date)
  - Date of Second Purchase (next minimum order date)
  - Sum of Sales, Count Distinct of Category, and Count Distinct of Product ID for each date
  - Note: uses all orders on specific dates, not just the oldest single order
- Dashboard size: 800 x 800, 3 sheets – all floating
- Create a scatterplot with first purchase date sales vs. second purchase date sales
- Create a line through 0 and match annotations for spend
- Create strip plots for the sales measures and line them up with the scatterplot
- Match tooltips
- **Important Exclusions**: 2 customers excluded due to their size — BM-11140 and SM-20320 filtered out at the data source level

## What the data set looks like

- Fields: Customer ID, 1st Purchase Date, 2nd Purchase Date, 1st Purchase Sum Sales, 2nd Purchase Sum Sales, 1st Purchase # Categories, 2nd Purchase # Categories, 1st Purchase # Products, 2nd Purchase # Products
- Total Rows: 781, with the visualization having 779 points after the 2 exclusions

## Hints

- Struggling to build it out in Prep or need to check your work? Make a crosstab in Tableau with the base data
- If you don't have access to Prep, CSV here: bit.ly/WW24CSV
- Axis labels/titles are on the strip plots, not the scatterplot
- Make sure all your axes are fixed on the same ranges
- There is only ONE calculated field in Tableau Desktop!

## Dataset

This week uses the superstore dataset. [Get it here](https://github.com/Workout-Wednesday/data/blob/main/2021/Sample%20-%20Superstore.xls/workspace/file?filename=Sample+-+Superstore.xls).
