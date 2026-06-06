# Power BI Data Transformation Assignment

## Overview

This project demonstrates a complete data transformation process using Power Query in Power BI. The objective is to integrate multiple data sources into a single consolidated dataset that matches the structure provided in the assignment output file.

## Data Sources

The following source files were used:

* `orders.txt`
* `order lines.txt`
* `Customers.xlsx`
* `Products.json`
* `ISO-3166-Countries-with-Regional-Codes.csv`
* `Age groups.txt`

These files contain order information, customer details, product data, country information, and age classification rules.

## Transformation Process

The data transformation process was implemented using Power Query and includes the following steps:

1. Import all source files.
2. Standardize data types.
3. Clean and prepare source data.
4. Calculate customer age using date of birth.
5. Classify customers into age groups.
6. Enrich customer data with country and regional information.
7. Join orders with order lines.
8. Join product information.
9. Calculate the sales amount using:

```text
Amount = Units × Unit Price
```

10. Generate a final consolidated dataset.

## Data Model

The final dataset is built using the following relationships:

* Customer ID
* Order ID
* Product ID
* Country Code

## Output

The resulting table contains:

* Customer information
* Geographic information
* Order details
* Product details
* Sales metrics

The output structure matches the requirements specified in the assignment.

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* Excel
* CSV
* JSON
* TXT

## Repository Structure

```text
.
├── data/
│   ├── orders.txt
│   ├── order lines.txt
│   ├── Customers.xlsx
│   ├── Products.json
│   ├── ISO-3166-Countries-with-Regional-Codes.csv
│   └── Age groups.txt
│
├── Assignment1_Data_Transformation_Strategy.docx
├── Assignment2.pbix
├── README.md
```

## Author

Maria Isabel Ortiz Naranjo

Master in Big Data & Analytics

EAE Business School
