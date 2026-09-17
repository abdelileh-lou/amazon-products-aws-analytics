# Architecture Description

## Overview

The project uses a simple AWS analytics architecture based on Amazon S3 and Amazon QuickSight.

The architecture contains two main AWS services:

* Amazon S3
* Amazon QuickSight

## Data Flow

The data flows through the architecture in the following order:

```text
CSV Dataset
    ↓
Amazon S3
    ↓
QuickSight Data Source
    ↓
QuickSight Dataset
    ↓
QuickSight Analysis
    ↓
QuickSight Dashboard
```

## Amazon S3

Amazon S3 is used as the storage layer for the CSV dataset.

The dataset is stored in an S3 bucket before it is consumed by QuickSight.

## Amazon QuickSight

Amazon QuickSight is used as the analytics and visualization service.

QuickSight connects to the data stored in S3 and creates a dataset from the CSV file.

The dataset is then used to create an analysis containing charts and visualizations.

The analysis can then be published as a dashboard.

## Architecture Components

### S3 Bucket

Stores the CSV data.

### QuickSight Data Source

Defines where QuickSight obtains the data.

### QuickSight Dataset

Represents the data that QuickSight uses for analysis.

### QuickSight Analysis

Used to create visualizations and explore the data.

### QuickSight Dashboard

Provides the final interactive visualization for users.

