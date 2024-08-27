README for NYC Motor Accidents Data Science Project Code


Geo Spatial Analysis

Notebook: NYC_Motor_Accidents_GeospatialAnalysis.ipynb


Datasets: 

1) Geospatial_Analysis_cleaned_dataset.csv : This dataset contains the cleaned dataset for Geospatial Analysis.

Feedback Incorporated into the IPYNB:

During the project presentation, professor pointed out that visualization of the number of accidents in each neighborhood per accident cause was difficult to interpret. Initially, presenting this data was challenging due to the diverse nature of accident reasons, which made interpretation difficult. In response, we implemented an enhanced bar plot using Plotly, allowing for more flexibility and interactivity. The new visualization not only offers a clearer representation of the data but also allows users to zoom in, facilitating a more detailed and accurate interpretation of the results. This approach significantly improves readability and enhances overall understanding, providing a more insightful perspective on accident causes across different neighborhoods.


How to run the code?

1. Run the "Imports", "Load Dataset" section - use "Geospatial_Analysis_cleaned_dataset.csv" dataset.
2. Run "Some Visualizations on the dataset" section
3. Run "Creting Global Helper Function"	section
4. SKIP "Creating New Column", "Data Cleaning" and "Task: Handle Missing Data" sections.
5. Steps to run "Feature - Data Visualization":
	A. SKIP "Some Analysis on the location,latitude and longitude fields."
	B. Run each block under "Feature: Borough Specific Plotting." section.


Overview
The geospatial feature of the project involves an in-depth analysis of traffic accidents within specific boroughs, leveraging geospatial data to provide insights crucial for improving road safety. Various visualizations and analyses have been performed to understand accident severity, causes, and fatality trends within different areas.

Features
a. Plot Location Borough-wise Killed Severity
Functionality: Generates a Folium map plotting accident coordinates based on severity within a specific borough.
Parameters: Customizable 'killed_threshold' for analysis.
b. Plot Location Borough-wise Injury Threshold
Similar to the above feature but focuses on injuries, offering insights into the geographical distribution of accidents.
c. Plot Road Infrastructure Issue Locations
Identifies and plots latitude and longitude related to accidents caused by road infrastructure issues.
Aids road departments in pinpointing areas needing fixes for safer roads and better traffic flow.
d. Bar Chart - Accident-related Deaths by Borough
Compares and highlights differences in accident-related fatalities across different boroughs.
Helps prioritize areas needing more attention or safety measures.
e. Bar Chart - Borough-wise Death Counts by Year
Provides a year-wise overview of death counts in a specific borough.
Offers insights into trends and patterns in road safety over time.
f. Consolidated Bar Plot - Pedestrian, Motorist, and Cyclist Deaths
Month-wise breakdown of deaths for pedestrians, motorists, and cyclists within a specific borough.
Enables spotting patterns or spikes in different months for targeted interventions.
g. Bar Plot - Borough-wise Accident Causes Leading to Deaths
Displays the number of deaths in a borough caused by different types of accidents.
Aids in pinpointing primary accident causes leading to fatalities for targeted safety measures.
h. Refined Bar Plot - Neighborhood-wise Accident Causes
Provides a detailed view of accidents attributed to various causes within specific neighborhoods.
Offers localized analysis for better understanding and intervention planning.
Usage
Each function or visualization can be accessed independently to extract specific insights from the provided dataset. The README within each function file contains detailed instructions on usage and parameters.

Conclusion
This project aims to empower traffic authorities and road departments with actionable insights derived from geospatial analysis, aiding in the identification of hotspots, causes, and trends for more targeted safety measures and interventions.

