# Data Visualization Best Practices Guide
## Week 6 | Hashclick Solutions LLC | Narendra Ogety

## 1. Clear Layout Principles

### The F-Pattern Rule
Users read dashboards in an F-pattern (top-left to right, then down-left). Place the most important KPIs in the top-left.

### Layout Hierarchy
```
[  KPI Card 1  ] [  KPI Card 2  ] [  KPI Card 3  ] [  KPI Card 4  ]
[        Trend Line Chart (Revenue Over Time)                      ]
[ Regional Map         ] [  Category Donut  ] [ Top Products Bar   ]
```

### Key Layout Rules
- One insight per visual
- No more than 5-7 visuals per page
- Group related visuals together
- Use whitespace to separate sections
- Place filters/slicers at top or left

## 2. Proper Chart Selection Guide

| Data Story | Best Chart Type | Avoid |
|-----------|----------------|-------|
| Compare categories | Bar / Column Chart | 3D charts |
| Show trend over time | Line Chart | Bar chart for time |
| Part-to-whole (<=5 parts) | Donut / Pie Chart | Pie with many slices |
| Correlation between variables | Scatter Plot | Line chart |
| Single important number | KPI Card | Table |
| Geographic distribution | Map / Filled Map | Bar chart for geo |
| Ranking | Horizontal Bar Chart | Pie chart |
| Distribution | Histogram / Box Plot | Line chart |

## 3. Consistent Formatting Standards

### Fonts
- Use ONE font family throughout (Segoe UI recommended)
- Title: Bold, 16-18px
- Subtitle: Regular, 12-14px
- Data labels: Regular, 10-11px
- Never use more than 2 font sizes per visual

### Colors
- Use a maximum of 4-5 colors per dashboard
- Maintain semantic color meaning (green=good, red=alert)
- Ensure sufficient contrast ratio (WCAG AA: 4.5:1)
- Never use rainbow/gradient colors for categorical data

### Alignment & Spacing
- Align all visuals to a grid
- Consistent margins: 8px or 16px
- Equal spacing between cards
- Avoid overlapping elements

### Data Labels
- Show labels only when they add value
- Format numbers consistently: $1.2M not $1,234,567
- Use K/M/B suffixes for large numbers
- Round to 1-2 decimal places maximum

## 4. Data Storytelling Principles

### The WHAT-SO WHAT-NOW WHAT Framework
1. **WHAT:** What does the data show? (Facts)
2. **SO WHAT:** Why does it matter? (Context/Impact)
3. **NOW WHAT:** What action should be taken? (Recommendation)

### Annotation Best Practices
- Add reference lines for targets/benchmarks
- Label significant data points (peaks, drops)
- Use text boxes to explain anomalies
- Include data source and last refresh time

### Dashboard Anti-Patterns to Avoid
- Chartjunk: Unnecessary decorations
- Dual Y-axis confusion
- Truncated Y-axis (misleading scale)
- Too many colors
- Pie charts with more than 5 slices
- 3D charts (distort perception)

## 5. Performance Best Practices
- Limit visuals to what fits one screen
- Use aggregated data at report level
- Filter data at source (query level)
- Avoid calculated columns when measures work
- Use import mode for static data, DirectQuery for live

---
*Narendra Ogety | Data Analyst | Hashclick Solutions LLC | Week 6*
