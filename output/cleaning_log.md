# Cleaning Log

## Issues Found

* Inconsistent text formatting in customer, location, and category fields.
* Multiple date formats found in order_date and ship_date columns.
* Duplicate order IDs identified.
* Missing values detected in some fields.
* Invalid discount values identified.
* Shipping date inconsistencies identified.
* Sales and profit mismatches checked.

## Cleaning Actions Performed

* Applied TRIM() to remove leading and trailing spaces.
* Applied PROPER() to standardize text capitalization.
* Standardized category and location names.
* Created cleaned versions of text columns.
* Standardized discount values.
* Created calculated sales and profit columns.
* Generated shipping delay calculation.
* Added duplicate record identification.
* Added data quality flag classification.

## Business Rules Applied

* Missing Region values replaced with "Unknown".
* Missing Ship Mode values replaced with "Unknown".
* Missing Discount values treated as 0 where appropriate.
* Discounts below 0 flagged as invalid.
* Discounts above 50% flagged as invalid.
* Cancelled orders excluded from completed sales analysis.
* Failed payment orders excluded from completed sales analysis.
* Refunded orders tracked separately.
* Shipping dates earlier than order dates flagged as invalid.

## Assumptions Made

* Maximum valid discount value is 50%.
* Missing discount values can be treated as 0 when other sales information is available.
* Duplicate order IDs require manual review rather than automatic deletion.

## Records Removed

* Exact duplicate rows removed: 0

## Records Flagged

* Duplicate order IDs were flagged for manual review.
* Invalid discounts were flagged.
* Invalid shipping records were flagged.

## Limitations

* Conflicting duplicate records require business review.
* Some date inconsistencies may require manual validation.

