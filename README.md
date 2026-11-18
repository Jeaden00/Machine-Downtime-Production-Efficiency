# Machine Downtime & Production Efficiency Analysis

### Microsoft Power BI \| Data Analytics Capstone Project

An interactive Power BI dashboard designed to analyze manufacturing
production performance, monitor machine downtime, identify major
downtime contributors, and support data-driven operational improvement.

------------------------------------------------------------------------

## 1. Project Overview

This project focuses on analyzing manufacturing production time and
machine downtime using Microsoft Power BI.

The dashboard consolidates production and downtime records into an
interactive reporting platform to evaluate production time efficiency,
identify recurring downtime factors, and analyze performance patterns
across production dates, products, flavors, and operators.

Through KPI monitoring, trend analysis, category comparisons, and Pareto
analysis, the project provides operational insights that can help
management prioritize improvement opportunities and strengthen
manufacturing performance.

## 2. Business Objectives

-   Monitor overall production performance through key performance
    indicators (KPIs).
-   Measure production time efficiency and track daily performance
    variations.
-   Identify and prioritize major machine downtime contributors.
-   Analyze downtime distribution across products, flavors, and
    operators.
-   Apply Pareto analysis to identify the most significant downtime
    categories.
-   Provide interactive filtering to support focused analysis and
    decision-making.

## 3. Tools and Technologies

  -----------------------------------------------------------------------
  Tool                                Application
  ----------------------------------- -----------------------------------
  Microsoft Power BI Desktop          Dashboard development and data
                                      visualization

  Power Query                         Data preparation and transformation

  DAX                                 KPI calculations and analytical
                                      measures

  Data Modeling                       Relationships between production
                                      and downtime tables

  Microsoft Excel                     Source data preparation
  -----------------------------------------------------------------------

## 4. Dataset and Data Model

The project uses manufacturing production and downtime datasets
organized into related tables.

**Key data tables:**

-   `dLineProductivity` -- Production batch time and minimum batch-time
    information.
-   `fLineDowntime` -- Recorded downtime duration in minutes.
-   `dDowntimeFactors` -- Downtime descriptions used for Pareto
    analysis.
-   Product and other dimension tables -- Supporting product, flavor,
    size, operator, and attribute analysis.

The data model supports KPI calculations, category comparisons,
interactive filtering, and Pareto analysis.

## 5. Dashboard Features

The interactive dashboard includes:

-   **KPI Cards:** Total Production Time, Total Minimum Batch Time,
    Total Downtime, and Production Time Efficiency.
-   **Production Time Efficiency Trend:** Monitors daily production
    efficiency.
-   **Downtime Trend:** Highlights daily downtime variations.
-   **Downtime by Product:** Compares recorded downtime across product
    categories.
-   **Downtime by Flavor:** Identifies downtime distribution by flavor.
-   **Downtime by Operator:** Displays recorded downtime by operator.
-   **Downtime Pareto Analysis:** Identifies leading contributors to
    downtime using cumulative percentage analysis and an 80% reference
    line.
-   **Operator Error Classification:** Displays the recorded Yes/No
    operator-error classification.

**Interactive filters:** - Operator - Product - Flavor - Size - Downtime
by Attribute

## 6. Key Performance Indicators (KPIs)

  Performance Indicator          Dashboard Result
  ---------------------------- ------------------
  Total Production Time             3,858 minutes
  Total Minimum Batch Time          2,470 minutes
  Total Downtime                    1,388 minutes
  Production Time Efficiency               64.02%

**Production Time Efficiency Formula:**

`Production Time Efficiency = Total Minimum Batch Time / Total Production Time`

`= 2,470 / 3,858 = 64.02%`

This is the project's defined production efficiency measure and should
not be interpreted as Overall Equipment Effectiveness (OEE).

## 7. Key Findings and Business Insights

### 7.1 Major Downtime Contributors

The Pareto analysis identified five leading downtime categories:

  Downtime Category        Minutes
  -------------------- -----------
  Machine Adjustment           332
  Machine Failure              254
  Inventory Shortage           225
  Batch Change                 160
  Batch Coding Error           145
  **Combined Total**     **1,116**

The five leading categories account for approximately **80.4% of
recorded downtime**, highlighting priority areas for further
investigation.

### 7.2 Production Performance

-   Production time efficiency ranged from 61.75% to 75.38% across the
    five displayed production dates.
-   The highest recorded daily downtime was 503 minutes on September 2,
    2024.
-   CO-600 recorded the highest absolute product downtime at 494
    minutes.
-   Cola recorded the highest absolute flavor downtime at 771 minutes.
-   The operator-error classification showed 55.91% Yes and 44.09% No.

These observations identify areas for further investigation; they do not
independently establish root causes or individual responsibility.

## 8. Recommended Improvement Opportunities

1.  Investigate the five leading downtime contributors using structured
    root-cause analysis, including 5 Whys and Fishbone Analysis.
2.  Strengthen equipment reliability through preventive maintenance and
    failure recurrence monitoring.
3.  Improve material readiness and standardize changeover activities.
4.  Conduct an event-level investigation of the September 2, 2024
    downtime peak.
5.  Normalize product and flavor downtime using production hours, batch
    counts, or output.
6.  Validate operator-error classifications before implementing
    corrective actions.

## 9. Project Deliverables

The repository contains the following project materials:

-   **Dashboard:** Power BI Desktop (`.pbix`) interactive dashboard.
-   **Reports:** Detailed technical project report and executive summary
    in PDF format.
-   **Screenshots:** Dashboard overview for portfolio presentation.
-   **README:** Project documentation, methodology, and key business
    insights.

## 10. Project Outcome

Developed an interactive Power BI dashboard that transforms
manufacturing production and downtime records into meaningful
operational insights.

The project demonstrates practical capabilities in data preparation,
data modeling, DAX measure development, KPI monitoring, trend analysis,
Pareto analysis, and business intelligence reporting.

It also demonstrates the ability to translate analytical findings into
management-level insights and actionable continuous improvement
recommendations.

------------------------------------------------------------------------

**Project:** Machine Downtime & Production Efficiency Analysis\
**Platform:** Microsoft Power BI\
**Project Type:** Data Analytics Capstone Project\
**Author:** Jeaden C. Lagleva

*Note: The analysis covers five displayed production dates from August
29 to September 3, 2024, with September 1 not shown in the dashboard
trend. Findings are limited to the supplied dataset and reporting
context.*
