# 2020 Week 2: Can you build a beautiful and dynamic bar chart?

- **Published:** January 7, 2020
- **Original post:** https://www.workout-wednesday.com/2020w02/
- **Author:** Ann Jackson

## Introduction

Happy New Year! I'm excited to be back for yet another year of Workout Wednesday. This year we've expanded the team and made a commitment to the community to provide solution videos. We've also got some great collaborations lined up, and a few exciting enhancements to come (custom color palette anyone?)!

To get the year started off right, I thought we could focus on an essential – building beautiful and dynamic bar charts. Bar charts are likely the number one chart you're making in your daily data viz life. They're easy to understand, useful in comparing information, and can be scaled large and small and still look good.

While this is only a bar chart, don't think I've gone too easy on you. This bar chart includes an interactive way to change between metrics – and perfect formatting for different number types.

We're focusing on three major components today: dynamically changing metrics, dynamically changing date ranges, and precision formatting for maximum understanding.

## Requirements

- Dashboard Size: 1100px by 800px
- # of Sheets – up to you
- Create a bar chart that switches between 3 metrics: Sales, Profit Ratio, Items per Order (Quantity/Orders)
- Bar chart must switch between 3 time ranges: Last 12 months, Last 13 weeks, Last 14 days
  - Since the data only goes through 12/31/2019, you can use a parameter to set a fixed "Today" date of 1/1/2020
- Formatting:
  - Match the headers for the dates (Month: Short Month and Year; Week: Week and number; Day: mm/dd)
  - Match the labels for the metrics (Sales as currency, no decimals, commas for thousands/millions; Profit Ratio as percentage with one decimal; Items per Order as decimal number with one decimal)
  - Use RegEx for formatting the numbers!
- Finishing elements:
  - Create a dynamic button system that changes based on metric selection
  - Match colors: Sales #9264a5, Profit Ratio #86b35e, Items per Order #63ccc6
  - Match tooltips

## Dataset

This week uses the superstore dataset for Tableau 2019.4.
