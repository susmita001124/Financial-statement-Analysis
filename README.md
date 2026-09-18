# Financial Statement Analysis

A financial statement review and ratio analysis project based on the source workbook: `Financial Statement Analysis.xlsx`.

## Overview

This project evaluates the financial performance of Square Pharmaceuticals and Ibn Sina Pharmaceuticals for FY2023 and FY2024 using the figures contained in the workbook. The analysis focuses on internal consistency across the raw data, calculation sheets, and key financial ratios used to compare company performance.

## View in Browser

Click the button below to open the dashboard:

[Open Dashboard](index.html)

This project includes a browser-based dashboard to present the analysis in a user-friendly format. To view it manually:

1. Open the project folder.
2. Double-click `index.html` or open it in a browser.
3. Use the interactive dashboard to explore financial ratios, filter by category, and review company comparisons.

The dashboard is designed to be viewed directly in a browser without any installation or server setup. It allows the user to navigate the ratio analysis visually and understand the results without opening the Excel file.

## Objective

The main goal is to review whether the reported financial ratios are computed correctly from the underlying data and whether the balance sheet relationships are internally consistent. The review also identifies material discrepancies between the workbook’s calculated values and the recomputed values.

## Data Source

The analysis is based on the workbook file:

- `Financial Statement Analysis.xlsx`

The workbook contains the raw financial figures and the ratio calculations used for comparison.

## Companies Covered

- Square Pharmaceuticals
- Ibn Sina Pharmaceuticals

## Period Covered

- FY2023
- FY2024

## Scope of Review

The review covers a set of core financial ratios across major categories, including:

- Liquidity
- Profitability
- Leverage
- Efficiency
- Returns

The work includes:

- Recomputing ratios directly from raw figures
- Comparing recomputed values to workbook formulas
- Checking balance sheet identities
- Highlighting discrepancies and explaining the source of any mismatch

## Key Findings

The review found that the vast majority of the ratios were internally consistent:

- 11 of 12 ratios matched exactly after recomputation
- 1 ratio was identified as incorrect: Square Pharmaceuticals FY2023 net profit margin
- The discrepancy arose because the workbook used profit before tax instead of net profit in the formula

This indicates that the overall financial structure and calculations are largely reliable, with one notable formula issue requiring correction.

## Methodology

The review was performed by:

1. Extracting the raw financial values from the source data sheet
2. Recalculating the ratios independently
3. Comparing the results against the workbook’s ratio calculation sheet
4. Checking whether accounting identities remain valid for each company-year
5. Recording any inconsistencies and corrections needed

## Verification Summary

The project verifies internal consistency using the workbook data rather than external audited annual reports. The objective was to confirm that the workbook calculations align with the underlying raw numbers and standard financial formula logic.

## Limitations

This review is limited to internal consistency checks. It does not verify the raw figures against the companies’ published annual reports or audited financial statements.

## Project Structure

This repository is centered around the financial statement review and the workbook used to generate the analysis. The project is intended to provide a clear summary of the review, methodology, and conclusions.

## Recommendation

The main correction needed is to revise the formula for Square Pharmaceuticals FY2023 net profit margin so it uses net profit instead of profit before tax. After that, the workbook’s ratio section should be refreshed to reflect the corrected value.

## Notes

- The source workbook was not modified during the review
- The project is intended as a financial analysis and validation exercise
- Results are based on the workbook data supplied in the project

## Conclusion

This project provides a structured review of the financial statement analysis for two pharmaceutical companies over two fiscal years. It confirms that the overall dataset is largely consistent while identifying one formula-level issue that should be corrected for accuracy.
