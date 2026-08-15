# 2020 Week 6: Can you build a MoM Progress Report?

- **Published:** February 4, 2020
- **Original post:** https://www.workout-wednesday.com/2020w06/
- **Author:** Ann Jackson

## Introduction

This week's challenge is ripped directly from two different requests I had over the past week. The idea is simple, create a single visualization that displays performance in different metric categories and provide an overall health indicator. This concept may look very familiar for people accustomed to KPI indicators in Excel (or dare I say conditional formatting).

You'll be making a Month over Month Progress Report that shows the health of Sales, Orders, and Units sold by Sub-Category. I've simplified it for the challenge, but you can imagine a real world where each of these boxes could be colored based on different measures of success.

## Requirements

- Dashboard Size: 600px by 800px
- # of Sheets – one
- Create a visualization that has 4 indicators, 3 for metric health, and one with an overall health indication: Sales, Orders (unique order IDs), Units (aka Quantity)
- Performance comparison – compare November 2019 vs. October 2019, but build it to be dynamic enough that someone could change the dates (do not hard code dates)
- Performance comparison is "percent of" aka Current Month / Prior Month, and the expectation is that the current month is at least 100% (or equivalent) to last month for it to be green, less than that it's gray
- Formatting:
  - Colors: Green #01665e; Gray #cdcecd; Alert Red #ff003b
  - Match the tooltips for each metric (current month + metric + value; same for prior month; summary column tooltip is different)
  - Font – Tableau regular

Small hint: Don't use Measure Names/Measure Values.

## Dataset

This week uses the superstore dataset for Tableau 2019.4.
