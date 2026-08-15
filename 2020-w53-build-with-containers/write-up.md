# 2020 Week 53: Can you build with containers?

- **Published:** December 30, 2020
- **Original post:** https://www.workout-wednesday.com/2020w53/
- **Author:** Guest challenge — Brad Werner (posted under Ann Jackson's WOW byline)

## Introduction

Brad Werner is responsible for this week's Workout Wednesday Challenge. Here are all the details in Brad's own words:

I have a confession. When I first started using Tableau, I was a strict advocate for #TeamFloating. Yes, I used to float ALL objects on my Tableau dashboards. I would decide on a dashboard layout and then calculate the pixel height and widths needed in order to make everything look just right. Not fast or scalable.

Then came along a Workout Wednesday challenge that changed my approach to dashboard design and converted me to #TeamTiled: Rody Zakovich's 2018 Week 51 challenge titled Container Fun.

This challenge helped me to see that any layout I wanted to use was just a combination of vertical/horizontal containers and inner/outer padding. I can now look at any design inspiration, deconstruct it into containers/padding, and recreate it in Tableau.

If you struggle with containers, please know that it is not just you. Containers continue to be a popular topic in the Tableau community.

I am excited to bring back a container challenge to Workout Wednesday in the hopes that it can help others learn about all the awesome ways that containers can improve the look of their dashboards. This technique, combined with using Tableau's format tools to maximize the data to ink ratio, is a sure way to improve the look of your dashboards.

## Requirements

- Dashboard Size: 1200px by 800px
- ONLY USE CONTAINERS, NO FLOATING OBJECTS! (Brad's version uses 6 containers)
- The background of the dashboard is light gray (#f5f5f5 – "The top gray")
  - But notice the title bar is white all the way across
  - Grab the logo from the top of the WorkoutWednesday website navigation bar; add 5px of outer padding
- This layout utilizes a card-style design. There are 4 cards (1 KPI card and 3 segment cards). Each card has 10px of padding around them and 10px of padding within them.
- Each card also has a solid, thin, and slightly darker gray border (#d4d4d4 – "The third from the top gray")
- The three Segment cards each contain the following items (anything without padding specified defaults to 4px outer padding):
  - A text header
  - A colored divider 3px tall with 10px of padding on both ends
  - A BAN showing total sales for the column's segment
  - A gray (#d4d4d4) divider 2px tall with 30px of padding on both ends
  - An area chart showing quarterly sales for the column's segment
- Colors used (feel free to give it your own spin): Red #F57D7C, Teal #6CC2BD, Blue #5A809E, Purple #7C79A2

## Dataset

This week uses the superstore dataset for Tableau 2020.3. Since this challenge focuses on containers and structure, data accuracy matters less, so feel free to use whatever version of superstore you have on hand.
