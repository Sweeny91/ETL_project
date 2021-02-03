Team members: Erik Watson, Steven Sweeny, and Kathy Nguyen

# Project Description:

The goal of this project was to display the ability of performing ETL operations -> Extract. Transform. Load. 

Extracting, Transforming and Loading operations were performed on Pollution and Population Data from 2000 - 2010.
In this project the scope was limited to two major cities, New York City and Los Angeles. 
The datasets created from this proejct could be used to aid data scientists in the evaluation of the effects of population on various pollution levels over the years.

# Sources of data:

Datasets https://www.kaggle.com/sogun3/uspollution https://www.census.gov/data/datasets/time-series/demo/popest/intercensal-2000-2010-cities-and-towns.html

# Extraction:
Two csv files were extracted from kaggle and the US Census Bureau.
  The kaggle dataset combines multiple datasets from the US EPA arranged together in the same format. The dataset has gathered daily readings across the US, from 2000-2016, for four major pollutants (Nitrogen Dioxide, Sulphur Dioxide, Carbon Monoxide, and Ozone). 
  The US Census Bureau dataset contains city and town intercensal population data for all cities that reported to the Census Bureau between 2000-2010. The census is taken once every ten years, so the data between years 2000 and 2010 are estimates.

# Transformation:
Transformation tasks needed for analysis preparation included but were not limited to data type transformation, column manipulation, value checks, removal of incomplete records, pivoting, grouping, and table joins. These operations were performed in the jupyter notebook within the "project 2" folder. 

# Load:
Tables were manually created in pgAdmin using the query editor and then finalized dataframes produced in jupyter notebook were imported in these tables.
The tables produced in postgres were then loaded back into jupyter notebook using sqlalchemy to check for accuracy and correctness.

# Deliverables:
The finalized jupyter notebook containing the entire ETL process can be found in the "project 2" folder and exported csv files can be found in the "output_data" folder.
