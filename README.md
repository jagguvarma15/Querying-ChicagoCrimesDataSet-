# Querying-ChicagoCrimesDataSet-
<html>
  <body>
    <h2>Introduction</h2>

<h4>Using this Python notebook you will:<h4>

Understand three Chicago datasets
Load the three datasets into three tables in a Db2 database
Execute SQL queries to answer assignment questions
Understand the datasets
To complete the assignment problems in this notebook you will be using three datasets that are available on the city of Chicago's Data Portal:

  <code>Socioeconomic Indicators in Chicago</code><br>
  <code>Chicago Public Schools</code><br>
  <code>Chicago Crime Data</code>

  <h3>1. Socioeconomic Indicators in Chicago</h3>
This dataset contains a selection of six socioeconomic indicators of public health significance and a “hardship index,” for each Chicago community area, for the years 2008 – 2012.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

  <h3>2. Chicago Public Schools</h3>
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. This dataset is provided by the city of Chicago's Data Portal.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

  <h3>3. Chicago Crime Data</h3>
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

<h4>Download the datasets</h4>
This assignment requires you to have these three tables populated with a subset of the whole datasets.

In many cases the dataset to be analyzed is available as a .CSV (comma separated values) file, perhaps on the internet. Click on the links below to download and save the datasets (.CSV files):

  <code>Chicago Census Data</code>

  <code>Chicago Public Schools</code>

  <code>Chicago Crime Data</code>

NOTE: Ensure you have downloaded the datasets using the links above instead of directly from the Chicago Data Portal. The versions linked here are subsets of the original datasets and have some of the column names modified to be more database friendly which will make it easier to complete this assignment.

Store the datasets in database tables
To analyze the data using SQL, it first needs to be loaded into SQLite DB. We will create three tables in as under:

CENSUS_DATA<br>
CHICAGO_PUBLIC_SCHOOLS<br>
CHICAGO_CRIME_DATA<br>
  
Let us now load the ipython-sql extension and establish a connection with the database
  
<q><h5>Note : This Repository contains iPython Notebook which is part of my DataBases_and_SQL_for_Data_Science(week-5) Coursera Course Assignment</h5></q>
</body>
  </html>
