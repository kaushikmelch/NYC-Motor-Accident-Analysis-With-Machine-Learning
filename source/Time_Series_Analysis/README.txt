README for NYC Motor Accidents Data Science Project Code


1. Time Series Analysis

Notebook: NYC_Motor_Accidents_Time_Series_Analysis.ipynb
Datasets: 

1) Original_Dataset_With_Location_Imputed.csv : Use this dataset to run the "Analyze Dataset" section
2) TimeSeries_Final_Dataset.csv : Use this dataset to run from the "Import Final Dataset" section.

This notebook contains the code for the Time Series Analysis of NYC Motor Accidents data for the 5 Boroughs. The cells can be run sequentially to reproduce the results.

For quick execution, run the first section which is to install and import libraries and then begin from the section "Import Final Dataset" as Data Preprocessing has been completed and stored in a new csv file called "TimeSeries_Final_Dataset.csv".

Data Preprocessing section will take time to run(8-9 hours) as it involves transforming the dataset and also making 56k API calls to reverse geocode.

You can take a look at the preprocessing approach in the notebook, but for quick execution of model use the 2nd dataset mentioned above and run from "Import Final Dataset" section.