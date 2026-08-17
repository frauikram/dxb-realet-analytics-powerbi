# DXB RealET 🏙️

## Dubai Real Estate Market Tracker — Power BI Dashboard

DXB RealET is an interactive market intelligence dashboard analyzing analyzing Dubai real estate transaction activity, market value, property types, and geographic trends using Dubai Land Department transaction data.

### Dashboard Overview

The dashboard provides a one-page executive view of the Dubai real estate market, focusing on:

- **Total Transactions**
- **Total Transaction Value**
- **Average Deal Size**
- **Average Price per Sq. Ft.**
- **Transaction Volume Trends**
- **Month-over-Month (MoM) Changes**
- **Property Type Distribution**
- **Transaction Activity by Area**
- **Freehold vs. Non-Freehold Properties**
- **Off-Plan vs. Completed Transactions**

### Data

The dashboard is built using Dubai real estate transaction data published by the **Dubai Land Department (DLD)**.

The dataset contains transaction-level information including:

- Transaction date
- Transaction number
- Transaction value
- Sale price per square meter
- Area
- Property type and subtype
- Usage
- Rooms
- Parking
- Freehold status
- Off-plan status

The raw data was cleaned and prepared in **Power Query** before being modeled in Power BI.

### Data Preparation

The Power BI workflow includes:

1. Importing the DLD transaction data
2. Cleaning and standardizing fields
3. Removing invalid and duplicate records
4. Handling missing and malformed dates
5. Standardizing categorical values
6. Creating a dedicated Date table
7. Building relationships between the Date table and transaction data
8. Creating reusable DAX measures
9. Designing the final analytical dashboard

### Key DAX Measures

The dashboard uses DAX measures for core KPIs and time-based analysis, including:

- Total Transactions
- Total Transaction Value
- Average Deal Size
- Average Price per Sq. Ft.
- Previous Month Transactions
- Month-over-Month Transaction Change
- Transaction Value MoM Change

### Dashboard Design

The dashboard follows a clean **light-purple analytical theme** with a one-page layout designed for quick business interpretation.

The visual hierarchy prioritizes:

**KPIs → Market Trend → Property Mix → Geographic / Area Analysis**

This makes it possible to quickly identify changes in transaction activity and understand which property segments and areas are driving the market.

### Tech Stack

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **CSV**
- **Git / GitHub**

### Project Roadmap

This dashboard represents the **Power BI analytics layer** of the larger DXB RealET project.

The planned end-to-end architecture will extend the project with:

- Python-based data ingestion
- Synthetic incremental transaction generation
- PostgreSQL
- Snowflake
- DuckDB
- dbt
- Airflow
- Docker
- GitHub Actions
- AWS
- Medallion-style data architecture
- Production-oriented data quality and transformation workflows

The Power BI dashboard serves as the presentation and business intelligence layer of the broader **DXB RealET Analytics Engineering project**.

## Repository

**Project:** 'github.com/frauikram/dxb-realet-analytics-powerbi'

**Focus:** Dubai Real Estate Market Analytics & Analytics Engineering

_Built by_ [frauikram](https://github.com/frauikram)