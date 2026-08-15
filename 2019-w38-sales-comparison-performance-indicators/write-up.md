# Week 38: Can you build a sales comparison chart with performance indicators?

- **Published:** September 18, 2019
- **Original post:** https://www.workout-wednesday.com/week-38-can-you-build-a-sales-comparison-chart-with-performance-indicators/
- **Author:** Ann Jackson

## Introduction

This week I'm tackling a topic that nearly everyone has been asked – visualizing good/bad as performance indicators that are red or green. At least here in the western world, the busy executive tends to think about things in terms of traffic lights. So this week your task is to create something that satisfies their ask of seeing immediate good/bad and adding on some additional analytical components for context (essentially the "why" behind the good/bad).

This dashboard also tackles the idea of automating the visualization to update as time ticks on. The goal is that you build something today and it will continue to work in the future. A side benefit of this challenge is learning how to build something that can be automated/pre-built, even if you don't yet have the data — pretending it's 2018 to use the static Superstore data set.

## Requirements

- Dashboard Size: 1100 x 700 (you choose # of sheets)
- Create a running total sales chart (MTD) for the 3 different Segments
  - Show current year as a running total line chart, colored red/green depending on if it's above/below the same MTD value from the prior year
  - Show prior year as area chart – if it's part of the prior comparative time period it should be dark gray, yet to come should be light gray
  - Create a dynamic reference line for Today
  - Add on a dynamic title that states the days left in the month
  - Add on an indicator to the left of BANs that is red/green depending on if sales is up or down
  - Match labels, tooltips, and all additional formatting
  - Include a Category filter so you can test the functionality
  - Hint: pretend we're in the year 2018 by subtracting X # of years from Today

## Dataset

This week uses the superstore dataset for Tableau 2019.1+.
