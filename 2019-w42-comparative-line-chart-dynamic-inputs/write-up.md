# Week 42: Can you build a comparative line chart with dynamic inputs?

- **Published:** October 16, 2019
- **Original post:** https://www.workout-wednesday.com/week-42-can-you-build-a-comparative-line-chart-with-dynamic-inputs/
- **Author:** Ann Jackson

## Introduction

This week's challenge is taken directly from a situation I recently had on a project. The goal of the project was to be able to isolate out time periods of a specific length and compare it to the time period directly before it. So as an example, if it's October 2019, I want to look at the 6 month period ending October 2019 (May 2019 to October 2019) vs. the 6 month period directly prior (November 2018 to April 2019). The intended final visual was a line chart that showed trending over time – so that the first month of the current period was compared directly to the first month of the prior period. This type of analysis is perfect for retail or consumer packaged goods environments – they often work off of 13, 26, or 52 week rolling periods.

I also emphasized ways to make the whole interaction more user friendly and dynamic in nature – instead of fumbling with drop-downs, users can have custom buttons to change the time range and end month.

## Requirements

- Dashboard Size: 1100 x 800 (# of sheets is up to you!)
- Create a line chart for two different periods
  - Periods are chosen through a dynamic input
  - Periods display in chronological order – oldest date for each time period should be the first data point per line
- Create a way to dynamically change the time range/periods; make this interactive
  - When users click on a time range, the selection should be hot pink, otherwise light gray (or pick your favorite colors)
- Create a way to dynamically change the end month; make this interactive
  - When users click an end month, all months that are part of the current period should be blue; those in the prior period should be very dark gray, those outside of either range should be light gray
- Create a dynamic title with a legend that includes the date ranges of the two periods
- Match tooltips, formatting, and labels

## Dataset

This week uses the Superstore Data Set from 2019.3 (it goes through the end of 2019).
