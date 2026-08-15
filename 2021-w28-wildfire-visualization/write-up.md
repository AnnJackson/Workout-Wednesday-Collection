# 2021 Week 28 | Tableau: Can you build an app to visualize wildfires?

- **Published:** July 13, 2021
- **Original post:** https://www.workout-wednesday.com/2021w28tab/
- **Author (byline):** Ann Jackson
- **GUEST CHALLENGE:** Written and built by Josh Jackson (Ann's husband). Josh typically prefers to stay in the background but asked to borrow one of Ann's weeks to share this challenge.

## Introduction

This week's Workout Wednesday is brought to you by Josh Jackson. For those who don't know, Josh is Ann's husband! He typically prefers to stay in the background, but asked if he could borrow one of Ann's weeks to share this challenge. Here's the challenge in his own words:

This week is inspired by a tool that Josh has always wanted. He likes to build calculators in Tableau that don't use any data and use Tableau's features to make something useful. He usually makes these so that they work on his phone and can be used at any time. There are a lot of wildfires in his area of the world (Phoenix, AZ) and the news always reports the size, but he didn't have any idea how big that size is. This tool draws a circle on a map for a given number of acres, and lets him draw that circle in a location where he knows how relatively big it is.

So that's the challenge for the week! Build an easy-to-use calculator that can quickly give you an idea of how big something is in acres.

For context, the largest recorded wildfire in Arizona is the Wallow Fire of 2011, which burned more than 522,000 acres. In 2021, the largest fire to date in AZ was the Telegraph Fire (recently contained on 7/4/21), which burned more than 180,757 acres.

Grand Canyon National Park (also in Arizona) is 1,218,375 acres (1,904 square miles).

## Requirements

- Dashboard Size: 400px by 700px
- # of Sheets – 2
- Create a map that shows a circle the size of the number of acres entered
  - Freebee: acres to feet calculation: SQRT(([Acres]*43560)/PI())
  - Disable all map controls
  - Allow users to zoom to pre-determined levels (1, 2, 5, 10, 50, 500 times the size of the circle on the map)
  - Allow users to pick pre-determined locations or enter custom coordinates (use your own locations that apply to you)
- Apply button needs to clear itself

Requires a version of Tableau with Map Layers (minimum 2020.4).

## Dataset

Copy paste this into Tableau to get started. Avoid connecting to a file if possible!

```
Data,
1,
2,
3,
4,
5
```
