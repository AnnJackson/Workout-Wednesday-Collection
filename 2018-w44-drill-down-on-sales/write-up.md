# Week 44: Ready, Set: Let's Drill Down on Sales!

- **Published:** October 31, 2018
- **Original post:** https://www.workout-wednesday.com/week-44-ready-set-lets-drill-down-on-sales/
- **Author:** Ann Jackson

## Introduction

At time of writing Tableau 2018.3 was just released. With it comes some brand new features, including the one that's the focus of this workout: set actions. Sets have long been a feature in Tableau and are responsible for creating dashboard actions, but set actions are something completely new. Set actions allow you to interact with your data to determine what data elements are part of the set, essentially sets become more dynamic.

One of the most straightforward uses of set actions is one that was demonstrated during Devs on Stage at TC18 – drilling down on the same sheet. They showed a video that included drilling down on a treemap from one level of detail to a lower granularity, to a third granularity.

So my challenge for you this week is to learn more about sets and set actions. You'll find these to be extremely useful moving forward on drill-filtering on the same sheet – both on maps and when you're trying to explore more detail. Not a lot of showy formatting or sophisticated calculations – your only goal is to get comfortable with set actions.

## Requirements

- Dashboard size: 1200 x 800; 2 sheets
- Create a line chart of monthly sales
- Create way for user to select months and drill/filter the line chart, this should also filter the treemap below
- Create a treemap of sales by category that has the ability to drill to sub-category and product name upon clicking
- Create dynamic labels (and tooltip) for the treemap that display based on the level of detail shown (category/sub-category/product name)
- Match all other formatting, labels, and tooltips
- Add a region filter for fun

**FYI:** Set Actions aren't quite working on Tableau Public, so download the workbook and view in 2018.3 to explore the full interactivity!

## Dataset

Data from this week comes from the Saved Data Source in Tableau 2018 (Sample – Superstore).
