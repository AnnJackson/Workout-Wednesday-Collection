# 2020 Week 11: Can you build smart ranked lists?

- **Published:** March 10, 2020
- **Original post:** https://www.workout-wednesday.com/2020w11/
- **Author:** Ann Jackson

## Introduction

I've heard rumblings that the past few weeks have been a little difficult – so this week I've decided to keep it simple.

The final visualization comes from something I encountered recently. I have a client that works with data that is very volume specific per day, so they wanted a way to quickly compare a given day of week to recent peers. Seasonality is also a factor, so it didn't make sense to go back too far in time.

The genesis of what we built was a bar chart, showing the amount for each of the given Wednesdays, but I felt something was missing. In the world of quick insights, it was hard to see at a glance "where" the current date fell among its peers. Sure you could compare the lengths of the bars, and could add an average line for even more insight, but a quick verbal utterance of performance still took some time.

This led me to create a super simplified and synthesized version and this week's challenge. The end user can select a date and compare to the prior 11 peers (for a total of 12 days). All the dates are then displayed in rank order by the metric, colored as to whether they are good/bad, the current date is marked differently, and the title synthesizes what you're seeing.

I also wanted to bring in a few design elements that you may not be familiar with (specifically the shadowing on the boxes). This way, even if the technical part of the challenge isn't difficult, you'll be flexing your design skills.

## Requirements

- Dashboard Size: 700px by 450px
- # of Sheets – not more than 4
- Create three ranked lists based on the following metrics: Sales, # Orders, Quantity
- Allow users to input a date and have the prior 11 (for a total of 12) days of the same weekday display
- Arrange the dates by their performance, from best to worst
- Indicate the date that is the focus of analysis with an arrow
- Color the values as follows:
  - Dark green = maximum value within all displayed
  - Light green = above average of the values
  - Yellow = below average of the values
  - Red = minimum value within all displayed
  - Color palette is built in, Temperature Diverging
- Build headers that display Above/Below average
- Build a button that allows users to click and change the date
- Formatting:
  - Make a dynamic title for the dashboard
  - Make a dynamic title that shows the rank of the date for each list
  - Match tooltips
  - Make sure there is a dark gray shadow beneath each sheet

## Dataset

This week uses the superstore dataset for Tableau 2019.4.
