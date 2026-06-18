# DecodeLabs Internship Project 1 - Data Quality Audit

Completed a Verification Gate Audit on a transactions dataset as part of the DecodeLabs internship.

## Objective
Identify and resolve 6 critical data quality issues to achieve 0% error rates before analysis.

## Key Changes Implemented
1. **Missing Data**: Imputed 'CouponCode' with 'NO_COUPON' to preserve rows from deletion
2. **Numerical Imputation**: Used column median to fill gaps without outlier bias
3. **Deduplication**: Removed duplicates via OrderID → 0% duplicate error rate
4. **Text Standardization**: Applied .str.strip and title casing to fix spacing issues
5. **Date Formatting**: Converted all dates to ISO 8601 (YYYY-MM-DD) → 0% format errors
6. **Financial Precision**: Enforced 2-decimal rounding for all monetary values

## Skills Demonstrated
Python, pandas, data wrangling, ETL, audit documentation, data quality assurance

## Files
- `DecodeLabs-ChangeLog.pdf` - Official change log documenting all fixes and impact
