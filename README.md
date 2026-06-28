# Business Data Cleaning, Validation and Excel Reporting

## Problem Summary

This project focuses on cleaning and validating retail order-level sales data exported from multiple internal systems.

The raw dataset contained inconsistencies in text formatting, date formats, missing values, duplicate records, invalid discounts, and calculation mismatches.

The objective was to create an analysis-ready dataset along with quality reports and business summaries.

## Dataset Description

The dataset contains order-level retail sales transactions including:

* Customer information
* Product information
* Order details
* Sales and cost information
* Payment and order status

## Tools Used

* Microsoft Excel
* Pivot Tables
* Excel Functions
* Conditional Formatting

## Cleaning Steps Performed

* Text standardization
* Missing value handling
* Date validation
* Duplicate detection
* Business rule validation
* Sales and profit recalculation

## Business Rules Applied

* Missing Region and Ship Mode replaced with Unknown.
* Invalid discounts flagged.
* Cancelled and failed payment orders excluded from completed sales summaries.
* Refunded orders summarized separately.

## Data Quality Issues Found

* Duplicate order IDs
* Missing values
* Date inconsistencies
* Discount issues

## Pivot Reports Created

* Sales and Profit by Region
* Sales and Profit by Category and Sub Category
* Order Count by Ship Mode
* Profit Margin by Customer Segment
* Refunded, Cancelled and Failed Orders by Region
* Monthly Sales Trend

## Key Business Insights

* Regional sales distribution varies significantly.
* Technology and Office Supplies contributed strongly to revenue.
* Standard shipping modes account for the majority of orders.
* Profit margins vary across customer segments.

## Assumptions

* Maximum valid discount set at 50%.
* Missing discounts treated as zero when appropriate.

## Limitations

* Duplicate order IDs require manual investigation.

## Screenshots Included

* Raw dataset preview
* Cleaned dataset preview
* Pivot summary screenshots

