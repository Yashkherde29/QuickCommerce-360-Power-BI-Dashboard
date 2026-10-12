# QuickCommerce 360 — Power BI Dashboard

An interactive business intelligence dashboard comparing **Blinkit, Zepto, and Swiggy Instamart** using Power BI.

The project explores platform-specific sales performance, product pricing, discounts, ratings, and inventory availability through a consistent, brand-inspired dashboard design.

## Dashboard Preview

### 1. Executive Overview

The Executive Overview brings together key metrics and platform-specific visualizations.

![QuickCommerce 360 Executive Overview]

**Key features**
- Blinkit total sales and average rating.
- Swiggy Instamart total sales and average rating.
- Zepto average selling price and average discount.
- Sales analysis by product type and category.
- Interactive platform-specific slicers.
- Brand-inspired colors for clear visual identification.

### 2. Pricing & Inventory Analysis

This page focuses on Zepto's product pricing and availability.

![Pricing and Inventory Analysis]

**Key features**
- Average selling price.
- Average discount.
- Product availability analysis.
- Category-level pricing comparisons.
- Inventory-related metrics where supported by the dataset.

### 3. Sales & Outlet Analysis

This page explores sales patterns across Blinkit and Swiggy Instamart.

![Sales and Outlet Analysis]

**Key features**
- Blinkit sales by outlet type and location type.
- Instamart sales by shop type and city type.
- Sales by establishment or opening year where supported.
- Platform-specific comparisons and breakdowns.

## Project Objectives

- Build an interactive Power BI dashboard for quick-commerce analytics.
- Analyze sales patterns and product categories.
- Explore product pricing, discounts, and availability.
- Present key performance indicators through clear visualizations.
- Demonstrate data cleaning, data modeling, DAX, and dashboard design skills.

## Tools and Technologies

- **Microsoft Power BI Desktop** — dashboard development and visualization.
- **Power Query** — data cleaning and transformation.
- **DAX** — calculated measures and KPI calculations.
- **CSV and Excel** — source data formats.
- **GitHub** — project documentation and portfolio hosting.

## Data Sources and Structure

The project uses three separate datasets:

| Platform | Main analytical focus |
|---|---|
| Blinkit | Sales, ratings, item types, and outlet characteristics |
| Swiggy Instamart | Sales, ratings, categories, and shop characteristics |
| Zepto | Product pricing, discounts, categories, and availability |

The datasets have different structures and metric coverage. They are analyzed separately rather than being combined into a single fact table.

**Data note:** The Zepto selling-price column is converted from the source's apparent paise units into rupees by dividing by 100. This conversion should be interpreted according to the source dataset's unit conventions.

The dashboard uses platform-specific measures because the datasets do not provide directly comparable sales or revenue metrics for all three platforms.

## Key Metrics

### Blinkit
- Total Sales
- Average Rating
- Sales by Item Type
- Sales by Outlet Type
- Sales by Outlet Location Type

### Swiggy Instamart
- Total Sales
- Average Rating
- Sales by Category
- Sales by Shop Type
- Sales by Shop City Type

### Zepto
- Average Selling Price
- Average Discount
- Pricing by Category
- Product Availability
- Inventory-related metrics supported by the source data

## Interactivity

The report includes slicers that allow users to filter the corresponding platform's visuals by:
- Outlet location type for Blinkit.
- Shop city type for Instamart.
- Product category for Zepto.

Because the datasets are separate, each slicer filters the visuals associated with its respective platform.


## How to Use the Dashboard

1. Download or clone this repository.
2. Open `QuickCommerce 360.pbix` using Microsoft Power BI Desktop.
3. Allow the report to load.
4. Explore the report pages and use the slicers to interact with the visuals.

Power BI Desktop is required to interact with the PBIX report.

## Limitations

- The source datasets have different schemas, coverage, and analytical capabilities.
- Zepto's dataset does not provide the same sales metrics as the Blinkit and Instamart datasets.
- Sales values should not be interpreted as a directly comparable cross-platform market-share analysis.
- Results depend on the quality, coverage, and definitions of the source datasets.
- Dataset-specific assumptions, including price-unit conversion, should be verified against the original sources.

## Future Improvements

- Add more detailed pricing and inventory analysis.
- Improve cross-page navigation and visual interactions.
- Add time-based sales analysis where suitable date fields are available.
- Improve data validation and document source dataset provenance.
- Expand the dashboard with additional verified analytical metrics.

## Author

**Data Analytics Portfolio Project**

Developed using Microsoft Power BI, Power Query, and DAX.

## Disclaimer

This project is intended for educational and portfolio purposes. Blinkit, Zepto, and Swiggy Instamart are respective brand names of their owners. This project is not affiliated with or endorsed by these companies.

Dataset ownership and redistribution permissions remain with the respective data providers. Please review the applicable dataset licenses before redistributing source data.
