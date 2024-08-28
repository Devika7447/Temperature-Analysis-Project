# Temperature Analysis Near Ann Arbor, Michigan (2005-2015)

Project Overview

This project involves the analysis of temperature data from NOAA's Daily Global Historical Climatology Network (GHCN-Daily) for the region near Ann Arbor, Michigan, United States. The analysis focuses on visualizing temperature trends over a decade (2005-2014) and comparing these trends with data from 2015 to identify any record-breaking temperatures.

Data Sources

The dataset used in this project consists of two CSV files:

temperature.csv: Contains daily temperature records, including maximum and minimum temperatures.
BinSize.csv: Contains additional information about the bin size for temperature values.
These datasets provide daily climate records from land surface stations in the region.

Objectives

Visualize Record Temperatures (2005-2014):

Generate a line graph showing record high and low temperatures for each day of the year.
Shade the area between the record high and low temperatures to represent temperature variability.

Overlay 2015 Data:

Identify and plot points where the 2015 temperature data broke the 2005-2014 record highs or lows.

Handle Leap Years:

Exclude February 29th (leap day) from the analysis to maintain consistency across years.

Station Mapping:

Visualize the geographical location of weather stations near Ann Arbor, Michigan, using a map.

Temperature Summary for 2015:

Plot a temperature summary near Ann Arbor for the year 2015.

Project Structure

analysis_notebook.ipynb: Jupyter Notebook containing the analysis code, visualizations, and brief notes on each step.
data/: Directory containing the temperature.csv and BinSize.csv files.
README.md: This documentation file explaining the project.

Installation and Setup

To run this project, ensure you have Python installed along with the necessary libraries:

pandas,
matplotlib,
seaborn,
geopandas,
numpy.

Key Insights

Temperature Variability: The shaded regions in the line graph indicate significant variability in temperature, especially during the summer months. This suggests that the region experiences a wide range of temperatures, which may be due to various climatic factors.

2015 Temperature Records: Several points in 2015 broke the record highs and lows from the previous decade, indicating unusual temperature patterns that year.

Station Mapping: The map visualization provides a clear geographic context for the weather data, showing the distribution of temperature recording stations in the region.

Additional Notes

Out-of-Box Modules: The geopandas library was used for mapping the weather stations, as it provides easy-to-use tools for geospatial data analysis and visualization, which were essential for this project's geographical component.

Data Handling: Special attention was given to managing leap year data and ensuring consistent year-over-year comparisons.

Conclusion

This analysis highlights the variability in temperatures near Ann Arbor, Michigan, over a decade and reveals that 2015 was an unusual year with several record-breaking temperatures. The project demonstrates the importance of visualizing historical climate data to understand trends and anomalies.

