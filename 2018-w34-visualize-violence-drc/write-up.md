# Week 34: Building an Interactive Display to Visualize Violence in the DRC

- **Published:** August 22, 2018
- **Original post:** https://www.workout-wednesday.com/week-34-building-an-interactive-display-to-visualize-violence-in-the-drc/
- **Author:** Ann Jackson

## Introduction

This week we're visualizing conflict data provided by ACLED. ACLED, which stands for Armed Conflict Location & Event Data Project, is a "disaggregated conflict collection, analysis and crisis mapping project." Throughout the Tableau Community this week there were several partner projects going on – all designed to provide awareness on ACLED's cause. Zen Masters Anya A'Hearn and Allan Walker were responsible for orchestrating this massive collaboration campaign.

For Workout Wednesday's part, the brief was: "Create a map for the Democratic Republic of the Congo in which we depict where specific actors have engaged in violence. This way we can begin to understand what locations have seen a multitude of actors engaging in violence. With the recent Ebola outbreak in the DRC, humanitarian groups are interested in understanding what groups may be most active and in which locations they have engaged in violence." This included a specific data set focused on militant groups within the DRC and including a record for each actor engaged in a specific event (and as you can imagine, there's usually multiple parties involved in a violent event). It's important to recognize that this data set is different than ACLED's traditional event-based set, which is not narrowly limited to the DRC or militant groups.

So the focus and challenge for this workout turned into creating an interactive display that would allow humanitarian groups to explore specific areas and quickly gain insight into recent violent acts.

## Requirements

- Dashboard size: 1200 x 800; 8 sheets (7 tiled, 1 float)
- Create a map of each event with color & shape depicting year
- Create BAN of total involved actors
- Create bar chart of # events by year, including custom legend & highlight on map
- Create treemap of most involved actors, # events involved in, date of last activity, and viz in tooltip version of map
- Create a section showing most recent event and militants involved
- Mechanics of Interactivity
  - Users should be able to select marks on the map using either the rectangle, radial tool, or lasso; users shouldn't be able to re-position map, or exclude points
  - Filtering on the map should affect the charts on right
  - The viz in tooltip displays each event for actor, and also reflects filtering of the larger map and includes labels of locations
  - When a recent event includes more than 200 characters in the description, it should have an ellipsis (…) display in the sheet space, however the tooltip should include the full description
  - Date range at top should filter appropriately
- Additional inclusions
  - Hover-over information button
  - Logo for ACLED
  - Icon for mouse selection
- Pay attention to the titles, particularly the overall dashboard title section
- White space matters on this one

## Dataset

Data from this week was provided by ACLED. [Get it here](https://github.com/Workout-Wednesday/data/blob/main/2018/for%20Workout%20Wednesday.csv).
