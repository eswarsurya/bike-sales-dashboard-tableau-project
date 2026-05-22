# Bike Sales Dashboard - Tableau

Tableau dashboard project focused on Indian bike sales performance, resale value, vehicle attributes, and business-friendly visual reporting.

## Why I Built This

Sales datasets can become difficult to understand when they include many product, pricing, location, and ownership fields. I built this dashboard to practise turning a raw sales table into a clear visual story for business users.

The project shows dashboard design, data preparation, visual comparison, and the ability to explain sales patterns without forcing the reader to inspect every row of data.

## Business Questions

- Which brands and states appear most often in the sales dataset?
- How do average price and resale price differ by brand, state, seller type, and owner type?
- What vehicle attributes, such as mileage and engine capacity, help explain bike sales and resale context?
- How can Tableau be used to make sales review easier for non-technical stakeholders?

## Dataset Context

The working dataset contains 10,000 bike sales records and 15 columns. It includes fields such as state, brand, model, price, year of manufacture, engine capacity, fuel type, mileage, owner type, seller type, resale price, and city tier.

The public GitHub version includes a smaller sample plus aggregate outputs so the project can be reviewed safely.

## Tools Used

- Tableau
- CSV data preparation
- Visual analytics
- Dashboard design
- Business reporting

## What I Implemented

- Reviewed the bike sales dataset and dashboard fields.
- Built a Tableau dashboard for sales and resale analysis.
- Prepared public-safe sample data for GitHub review.
- Exported summary outputs by brand, state, owner type, and seller type.
- Added visual summaries so reviewers can understand the dashboard logic without opening Tableau first.
- Documented the workbook status and public-sharing approach.

## Repository Guide

```text
data/
  README.md
  public_sample_bike_sales_india.csv

outputs/
  README.md
  dataset_profile.csv
  brand_summary.csv
  state_sales_summary.csv
  owner_type_summary.csv
  seller_type_summary.csv
  dashboard_output_summary.md

dashboards/
  README.md

reports/
  report_summary.md

assets/
  brand_records_summary.svg
  state_records_summary.svg
```

## Outputs And Results

The current public evidence shows:

- 10,000 sales records reviewed in the working dataset.
- 8 bike brands and 40 bike models represented.
- 10 Indian states included in the analysis.
- Average listed price: INR 224,328.72.
- Average resale price: INR 133,828.97.
- Dealer and individual seller groups are both represented almost evenly.

These outputs support the Tableau dashboard by giving a clear, public-safe view of the data behind the visuals.

## How To Review This Project

Start with the README, then review:

1. `data/README.md` for dataset context.
2. `outputs/dataset_profile.csv` for project scope.
3. `outputs/brand_summary.csv` and `outputs/state_sales_summary.csv` for dashboard-level insights.
4. `outputs/dashboard_output_summary.md` for the business explanation.
5. `assets/` for quick visual summaries.

## Public Sharing Note

The local project includes a Tableau packaged workbook and a PDF report. The workbook is not uploaded in this phase because Tableau files can include embedded data and should be checked carefully before publishing.

## Recruiter Notes

This project demonstrates dashboard design, sales analysis, Tableau reporting, and clear communication of business insights from structured data.
