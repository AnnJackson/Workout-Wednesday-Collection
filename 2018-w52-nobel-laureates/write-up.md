# Week 52: Nobel Laureates, 1901 to Present

- **Published:** December 26, 2018
- **Original post:** https://www.workout-wednesday.com/week-52-nobel-laureates-1901-to-present/
- **Author:** Ann Jackson

## Introduction

Congratulations for making it to the end of 2018 and the last workout of the year! This week I've spiced things up a bit and decided to use a different data set. The data you'll be working with is a list of Nobel Prize Laureates from 1901 to 2018 ('present' at time of writing). And I've chosen to use the data set to construct a timeline view.

This data set comes from a real life problem I solved recently – a way to work with multiple date columns to construct timelines. You'll be forced to work with the data set as-is, no reshaping the data. And the goal is to display multiple dates as marks of different colors. And true to form, you'll also be constructing some custom labels, and be working on creating a drop-down that sorts both alphabetically and by dates.

## Requirements

- Dashboard size: 1000 x 1200; you choose # of sheets
- Create a timeline showing birth date, prize date(s), death date or today
  - Death date will be a circle, today will be a gantt bar
  - Assume that each prize is awarded on December 10th of every year
- Color the dots of the prize dates according to their category
- Create a line that goes from birth date to death/today depending on the person
- Construct a label that is beneath each person's timeline – make sure it only shows up once
  - Include critical birth/death dates
- Create reference lines for December 1901, the first year of the prize and today (which should be dynamic)
- Create a legend that acts as a filter
- Construct sorting for each of the following: alphabetical, birth date newest/oldest, prize date newest/oldest, death date newest/oldest
- Match formatting & tooltips (Tableau Medium and Tableau Bold fonts; colors from Superfishel Stone)

## Dataset

This week uses a special Nobel Laureates data set modified from Kaggle (to include more birthdays, and default birth dates to January 1 of the year if unknown).
