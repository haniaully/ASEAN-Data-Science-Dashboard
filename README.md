✿ ASEAN Data Science Enablement Session 2024 — COVID-19 Dashboard ✿

![Dashboard Image](img/Story%20Hania%20Ully%20Hafizha%20-%20ASEAN%20Foundation.png)

## Overview
this dashboard, created using SAP Analytics Cloud, presents a comprehensive view of the COVID-19 situation across various ASEAN countries using historical data. the dashboard includes several features such as filters, bar charts, line charts, and a positivity rate indicator, providing insightful analysis and trends.

## Features Explanation

✿ **Filters**
- _**Location Filter**_: located on the left side, this filter allows users to select one or multiple countries from the ASEAN region. the data visualizations will adjust dynamically based on the selected locations.

✿ **New Cases per Location**
- _**Bar Chart**_: this chart displays the total number of new COVID-19 cases for the top 5 locations. 
  - _**Data**_: the chart shows the number of new cases for each country, with Indonesia, the Philippines, Malaysia, Myanmar, and Singapore being the top 5 countries.

✿ **New Tests per Location**
- _**Bar Chart**_: this chart represents the total number of new COVID-19 tests conducted in the top 5 locations.
  - _**Data**_: the chart highlights the testing efforts with the Philippines, Malaysia, Indonesia, Thailand, and Myanmar leading in the number of tests conducted.

✿ **Positivity Rate**
- _**Key Metric Indicator**_: the positivity rate is displayed prominently in the center, showing the percentage of positive COVID-19 cases out of the total tests conducted.
  - _**Data**_: as per historical data, positivity rate is 10.11%.

✿ **New Cases per Date**
- _**Line Chart with Forecast**_: this chart shows the trend of new COVID-19 cases over time, with an additional forecast component to predict future cases.
  - _**Data**_: the chart tracks the daily new cases from May 1, 2020, to July 1, 2021, with key milestones marked (e.g., 6,316 cases on September 1, 2020, and 18,285 cases on July 1, 2021). the forecast feature provides a projected trend based on historical data.

## How to Create This Dashboard in SAP Analytics Cloud

1. _**Create a New Story**_:
   - navigate to the 'Stories' tab and click 'Create New Story'.
   - select 'Canvas' to start with a blank canvas.

2. _**Add a Location Filter**_:
   - click on 'Filter' in the toolbar.
   - select 'Add Filter' and choose 'Location'.
   - configure the filter to include the desired countries.

3. _**Create New Cases per Location Bar Chart**_:
   - click on 'Insert' and select 'Chart'.
   - choose 'Bar/Column Chart'.
   - in the 'Builder' panel, set the 'Measures' to 'New Cases' and 'Dimensions' to 'Location'.
   - apply filters to show the top 5 locations.

4. _**Create New Tests per Location Bar Chart**_:
   - repeat the steps for the new cases bar chart.
   - set the 'Measures' to 'New Tests' and 'Dimensions' to 'Location'.
   - apply filters to show the top 5 locations.

5. _**Display Positivity Rate**_:
   - click on 'Insert' and select 'Numeric Point'.
   - set the measure to 'Positivity Rate'.
   - format the display to show percentage values.

6. _**Create New Cases per Date Line Chart with Forecast**_:
   - click on 'Insert' and select 'Chart'.
   - choose 'Line Chart'.
   - cn the 'Builder' panel, set the 'Measures' to 'New Cases' and 'Dimensions' to 'Date'.
   - enable the 'Forecast' feature in the chart settings to predict future trends.

## Data Source
the data used in this dashboard was provided by the organizers of the ASEAN Data Science Enablement Session 2024 _(ASEAN Foundation)_.

## Notes on SAP Analytics Cloud
while SAP Analytics Cloud offers powerful data viz. and analytical capabilities, it currently lacks an **Undo** feature. this limitation can be challenging as accidental changes to the dashboard cannot be easily reverted, potentially impacting the format you have carefully created.

_THANK YOU FOR READING MY WORK! ⋆˚✿˖° 𐙚 ₊ ⊹ ♡ — Hania Ully H._
