# Sports Product Assortment Dashboard

**Author:** Cameron Batts

## Problem
Show how reported product counts are distributed across categories and product lines.

## Dashboard design and review
Review the product-line donut chart, category ranking and product-group treemap, preserving the meaning of the displayed Number of Products measure.

## Findings
The dashboard displays a rounded 3.2K product total. Clothes is the largest displayed category with 884 products, followed by Assorted Sports Articles with 465, Children Sports with 413 and Shoes with 330. The twelve displayed category counts sum to 3,151, consistent with the rounded headline. These figures describe the exported product-count view.

## Limitations
Product counts are not units sold, revenue, available stock or inventory turnover. The source table and native SAS report definition are absent, so distinct-count logic, filters and aggregation rules cannot be verified. A static export does not demonstrate a live drill-through or pop-up interaction. No operational outcome or improved inventory allocation was measured. Dataset provenance is not recorded in the supplied export; previous claims of real operational data were unsupported.

## Data and provenance
The repository contains a dashboard image and PDF, with no raw product table. The exported product-line labels are Children, Clothes & Shoes, Outdoors and Sports. The analysis retains factual category and product labels.

## Verification
Displayed category counts and the rounded KPI were checked against the PDF and a rendered page. The twelve visible category values were summed independently. No underlying SAS dataset was recomputed.

## Reading the dashboard
The donut chart summarizes four product lines, the ranked bars compare twelve categories, and the treemap shows finer product-group composition. The report is a static portfolio case study of that design.

## View the project
- [Analysis report](Reports/sas_sports_product.html)
- [Portfolio analysis](https://cameron-batts.github.io/sas_sports_product.html)
- [Original export: Product_Analysis_on_Apr_25__2026.pdf](Reports/Product_Analysis_on_Apr_25__2026.pdf)

## Dashboard previews
![Product Analysis](Images/Product%20Analysis.png)
