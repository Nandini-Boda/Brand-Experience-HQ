# Dashboard Architecture
## Hospitality Weekly Insight Hub

### 1. Overview

Hospitality Weekly Insight Hub is a centralized hospitality business intelligence dashboard developed to present business performance and operational information through an interactive reporting experience.

The dashboard is developed using Lovable, with Google BigQuery serving as the reporting data warehouse.

Its design brings five business reporting areas together:

1. Revenue
2. Brand
3. People
4. Property
5. Executive Review

### 2. High-Level Architecture

The solution follows a simple reporting flow:

**Reporting Data Sources → Google BigQuery → Dashboard Data Integration → Interactive Dashboard → Business Insights**

- **Reporting Data:** Hospitality business information organized into reporting datasets.
- **Data Warehouse:** Google BigQuery provides the centralized reporting data.
- **Dashboard Integration:** The dashboard accesses reporting data through its configured integration.
- **Presentation Layer:** Lovable provides the interactive dashboard interface.
- **Business Insights:** Users explore performance indicators, trends and operational information through the dashboard.

### 3. Dashboard Structure

| Dashboard Section | Business Purpose |
|---|---|
| Revenue | Monitor sales, revenue performance, targets and upselling |
| Brand | Review guest ratings, reviews and brand performance |
| People | Monitor workforce information and training attendance |
| Property | Review property-level operational indicators and guest complaints |
| Executive Review | Present management discussion points and follow-up items |

### 4. Data Integration

Google BigQuery is used as the reporting data warehouse for the dashboard.

The reporting solution was updated to use BigQuery-based demonstration tables in place of the previous Google Sheets reporting dependencies.

This provides a centralized reporting foundation for the dashboard's business areas.

### 5. Reporting Experience

The dashboard is organized around business functions rather than individual data sources.

This allows users to explore different reporting perspectives through a consistent interface while keeping related business information organized.

### 6. Architecture Scope

This document describes the dashboard architecture at a business and solution level.

It intentionally excludes private project identifiers, actual internal table names, credentials, confidential infrastructure details and sensitive business information.

