
# Automated Retail Inventory and Sales Analysis

## Project Overview

This project uses **Microsoft Excel and Power Query** to automate the preparation, cleaning, validation, and analysis of retail sales and inventory data.

The objective is to create a repeatable data-processing workflow that reduces manual data preparation and produces structured outputs for retail business analysis.

## Business Problem

Retail sales and inventory datasets contain large volumes of records that require consistent cleaning, standardization, and validation before they can be used for analysis.

Manually processing updated files can be time-consuming and may introduce inconsistencies.

This project addresses that problem through an Excel Power Query workflow that processes Sales and Inventory CSV files and refreshes the resulting outputs.

## Project Objectives

- Automate the ingestion of Sales and Inventory CSV files.
- Clean and standardize source data.
- Apply data-quality checks and validation rules.
- Create structured sales and inventory analysis outputs.
- Establish a repeatable refresh workflow using Excel Power Query.

## Tools and Technologies

- Microsoft Excel
- Power Query
- CSV datasets
- GitHub

## Dataset Information

**Source:** Mendeley Data – Retail Transactions and Stocks Data

**DOI:** [10.17632/27x8mjm8k4.1](https://doi.org/10.17632/27x8mjm8k4.1)

**License:** CC BY 4.0

**Data Coverage:** 1 June 2025 – 24 April 2026

The source datasets contain retail sales and inventory records across multiple stores and products.

## Project Workflow

1. Import Sales and Inventory CSV files into Power Query.
2. Apply data cleaning and standardization.
3. Set appropriate data types.
4. Create data-quality flags.
5. Perform schema and data-type error checks.
6. Generate structured analysis outputs.
7. Refresh the workbook when updated source files are available.

### Refresh Process

1. Replace the source CSV files using the same filenames and folder paths.
2. Open the Excel workbook.
3. Select **Data → Refresh All**.
4. Review the refreshed outputs.

## Completed Business Analysis

The project includes four completed business analysis outputs.

| No. | Business Question | Analysis Output |
|---|---|---|
| 1 | How do recorded sales quantities, Sales Amount and COGS differ across sales types? | Sales Performance by Sales Type |
| 2 | Which stores have the highest and lowest recorded Sales Amount? | Sales Performance by Store |
| 3 | Which 10 products recorded the highest Sales Amount? | Top 10 Products by Sales Amount |
| 4 | What are the latest recorded inventory observations for each store-product combination? | Latest Inventory Observation |

These outputs provide descriptive insights into sales performance and recorded inventory observations.

## Data Quality and Validation

The workflow includes:

- Text cleaning and standardization.
- Data-type assignment.
- Sales and inventory review flags.
- Schema validation.
- Data-type error checks.
- Combined validation reporting.

The current validation results show that all four schema and data-type checks passed.

These checks do not establish that every source value is accurate or that all business rules are satisfied.

## Key Project Limitations

- Sales Amount and COGS are reported as supplied. Their currency and accounting definitions have not been independently verified.
- Returns are included as negative values in the sales data.
- Latest inventory observations represent the latest recorded observations for each store-product combination, not verified current stock levels.
- Inventory interval semantics have not been independently confirmed.
- Supplier lead times, reorder points, and other information required for automated replenishment decisions are not established by the available data.
- The workbook's source paths may need to be configured on another computer.

## Testing

- Sales and Inventory source queries were refreshed successfully using the configured source files.
- An Inventory source-replacement test using modified data was successfully performed, and the original source file was subsequently restored.
- A changed-source replacement test was not completed for Sales.
- Schema and data-type validation checks passed for both datasets.

## Repository Contents

This repository presents selected project documentation and screenshots of completed outputs.

## Project Scope

This project demonstrates Excel-based data automation, data preparation, validation, and descriptive retail analysis.

It is not a real-time inventory monitoring system, automated replenishment system, or demand forecasting solution.

## Acknowledgement

Dataset: *Retail Transactions and Stocks Data*, Mendeley Data.

DOI: https://doi.org/10.17632/27x8mjm8k4.1
Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
