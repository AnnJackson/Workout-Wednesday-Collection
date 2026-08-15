# Week 27: How do current year sales compare to previous?

- **Published:** July 4, 2018
- **Original post:** https://www.workout-wednesday.com/week-27-how-do-current-year-sales-compare-to-previous/
- **Author:** Ann Jackson

## Introduction

For this week's workout I've decided to keep things simple and focus on creating one powerful alternative visualization for comparison over time. I think we all tend to get stuck in a bar chart rut and struggle to find ways to spice things up. I tend to do this a lot, especially when I am comparing large chunks of time. It is so easy to build out a bar chart with years or months on labels that go in sequential order. (And let's be honest, there's really nothing wrong with that!). But sometimes the sequential ordering of years prevents us from doing multiple comparisons at the same time. Bar charts can also get messy when there are tons of dimensions slicing up our view. Bar charts love vertical space.

So instead of a bar chart, this week we're building out dot plots! Dot plots have the advantage of using position instead of length for data comparisons. They can make it easier when looking at multiple comparative data points to spot trends or patterns. They become very powerful if what your audience cares about is something like a specific measurement compared to all other recordings of that measurement. You'll notice that the visualization forces you to focus on the color representing "current year" but you can't mentally map a trend of sales by year.

To help make the dot plot shine, I've found that adding a horizontal line works really well. The simple act of the horizontal line makes cognition quicker – grounded by the line scanning left to right becomes automatic. I've also spiced up the labels, colors, and tooltips to ensure that you keep strengthening your skills.

## Requirements

- Dashboard size: 1250 x 900, 2 sheets, tiled
- Each dot represents annual sales by subcategory
- Color of dots:
  - Most recent year below average = pink
  - Most recent year above average = blue
  - Not most recent year = gray
- Calculation for most recent year should work if data updates and 2018 gets added in (don't hard code 2017!)
- Match tooltip language – don't hard code the number of years, build a calculation!
- Match formatting: specifically horizontal line, banding, reference line
- Don't forget about the legend

I've added on a year filter so you can see what the tooltips and colors look like – I will be checking to see what happens if I filter out 2017!

## Dataset

This week uses the superstore dataset. [Get it here](https://github.com/Workout-Wednesday/data/blob/main/2021/Sample%20-%20Superstore.xls/workspace/file?filename=Sample+-+Superstore.xls).
