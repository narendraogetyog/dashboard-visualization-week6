# Dashboard Design Specification
## Week 6 | Hashclick Solutions LLC | Narendra Ogety

## Dashboard Overview
**Dashboard Name:** Sales Performance Dashboard - Enhanced v2.0
**Tool:** Power BI / Tableau
**Data Source:** Sales transactions dataset (Q1-Q2 2026)
**Refresh Frequency:** Daily

## Layout Structure

### Section 1: Executive KPI Summary (Top Row)
| KPI Card | Metric | Target | Status |
|----------|--------|--------|--------|
| Total Revenue | $2.4M | $2.2M | Green |
| Total Orders | 8,450 | 8,000 | Green |
| Active Customers | 3,210 | 3,000 | Green |
| Gross Profit Margin | 42.3% | 40% | Green |
| Avg Order Value | $284 | $270 | Green |

### Section 2: Trend Analysis (Middle Row)
- Monthly Revenue Trend (Line Chart) - Jan to Jun 2026
- Order Volume by Month (Bar Chart)
- Customer Acquisition vs Churn (Dual-axis Line Chart)

### Section 3: Dimensional Breakdown (Bottom Row)
- Revenue by Region (Map Visual + Bar Chart)
- Revenue by Product Category (Donut Chart)
- Top 10 Products by Revenue (Horizontal Bar Chart)
- Customer Segment Analysis (Stacked Bar Chart)

## Color Theme
```
Primary Blue:    #0078D4  (Microsoft Blue)
Success Green:   #107C10
Alert Red:       #D83B01
Neutral Gray:    #8A8886
Background:      #F3F2F1
Text:            #323130
```

## Typography
- Title: Segoe UI Semibold, 18px
- Subtitle: Segoe UI Regular, 14px
- KPI Values: Segoe UI Bold, 28px
- Labels: Segoe UI Regular, 11px

## Spacing & Padding
- Card padding: 16px all sides
- Section gap: 12px
- Visual border radius: 4px
- Shadow: 0 2px 4px rgba(0,0,0,0.1)

## Interactive Elements
- Global date slicer (top-right corner)
- Region filter (dropdown)
- Product category filter (multi-select)
- Customer segment toggle
- Drill-through enabled on all visuals

## Accessibility
- Color-blind safe palette
- All charts have data labels
- Alt text on all visuals
- High contrast mode supported

---
*Narendra Ogety | Data Analyst | Hashclick Solutions LLC | Week 6*
