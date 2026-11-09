# Automated Inventory Audit & Discrepancy Dashboard (Excel / Power Query)

## Executive Summary
An operational auditing dashboard developed in Microsoft Excel and Power Query to track inventory accuracy, identify variance root-causes, and quantify monetary shrink risk across warehouse zones.

## Features & Implementation
- **Power Query Automation:** Cleaned raw cycle-count data, updated schema formatting, and applied conditional logic to flag high-risk variance items ($200+ shrink threshold).
- **Advanced Excel Modeling:** Used nested `IF`, `ABS()`, and percentage variance formulas to evaluate cycle count accuracy across 30 SKU categories.
- **Dynamic Dashboard UI:** Built interactive PivotCharts connected via global Slicers to allow real-time filtering by Warehouse Zone and Risk Category.

## Key Insights
- **Net Inventory Accuracy Rate:** 97.8% across audited locations.
- **Top Risk Area:** Zone C accounted for the largest dollar variance, driven by high-cost items like Fuel Pump Modules and Water Pump Assemblies.
