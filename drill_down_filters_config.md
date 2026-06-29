# Drill-Down & Filters Configuration
## Week 6 | Hashclick Solutions LLC | Narendra Ogety

## Overview
This document details all interactive filter and drill-down configurations applied to the Week 6 Sales Performance Dashboard.

## 1. Global Slicers / Filters

### Date Range Slicer
- **Type:** Between (date picker)
- **Default:** Last 30 days
- **Affects:** All visuals on the page
- **Placement:** Top-right corner

### Region Filter
- **Type:** Dropdown single-select
- **Options:** All | North | South | East | West | International
- **Default:** All

### Product Category Filter
- **Type:** Multi-select checklist
- **Options:** Electronics | Clothing | Home & Garden | Sports | Books | Other
- **Default:** All selected

### Customer Segment Toggle
- **Type:** Button slicer
- **Options:** All Customers | Enterprise | SMB | Individual
- **Default:** All Customers

## 2. Drill-Down Hierarchies

### Date Hierarchy
```
Level 1: Year (2024, 2025, 2026)
  Level 2: Quarter (Q1, Q2, Q3, Q4)
    Level 3: Month (Jan, Feb, Mar...)
      Level 4: Week (Week 1, Week 2...)
        Level 5: Day
```
**Applied to:** Revenue Trend Line Chart, Orders Bar Chart

### Geography Hierarchy
```
Level 1: Country (USA, Canada, Mexico)
  Level 2: Region (North, South, East, West)
    Level 3: State
      Level 4: City
```
**Applied to:** Regional Revenue Map, Regional Bar Chart

### Product Hierarchy
```
Level 1: Category (Electronics, Clothing...)
  Level 2: Sub-Category (Laptops, Phones...)
    Level 3: Brand
      Level 4: Product Name
```
**Applied to:** Category Donut Chart, Top Products Bar Chart

## 3. Cross-Filter Configuration

| Source Visual | Target Visual | Filter Type |
|--------------|---------------|-------------|
| Regional Map | Revenue Trend | Cross-highlight |
| Category Donut | Top Products | Cross-filter |
| Customer Segment Bar | KPI Cards | Cross-filter |
| Date Slicer | All Visuals | Global filter |
| Region Slicer | All Visuals | Global filter |

## 4. Drill-Through Pages

### Product Detail Page
- Triggered by: Right-click on any product in Top Products chart
- Shows: Product sales history, customer breakdown, regional performance
- Back button: Returns to main dashboard

### Customer Detail Page
- Triggered by: Right-click on customer segment
- Shows: Customer list, order history, lifetime value

### Regional Detail Page
- Triggered by: Click on map region
- Shows: State-level breakdown, top customers in region, YoY comparison

## 5. Tooltip Configuration

### Revenue Trend Tooltip
- Month: [Month Name]
- Revenue: $[Value]
- vs Prior Month: +/-[%]
- vs Target: +/-[%]

### Product Bar Tooltip
- Product: [Name]
- Revenue: $[Value]
- Units Sold: [Count]
- Avg Price: $[Value]
- Rank: #[Number]

## 6. Bookmarks

| Bookmark Name | Description |
|--------------|-------------|
| Default View | All filters reset, current month |
| Q2 2026 Summary | Q2 date range applied |
| Electronics Only | Category = Electronics |
| West Region | Region = West |
| Top Customers | Customer Segment = Enterprise |

---
*Narendra Ogety | Data Analyst | Hashclick Solutions LLC | Week 6*
