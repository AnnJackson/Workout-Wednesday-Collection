# 2020 Week 24: Can you compare a 3-day vs. 14-day moving average and describe the latest trend?

- **Published:** June 9, 2020
- **Original post:** https://www.workout-wednesday.com/2020w24/
- **Author:** Ann Jackson (written by Ann; example workbook built in collaboration with Jami Delagrange)

## Introduction

I've got an exciting challenge for you this week! It involves collaboration with a peer of mine in the data community (Jami Delagrange, who you may recognize as an upcoming Community Month contributor) and also a challenge that involves working with COVID-19 data.

This built-for-mobile dashboard was born out of seeking to understand the state of COVID-19 in different geographic areas of the United States and to support decision makers who are trying to decide if it is the right time to begin different phases of "re-opening." Jami was charged with making this a reality.

To support the ask, Jami did some research and found a few remarkable resources on the Tableau COVID-19 hub and also some compelling community examples. One visualization stuck out to her, and it formed the basis for our challenge this week: a map by Christian Felix showing by county whether the 3 day moving average of COVID cases was above the 14 day moving average number of COVID cases, indicating either an increase or decrease, and also computing the length of the subsequent trend (eg: decreasing for X days).

So that's your challenge for this week. Rebuilding a map that does day-by-day comparisons of a 3 day moving average vs. a 14 day moving average, computes the number of days that a county is on a certain trend, and then displays it on a map. And by the way, all data manipulation must be done in Tableau (this is where I had a slight role to play).

I will forewarn you – this week will really challenge your understanding of Table Calculations.

Finally, a friendly caveat from us before we get to requirements: in no way should the analytical choices and resulting visualizations serve as a substitute for using recognized expert opinions from national and international health and welfare organizations on COVID-19 in your geographic area.

## Requirements

- Dashboard Size: 450px by 1000px
- # of Sheets – up to you
- Create a table for US counties that has:
  - # of New Cases for latest data date (currently June 7 in the data set)
  - Total Reported Cases
  - 3 Day Moving Average # of new cases
  - 14 Day Moving Average # of new cases
- Create a dual axis bar + line chart with:
  - # of new cases by day
  - Line of average that can be toggled between 14 or 3-day
  - Color line chart based on increase or decrease trend
- Create a county map that highlights the chosen county and shows the trend of green or red based on increase or decrease of 3-day vs. 14-day comparison
- Build a mini-BAN which describes the number of days the county has been on the trend and whether it is an increase or a decrease (or no change)
- Match formatting and tooltips, specifically:
  - Tooltips within map, table, and chart
  - Reference line of first reported case

You may find it helpful to begin with the table to build your solution.

## Dataset

This week uses the COVID-19 data set provided by the Tableau COVID-19 data hub.
