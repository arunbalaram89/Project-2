Projec ETL - Miniproject - Arun Balaram

Repo used for Miniproject
Github link: https://github.com/Hbentahila/Crowdfunding_ETL.git

Source of data
contacts.xlsx
crowdfunding.xlsx


Project Intro/Objective
The purpose of this project is to build an ETL pipeline using Python, pandas and then transforming the dataframes Once completedd, we then used Postgres SQL and Quick DBD to create an ERD Diagram along with Table Schemas. Each member created a Jupyter Notebook from each of the 4 databases that had to be created. Once completed, all 4 notebooks were merged into 1 notebook. An ERD Diagram was created to connect all 4 databases uses Quick DBD. The 4 csv files were then uploaded to the tables. 


Partners:
Arefin Shamsil
Hicham Bentahila
Shelly Girdhar Sakkerwal 



Methods Used/Technologies

Python
PostGres SQL, 
Pandas, 
Jupyter



Project Description

The data was very messy, and had to be cleaned. Ex. the dates were timestamps, the contact dataframe was all in 1 column. We had to split the category and subcategory data. The first thing was find out the data types in each column of each dataframe. Then we changed some column's datatype to better analyze the data. For the category and subcategory, after splitting the columns we then created a csv for each dataframe. With the campaign data, before submitting the cleaned version, we had to merge it with both the category and subcategory dataframes, then create a clean dataframe and csv. 


Needs of this project

Data exploration/descriptive statistics
Data processing/cleaning
statistical modeling
writeup/reporting




Steps involved

This  mini project was divided into the following subsections:
​
 - Create the Category and Subcategory DataFrames: Our team members Hicham Bentahila and Arefin Shamsil successfully created the Category and Subcategory DataFrames respectively with the category.csv and subcategory.csv as output files.
 - Create the Campaign DataFrame: Our team member Arun Balaram successfully created the Campaign DataFrame with the campaign.csv as output file
 - Create the Contacts DataFrame: Our team member Shelly successfully created the Contacts DataFrames with the contacts.csv as output file
 - Create the Crowdfunding Database: Our team collectively worked on crowdfunding database to establish and present the Entity Relationship Diagram (ERD) using Quick DBD (https://www.quickdatabasediagrams.com/)
- We successfully created the database tables and imported the csv files using the PostgreSQL.




Links to Jupyter file

ETL_Mini_Project_AShamsil_ABalaram_SSakkerwal_HBentahila.pynb - Merged Jupyter notebook 
ETL_Mini_Project_Starter_Code_CAMPAIGN_Dataframe.pynb - my section 









