# Week 34: Can You Build a Top N Bar Chart on a Single Worksheet?

- **Published:** August 21, 2019
- **Original post:** https://www.workout-wednesday.com/week-34-can-you-build-a-top-n-bar-chart-on-a-single-worksheet/
- **Author (byline):** Ann Jackson — **GUEST CHALLENGE submitted by Jeffrey Shaffer** (Community Contributor Month)

## Introduction

We're in week 3 of Community Contributor Month. This week's challenge is brought to us by Jeffrey Shaffer, a 4 time Tableau Zen Master, co-author of The Big Book of Dashboards, and maintainer of TableauReferenceGuide.com.

In Jeff's own words: "This Workout Wednesday comes from a real-world example where we wanted to show the top N dimensions within another dimension. This could be done on multiple worksheets, but building this on a single worksheet was more efficient. The dataset this week is the Superstore data and we will be showing the Top N Manufacturers by Region. The Manufacturers showing in the Top N will be different from Region to Region, but the 'Other' category of Manufacturer is the most frequent. Therefore, we will give the user the ability to turn on/off the 'Other' category of Manufacturer and enter how many N to show in the Top N. All of this should be done on a single worksheet."

## Requirements

- Single Worksheet
- Create a bar chart showing Quantity by Top N Manufacturers by Region (top N differ from region to region)
- Format the bar charts as close as possible:
  - Show Quantity in descending order
  - Right-align the Manufacturer name
  - Show the Quantity label on the bar and remove x-axis labels
  - Show a single line for the y-axis without any other lines
  - Color the Manufacturers, the bars and the labels by Region (ex. Nuriel Stone)
  - Remove Tooltip
- Use a parameter to control for N in the Top N
- Use a parameter to include/exclude the 'Other' category
- Use the Top N value in the title
- Highlight the Manufacturer name on hover
- Include the rank with the Manufacturer name on hover

## Dataset

This week uses the superstore dataset for Tableau 2019.1+.
