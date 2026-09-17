# AWS Architecture

## Overview

The project implements a simple cloud analytics architecture using Amazon S3 and Amazon QuickSight.

## Architecture

```text
Amazon S3
    │
    │ CSV data
    ▼
QuickSight Data Source
    │
    ▼
QuickSight Dataset
    │
    ▼
QuickSight Analysis
    │
    ▼
QuickSight Dashboard
```

## Amazon S3

Amazon S3 provides object storage for the CSV dataset.

The CSV file is stored inside an S3 bucket and acts as the source of the analytics data.

## Amazon QuickSight

QuickSight is responsible for analyzing and visualizing the data.

The QuickSight workflow consists of:

1. Data Source
2. Dataset
3. Analysis
4. Dashboard

## Data Source

The QuickSight data source connects to the S3 CSV file.

## Dataset

The dataset represents the imported data and its fields.

QuickSight uses the dataset as the foundation for analysis.

## Analysis

The analysis is used to create charts, filters, tables, and other visualizations.

## Dashboard

The dashboard presents the final visualizations in an interactive format.

## Design Choice

S3 was selected as the storage layer because the project uses a CSV file and does not require a database for this simple analytics workflow.

QuickSight was selected because it provides cloud-based business intelligence and visualization capabilities.

