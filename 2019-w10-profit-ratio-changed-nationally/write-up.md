# 2019 Week 10: How Has Our Profit Ratio Changed Nationally?

- **Published:** March 6, 2019
- **Original post:** https://www.workout-wednesday.com/2019-week-10-how-has-our-profit-ratio-changed-nationally/
- **Author:** Ann Jackson

## Introduction

This week's challenge is plucked directly from #IronQuest, a monthly challenge during the off season of Tableau Public's Iron Viz feeder contest run by Sarah Bartlett. The month of February closed with a theme voted on by the public, Business Dashboards. Since the theme falls heavily in line with Workout Wednesday, I decided to bring my own submission for #IronQuest over as a challenge.

The final dashboard was born out of the challenge of showing all 50 states plus DC in a single view. The size of the states was problematic for showing a metric – as the size of the geography was dwarfing the overall performance of all the states. And of course Hawaii and Alaska fell victim to not fitting neatly on a map, so our first goal was to create a view that more cleanly displayed all the states. In addition, we wanted to compare performance over a specific time period (one year for the sake of the workout) and quickly identify improvements and performance gaps.

The final visualization is a tile map (NPR style) that allows for YoY comparison of profit ratio.

## Requirements

- Dashboard size: 1200 x 900; 1 sheet
- Create a tile map showing 2017 vs 2018 profit ratio
  - 2018 = smaller square; 2017 = larger square
- Build a calculated field that shows the percentage change in profit ratio YoY and place on label
  - Formatting must match (use AZ, IL, and MI as references)
- Color profit ratio using the scale in the upper right
  - Color palette is Color Brewer Red Blue, using 8 equal steps (-1 to 1)
- Match all additional labels, tooltips, and formatting that you spot (including the year labels on Florida!)
- You are not allowed to use Level of Detail (LOD) Expressions!

## Dataset

This week uses a modified version of Superstore to allow for more variety and all 50 (+1) states.
