# 2019 Week 2: Order Sales Spread by Region

- **Published:** January 9, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-2-order-sales-spread-by-region/
- **Author:** Ann Jackson

## Introduction

Happy New Year! It's time for my first Workout Wednesday of 2019. This week I've decided to take inspiration from a trick or two from past workouts and combine them with some recent work I've been doing. One thing about Tableau that I like is that you can set independent axes for continuous measures if you've got headers on the same shelf (rows or columns). But what if you wanted to have independent axes and headers aren't on the same shelf? The workout this week explores that idea and puts it to the test.

In addition to exploring how to get over that obstacle, I also wanted to play around with date filtering. This week you'll be exposed to a user-friendly calendar that doubles as a filter OR highlighter. I've found that it represents a great way for end users to freely pick a single date, multiple dates, date ranges, random individual dates – pretty much any combination that they would like.

## Requirements

- Dashboard size: 1200 x 800, jitterplots must be one sheet, everything else is up to you
- Create a jitterplot that shows sales by order ID (no need to worry if your jitter isn't exactly the same)
  - Ensure that each plot behaves as if it has an "independent axis" and spans the extent of data within each region
- Create a calendar view that can be used as a filter or a highlighter
  - When used as a filter, chosen dates will filter the jitterplot
  - When used as a highlighter, chosen dates will change to a darker color in jitterplot
- Create a footnote that is responsive to the date selection
- Create average line & callout that are responsive to date selection
- Match colors & tooltips

## Dataset

This week uses the superstore dataset for Tableau 2018.3.
