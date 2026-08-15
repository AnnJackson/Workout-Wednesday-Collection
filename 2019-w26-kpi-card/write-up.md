# 2019 Week 26: KPI Card

- **Published:** June 26, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-26-kpi-card/
- **Author:** Ann Jackson

## Introduction

Last week I was lucky enough to spend some time in Berlin attending Tableau Conference Europe. Coming off the heels of the conference I was struck by the three components the Tableau team was sharing in terms of new features and development: Making Analytics for Everyone, Analytics at Scale, and Having Trusted Data. I was particularly intrigued by Analytics for Everyone, because I think several of the newest features are heading in that direction – a fluid and inviting analytics experience with the opportunity to view metrics at a high level while providing more insight in context.

This week your task is to build out a KPI card that's packed with a menu revealing more context and insight into the data. It's designed to be simplistic and fit into a compact space, but has additional aspects to visually understand what's being displayed. The KPI card allows the end user to access a menu to define a time period, and select both a Segment and Sub-Category.

## Requirements

- Dashboard size: 600 x 500; you choose the # of sheets
- Create a KPI box that is orange when performance is down from prior period and blue when it's up
- Create functionality to switch between YTD, QTD, and MTD
  - This should be dynamic based on "Today," where "Today" is DATEADD('year',-1,TODAY())
  - You're doing this to compensate Superstore only going through 2018
  - Make sure that your data doesn't go further than "Today"
- Create a menu section that has a sparkline that colors older time, previous period, and current period
  - YTD goes back 2 years
  - QTD goes back 18 months
  - MTD goes back 120 days
- Create contextual bar charts showing % of total based on filter selections
  - Ensure the dynamic titles update appropriately to say "All Segments" or "All Sub-Categories"
- Create a BAN that represents the intersection of the selected filters
- Match all formatting (no tooltips this week!)

## Dataset

This week uses the superstore dataset for Tableau 2019.1.
