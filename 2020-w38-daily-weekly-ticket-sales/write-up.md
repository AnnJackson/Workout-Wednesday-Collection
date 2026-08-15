# 2020 Week 38: Can you Visualize Daily and Weekly Ticket Sales in the Same View?

- **Published:** September 16, 2020
- **Original post:** https://www.workout-wednesday.com/2020w38/
- **Author:** Guest challenge — Jami Delagrange (posted under Ann Jackson's WOW byline)

## Introduction

Jami Delagrange is responsible for this week's Community Workout Wednesday Challenge. Here are all the details in Jami's own words:

A few months ago, I was working with conference registration data and the event team asked the question, "can we look at daily and weekly registrations in the same view?" The chart below is an adaption of that request using generic event data focused on ticket sales.

The daily view provides a space to highlight specific dates. I am only exposing the launch date and event date in this example, but it's a great area to display marketing promotions (like early bird discounts, etc.). The weekly view is a quick way to recognize pacing across the event year or YoY event comparison.

This week's challenge is more intensive from a data modeling perspective and understanding how to manipulate dates; however, an extract file is also provided if you want to jump right into the visualization.

## Requirements

- Dashboard Size: 1600px by 900px
- # of Sheets – 1
- Create a dual axis chart showing:
  - Total Daily Ticket Sales
  - Total Weekly Ticket Sales
- Set each event to start during the week of the launch date
- Set each event to end during the week of the event date
- Set each week to start on a Monday
- The full 7 days are always available within each week
- Color:
  - Daily – based on important dates (launch date, event date, regular)
  - Weekly – percent of total sales (money green #7a996d)

## Dataset

This week uses a custom dataset based on an event that happens twice a year, with 3 events packed into a weekend (small, medium, large/massive), repeating. Provided as either raw CSVs to build the data model from scratch (DimDate, DimEvent, DailyAggEventTicketSales) or a pre-built Tableau extract.
