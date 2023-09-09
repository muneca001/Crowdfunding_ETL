# ETL Project 

## Project Overview

This ETL (Extract, Transform, Load) mini project was collaboratively developed by Jolyciel Fullerton and Luis Rodriguez. The goal of this project was to create a Crowdfunding Database from raw data provided in Excel files, following specific data transformation and database schema requirements.

## Project Files and Structure

- **ETL_Mini_Project_LRodriguez_JFullerton.ipynb**: This Jupyter Notebook file contains the Python code used to perform the data extraction, transformation, and loading (ETL) processes. It includes the creation of DataFrames, data cleansing, and exporting to CSV files.

- **Schema**: This folder contains the SQL schema file required to create the Crowdfunding Database. Specifically, the file `crowdfunding_db_schema.sql` outlines the database structure and table definitions.

- **ERD**: This folder holds a screenshot of the Entity-Relationship Diagram (ERD) for the Crowdfunding Database. It also contains the code used to create the ERD, which may be useful for reference.

- **Resources**: This folder contains the original Excel files with the raw data provided for the project. Additionally, it includes the newly created CSV files that resulted from the data transformation process.

## Data Transformation and CSV Export

### Category DataFrame
- A Category DataFrame was created, containing "category_id" and "category" columns.
- The Category DataFrame was exported to a CSV file named `category.csv`.

### Subcategory DataFrame
- A Subcategory DataFrame was created, containing "subcategory_id" and "subcategory" columns.
- The Subcategory DataFrame was exported to a CSV file named `subcategory.csv`.

### Campaign DataFrame
- A Campaign DataFrame was created with columns including "cf_id," "contact_id," "company_name," "description," "goal," "pledged," "outcome," "backers_count," "country," "currency," "launch_date," "end_date," "category_id," and "subcategory_id,".
- The Campaign DataFrame was exported to a CSV file named `campaign.csv`.

### Contacts DataFrame
- A Contacts DataFrame was created with columns "contact_id," "first_name," "last_name," and "email".
- The Contacts DataFrame was exported to a CSV file named `contacts.csv`.

## Crowdfunding Database Creation

- A Crowdfunding Database was created using the SQL schema defined in the `crowdfunding_db_schema.sql` file. This schema was designed to showcase database structure.

## Data Verification

- To ensure data was correctly loaded into the Crowdfunding Database, SELECT * statements were executed on each table, and the results were reviewed for accuracy.

## Conclusion

This ETL mini project demonstrates our ability to extract, transform, and load data effectively to create a functional database. The Crowdfunding Database is now ready for use.

