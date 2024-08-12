# Global-Energy-Trade-Analysis-Power-Bi-Project
To create a Global Energy Trade Analysis dashboard in Power BI using a donut chart, line chart, and map, you can follow these steps:

Step 1: Data Preparation
Data Sources: Collect data related to global energy trade, including imports, exports, trade balance, and energy types (e.g., oil, gas, coal, renewables). The data should include country/region information, trade volumes, trade values, and time periods.
Data Cleaning: Ensure that the data is clean and structured, with relevant fields like country, energy type, trade volume/value, and dates.
Step 2: Load Data into Power BI
Open Power BI Desktop.
Click on Get Data and load your data from the respective sources (e.g., Excel, SQL Server, APIs).
Use Power Query to clean and transform the data as needed, ensuring that fields are correctly formatted and ready for analysis.
Step 3: Designing the Dashboard Layout
Donut Chart (Trade Breakdown by Energy Type):

Add a Donut Chart from the Visualizations pane.
Set the Legend to different energy types (e.g., oil, gas, coal, renewables).
Set the Values to the trade volume or trade value for each energy type.
This chart will show the proportion of each energy type in the global energy trade.
Line Chart (Trade Trends Over Time):

Select the Line Chart from the Visualizations pane.
Set the Axis to the time period (year, quarter, month).
Set the Values to trade volumes or values.
Optionally, use Legend to differentiate between energy types or regions.
This chart will illustrate how energy trade has evolved over time.
Map (Geographical Distribution of Energy Trade):

Choose the Map visual from the Visualizations pane.
Set the Location field to the country/region.
Set the Size or Color Saturation to represent trade volumes or values.
This map will display the global distribution of energy trade, showing which countries are the biggest importers/exporters.
Step 4: Add Interactivity
Slicers: Add slicers for energy type, trade type (import/export), and time period to allow users to filter the data.
Cross-filtering: Enable cross-filtering between visuals so that selecting a segment on the donut chart or a point on the map automatically updates the other visuals.
Step 5: Enhance Visualizations
Formatting: Customize the visuals by adjusting colors, fonts, and labels to ensure clarity and visual appeal.
Tooltips: Enhance tooltips to provide additional context, such as trade partner countries or changes in trade volumes over time.
Titles and Labels: Add descriptive titles and axis labels to make the dashboard easy to understand.
