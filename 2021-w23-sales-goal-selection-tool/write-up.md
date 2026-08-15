# 2021 Week 23 | Tableau: Sales Goal Selection Tool

- **Published:** June 9, 2021
- **Original post:** https://www.workout-wednesday.com/2021w23tab/
- **Author:** Ann Jackson

## Introduction

This week's challenge is inspired by a recent situation Ann encountered. The dashboard users had two different ways to calculate a goal and wanted the option to change how the calculation works for each category. Not only that, they wanted to be able to take the mixed calculations and sum them up to get an overall goal for the year.

So that's the challenge for the week! Build out functionality to support 2 different goals, one that can be toggled interactively and one that will aggregate up.

## Requirements

- Dashboard Size: 1200px by 800px
- # of Sheets – 2
- Create BANs with Sales YTD, Sales LY YTD, and a Year-End Goal
  - For the sake of the challenge, "Today" is statically set to 6/9/2021 with a parameter
- Create a bar chart with a goal line with the same calculations as above
- Create distance to goal and % of goal calculations
- Create functionality that lets the user click on a circle to change the goal calculation type and then a way to toggle back

Goal calculation methodology: for "same pace" find the average sales per day for 2021, use that value to construct what a full year would be. For "last year + X%" use a parameter that has a percentage increase — Ann selected 10% and then hid the parameter (can be exposed instead).

If you're up for the challenge, make sure the average sales calculations can withstand leap years.

## Dataset

This week uses the superstore dataset for Tableau 2021.1.
