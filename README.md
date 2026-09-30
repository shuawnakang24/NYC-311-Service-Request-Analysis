# NYC 311 Service Request Analysis

A four-page Power BI report exploring NYC 311 requests created in June 2025. This project examines request volume, common problems, agency closure performance, and neighborhood hotspots.

## Tools and Skills

- Power BI Desktop
- DAX measures
- Interactive slicers and cross-filtering
- ZIP code drillthrough and back navigation
- KPI cards, bar charts, line charts, treemaps, and tables

## Report Pages

### 1. Service Overview
Displays total requests, closed requests, closure rate, and median hours to close. Includes the top 10 problems, borough comparisons, daily request trends, and an agency filter.

### 2. Response Performance
Compares closure rates and median closure times for agencies with at least 100 requests. Selecting an agency's bar filters the comparison table.

### 3. Neighborhood Hotspots
Explores request volume by borough and ZIP code through a borough slicer, a top 10 ZIP code chart, and a treemap.

### 4. ZIP Detail
Provides request counts, median closure time, and problem types for a selected ZIP code.

## Key Findings

- The overview contains approximately 295,500 requests.
- The recorded closure rate is 98.83%.
- The overall median closure time is 3.45 hours.
- Illegal parking is the most common problem in the overview.
- Brooklyn has the highest request volume among boroughs.
- Parks and Recreation has a recorded closure rate of 85.70%, the lowest among the agencies displayed.

## Metric Definitions and Limitations

- Closure rates reflect the available dataset, including closures after June 2025.
- Median closure time is calculated from Created Date to Closed Date, using records with a nonblank closed date on or after creation.
- Agency workloads and request types differ, so closure metrics alone do not establish service quality.
- The agency comparison excludes agencies with fewer than 100 requests.
- The PDF is a static preview. Interactive filtering and drillthrough require the Power BI report.

## How to Explore

1. Open the `.pbix` file in Power BI Desktop.
2. Use the agency and borough slicers to filter the report.
3. On Neighborhood Hotspots, right-click a ZIP code bar.
4. Select **Drill through → ZIP Detail**.
5. Use the back arrow to return. In Desktop editing mode, hold Ctrl while clicking the arrow.

## Author

Shuawna Kang  
Bachelor's in Data Analytics | Power BI Portfolio Project
