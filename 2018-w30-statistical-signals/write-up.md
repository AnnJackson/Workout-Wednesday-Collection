# Week 30: Statistical Signals in Superstore Sales

- **Published:** July 25, 2018
- **Original post:** https://www.workout-wednesday.com/week-30-statistical-signals-in-superstore-sales/
- **Author:** Ann Jackson

## Introduction

This week's workout is all about finding signals or patterns in data, specifically using run charts (aka line charts). Variance over time is one of the most common ways to understand a process and often when we're visualizing the data we use data summarization tools like the mean (average) or median to help aid in what we're seeing. Quite often there's a story that unfolds during our visual analysis – these points are all low, look at this trending section, this single measurement is way different than the others.

These visual tests are good on their own, but they can lead to imprecise interpretation, focusing on detail that may not indicate a pattern, or the inability to communicate findings in a rational and logical way to others. Fortunately for us there's an easy way to combat that from happening – enter statistical tests and control charts!

Control charts using their most basic definition are a way to determine if a process is stable (aka "under control") and typically uses different types of statistical tests to programmatically identify any signals or patterns based on rules placed on the data set. I was introduced to them from a process engineering and industrial engineering perspective and I would say from my experience they work most effectively when a process isn't constantly changing (the most popular example: a screw factory always makes 1 inch screws, anything outside of 1 inch would indicate a problem in the manufacturing process).

So your challenge this week is to recreate 3 different statistical tests using Superstore data. (Play along with me a little bit and assume Superstore doesn't invest anything in changing monthly sales). And remember – these are just signals within your data – it's always important to validate these signals to determine if there's a legitimate reason behind them.

## Requirements

- Dashboard size: 1100 x 800; 3 sheets, tiled
- Create a run chart of monthly sales (without date drilling)
- Create a middle line that is either the mean or median
- Create +3 SD and -3 SD lines from the middle line
- Build out the 3 statistical tests – match for test causes an orange dot to be plotted on run chart:
  - more than 3 SD from the middle line
  - 3 consecutive points trending in the same direction positively or negatively (ex: point 1 > point 2 > point 3)
  - 3 consecutive points above or below the middle line
- Create a corresponding chart below run chart with indicators of the test
  - Yellow dot if it's part of the pattern that corresponds with the test
  - Orange dot if it's a signal (aka meets the test criteria, should match the run chart)
- Interactivity
  - In line chart, tooltip for orange dots should indicate 'signal'
  - In symbol chart, tooltip should indicate 'part of test pattern' = gold dot, 'meets test criteria' = orange dot
  - Match hovering on the run chart or the symbol chart – hovering over an orange dot, label appears in run chart
- Test Description – match the text, this should change with the test selected
- Match all other tooltips, descriptions, and filters

## Dataset

Data from this week comes from the Saved Data Source in Tableau 2018 (Sample – Superstore).
