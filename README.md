
## Project Overview

Healthcare_DB is a data engineering project developed as part of a technical assessment focused on healthcare analytics and large dataset processing.

The project demonstrates the complete lifecycle of a data engineering solution:

* Data Extraction from CDC Healthcare APIs
* Data Cleaning and Transformation
* PostgreSQL Database Loading
* Exploratory Data Analysis
* Data Visualization
* Data Architecture Design

The goal was to transform raw healthcare API data into a structured and queryable format suitable for analysis and reporting.

---

## Business Problem

Healthcare organizations generate large volumes of data that often arrive in unstructured nested/semi-structured formats.

This project demonstrates how healthcare data can be ingested from an external API, transformed into a clean structure, and stored in a relational database to support analytics and decision-making.

---

## Technology Stack

* Python
* Pandas
* NumPy
* PostgreSQL
* SQLAlchemy
* Matplotlib
* Jupyter Notebook

---

## Data Architecture

CDC Healthcare API
↓
Python Extraction Layer
↓
Data Validation
↓
Data Cleaning & Transformation
↓
PostgreSQL Database
↓
SQL Analysis
↓
Visualization & Reporting

---

## ETL Pipeline

### Extract

* Retrieved healthcare data from CDC public API.
* Parsed JSON response into structured tabular format.

### Transform

Transformations performed:

* Removed duplicate records.
* Standardized column names.
* Converted data types.
* Handled missing values.
* Cleaned categorical fields.
* Created analytical groupings.

### Load

* Loaded transformed data into PostgreSQL.
* Created structured tables.
* Enabled SQL querying and reporting.

---

## Results

The processed dataset was analyzed to understand:

* Dataset size
* Healthcare visit trends
* Demographic distributions
* Data quality characteristics
* Category frequency analysis

---

## Skills Demonstrated

* Data Engineering
* ETL Development
* API Integration
* PostgreSQL
* SQL
* Data Cleaning
* Data Analysis
* Data Visualization
* Healthcare Analytics

