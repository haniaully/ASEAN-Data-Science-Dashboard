✿ ASEAN Data Science Enablement Session 2024 — COVID-19 Dashboard ✿

![Dashboard Image](img/Story%20Hania%20Ully%20Hafizha%20-%20ASEAN%20Foundation.png)

## Overview
This dashboard, created using SAP Analytics Cloud, presents a comprehensive view of the COVID-19 situation across various ASEAN countries using historical data. The dashboard includes several features such as filters, bar charts, line charts, and a positivity rate indicator, providing insightful analysis and trends.

## Features Explanation

✿ **Filters**
- _**Location Filter**_: Located on the left side, this filter allows users to select one or multiple countries from the ASEAN region. The data visualizations will adjust dynamically based on the selected locations.

✿ **New Cases per Location**
- _**Bar Chart**_: This chart displays the total number of new COVID-19 cases for the top 5 locations. 
  - _**Data**_: The chart shows the number of new cases for each country, with Indonesia, the Philippines, Malaysia, Myanmar, and Singapore being the top 5 countries.

✿ **New Tests per Location**
- _**Bar Chart**_: This chart represents the total number of new COVID-19 tests conducted in the top 5 locations.
  - _**Data**_: The chart highlights the testing efforts with the Philippines, Malaysia, Indonesia, Thailand, and Myanmar leading in the number of tests conducted.

✿ **Positivity Rate**
- _**Key Metric Indicator**_: The positivity rate is displayed prominently in the center, showing the percentage of positive COVID-19 cases out of the total tests conducted.
  - _**Data**_: As per historical data, positivity rate is 10.11%.

✿ **New Cases per Date**
- _**Line Chart with Forecast**_: This chart shows the trend of new COVID-19 cases over time, with an additional forecast component to predict future cases.
  - _**Data**_: The chart tracks the daily new cases from May 1, 2020, to July 1, 2021, with key milestones marked (e.g., 6,316 cases on September 1, 2020, and 18,285 cases on July 1, 2021). The forecast feature provides a projected trend based on historical data.

## How to Create This Dashboard in SAP Analytics Cloud

1. _**Create a New Story**_:
   - Navigate to the 'Stories' tab and click 'Create New Story'.
   - Select 'Canvas' to start with a blank canvas.

2. _**Add a Location Filter**_:
   - Click on 'Filter' in the toolbar.
   - Select 'Add Filter' and choose 'Location'.
   - Configure the filter to include the desired countries.

3. _**Create New Cases per Location Bar Chart**_:
   - Click on 'Insert' and select 'Chart'.
   - Choose 'Bar/Column Chart'.
   - In the 'Builder' panel, set the 'Measures' to 'New Cases' and 'Dimensions' to 'Location'.
   - Apply filters to show the top 5 locations.

4. _**Create New Tests per Location Bar Chart**_:
   - Repeat the steps for the new cases bar chart.
   - Set the 'Measures' to 'New Tests' and 'Dimensions' to 'Location'.
   - Apply filters to show the top 5 locations.

5. _**Display Positivity Rate**_:
   - Click on 'Insert' and select 'Numeric Point'.
   - Set the measure to 'Positivity Rate'.
   - Format the display to show percentage values.

6. _**Create New Cases per Date Line Chart with Forecast**_:
   - Click on 'Insert' and select 'Chart'.
   - Choose 'Line Chart'.
   - In the 'Builder' panel, set the 'Measures' to 'New Cases' and 'Dimensions' to 'Date'.
   - Enable the 'Forecast' feature in the chart settings to predict future trends.

## Data Source
The data used in this dashboard was provided by the organizers of the ASEAN Data Science Enablement Session 2024.

## Notes on SAP Analytics Cloud
While SAP Analytics Cloud offers powerful data visualization and analytical capabilities, it currently lacks an **Undo** feature. This limitation can be challenging as accidental changes to the dashboard cannot be easily reverted, potentially impacting the format you have carefully created.

_THANK YOU FOR READING MY WORK! ⋆˚✿˖° 𐙚 ₊ ⊹ ♡ — Hania Ully H._
