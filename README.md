# UPI Transaction Analysis Dashboard

An interactive Power BI dashboard built to analyze UPI transaction
activity across different cities, banks, payment methods, transaction
types, customer demographics, and months.


## Project Overview

This project uses an Excel dataset containing **20,000 UPI transaction
records** from 2024. The data was loaded into Power BI Desktop and
transformed into an interactive two-page dashboard.

The report focuses on monthly transaction trends, transaction amounts,
remaining balances, and filtering the data across multiple dimensions.

## Key Features

-   Data loading and profiling in Power BI
-   Custom Age Group column
-   Monthly transaction trend analysis using a line chart
-   Matrix visual for Amount and Remaining Balance
-   Interactive slicers for:
    -   Bank Name Sent
    -   Bank Name Received
    -   City
    -   Device Type
    -   Gender
    -   Age Group
    -   Merchant Name
    -   Payment Method
    -   Purpose
    -   Transaction Type
-   Synced slicers across report pages
-   Conditional formatting
-   Bookmarks for switching between Amount and Remaining Balance
-   Report publishing workflow for Power BI Service

## Dataset

The dataset contains **20,000 transaction records** and **20 columns**.

Some of the main fields include:

  Field              Description
  ------------------ ------------------------------------------
  TransactionID      Unique transaction identifier
  TransactionDate    Date of the transaction
  Amount             Transaction amount
  BankNameSent       Sending bank
  BankNameReceived   Receiving bank
  RemainingBalance   Balance remaining after the transaction
  City               Transaction/customer city
  Gender             Customer gender
  TransactionType    Type of transaction
  DeviceType         Device used for the transaction
  PaymentMethod      Payment method
  MerchantName       Merchant associated with the transaction
  Purpose            Transaction purpose
  CustomerAge        Customer age
  Currency           Transaction currency

## Tools Used

-   **Microsoft Power BI Desktop**
-   **Microsoft Excel**
-   Data profiling
-   Data visualization
-   Slicers and filters
-   Matrix visual
-   Line chart
-   Conditional formatting
-   Bookmarks
-   Slicer synchronization
-   Power BI Service

## Learning Reference

This project was created while following a structured Power BI course.
The lessons used for this project covered:

1.  Loading Data into Power BI Desktop
2.  Data Profiling
3.  Sizing and Positioning Slicers
4.  Formatting Slicers
5.  Adding a Page and Age Group Column
6.  Adding a Line Chart
7.  Adding a Matrix Visual
8.  Syncing Slicers and Applying Conditional Formatting
9.  Adding Bookmarks for Transactions
10. Adding Bookmarks for Remaining Balance
11. Publishing the Report to Power BI Service

The project gave me hands-on practice with building an interactive Power
BI report and understanding how different Power BI features work
together.

## Project Structure

``` text
UPI Transaction Analysis Dashboard/
│
├── README.md
│
├── Data/
│   └── UPI+Transactions.xlsx
│
├── Power BI/
│   └── UPI Report.pbix
│
└── Screenshots/
    ├── 1.png
    └── 2.png
```
and presenting information through multiple visualizations.

This project is part of my Power BI learning journey. My next step is to
build more original projects where I independently define the business
problem, KPIs, analysis, and dashboard design.
