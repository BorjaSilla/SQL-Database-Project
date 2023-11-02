# Project: Creating a Database from CSV Files using Pandas and SQL

![Project Cover](https://cdn.corporatefinanceinstitute.com/assets/database.jpeg)

## Intro

## Intro

This project aimed to create a comprehensive database from multiple CSV files by leveraging the power of Python with Pandas for data cleaning and MySQL for database creation. The primary objectives were to extract, clean, and structure the data for efficient storage, establish proper relationships within the database, and load the data. Here's an overview of the key project phases:

1. **Data Cleaning and Extraction**: Initially, Python with Pandas was used to extract data from the CSV files, followed by thorough data cleaning. This involved renaming columns, changing data types, dividing columns into subcolumns, merging tables to add more information, and establishing many-to-many relationships through table merges.

2. **Database Creation**: The database creation process involved MySQL. An Entity-Relationship Diagram (ERD) was meticulously designed to ensure the correctness of relationships between tables, correct data types, foreign keys, and constraints. The ERD served as the blueprint for structuring the database. Finally, the CSV data was loaded into the MySQL tables.

The project's deliverables include a Jupyter Notebook detailing the data cleaning and extraction process and an SQL script containing the necessary queries for creating the database based on the ERD.

Feel free to explore the project tree below to get a sense of the directory structure.

## Project Tree

```plaintext
project-root-directory/
├── clean_data/
│ ├── actor_clean.csv
│ ├── actor_film.csv
│ ├── category_clean.csv
│ ├── customer_rental_clean.csv
│ ├── customers_clean.csv
│ ├── film_clean.csv
│ ├── inventory_clean.csv
│ ├── language_clean.csv
│ └── rental_clean.csv
│
├── data/
│ ├── actor.csv
│ ├── category.csv
│ ├── film.csv
│ ├── inventory.csv
│ ├── language.csv
│ ├── old_HDD.csv
│ └──rental.csv
│
├── notebooks/
│ ├── cleaning.ipynb
│ └── customer_dummy.ipynb
│
├── sql/
│ ├── createdb.sql
│ └── customer_dummy.ipynb
│
└── README.md
```

## Data Cleaning and Extraction

In this phase, the following data cleaning and extraction steps were undertaken:

- Data was extracted from the CSV files into Pandas DataFrames.
- Columns were renamed and data types were modified as needed.
- Columns were divided into subcolumns to better structure the data.
- Multiple tables were merged to incorporate additional information.
- Many-to-many relationships were established using table merges.

## Database Creation

The database was created using MySQL with the following steps:

- An Entity-Relationship Diagram (ERD) was designed to define the relationships between tables, data types, foreign keys, and constraints.
- The ERD ensured the proper structure and integrity of the database.
- CSV data was loaded into the corresponding tables in the MySQL database.

## The Deliverables

The project includes the following deliverables:

1. `cleaning.ipynb` - A Jupyter Notebook that details the data cleaning and extraction process.
2. `customer_dummy.ipynb` - A Jupyter Notebook that contains the data generation and saving process.
3. `createdb` - An SQL script containing the database creation queries based on the ERD.
