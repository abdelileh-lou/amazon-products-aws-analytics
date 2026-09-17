# Amazon Products AWS Analytics

## Overview

This project demonstrates a simple AWS cloud analytics architecture using Amazon S3 and Amazon QuickSight.

The project uses a CSV dataset containing Amazon product/book information. The dataset is stored in Amazon S3 and analyzed using Amazon QuickSight to create visualizations and an interactive dashboard.

## Architecture

```text
                    AWS CLOUD
                        │
                        ▼
                  ┌───────────┐
                  │    S3     │
                  │           │
                  │ products  │
                  │   .csv    │
                  └─────┬─────┘
                        │
                        ▼
                ┌───────────────┐
                │  QuickSight   │
                │               │
                │ Data Source   │
                │      ↓        │
                │ Dataset       │
                │      ↓        │
                │ Analysis      │
                │      ↓        │
                │ Dashboard     │
                └───────────────┘
```

## AWS Services

* Amazon S3
* Amazon QuickSight

## Project Flow

1. The CSV dataset is stored in an Amazon S3 bucket.
2. Amazon QuickSight connects to the S3 data.
3. A QuickSight dataset is created from the CSV file.
4. The dataset is used to create an analysis.
5. Visualizations are created in the analysis.
6. The analysis is published as an interactive dashboard.

## Repository Structure

```text
amazon-products-aws-analytics/
│
├── architecture/
│   ├── architecture.png
│   └── architecture-description.md
│
├── data/
│   └── README.md
│
├── docs/
│   ├── architecture.md
│   ├── deployment.md
│   ├── security.md
│   ├── testing.md
│   └── cost.md
│
├── screenshots/
│   ├── s3-bucket.png
│   ├── quicksight-dataset.png
│   ├── quicksight-analysis.png
│   └── dashboard.png
│
├── .gitignore
└── README.md
```

## Learning Objectives

This project was created to practice:

* AWS S3
* AWS IAM permissions
* Amazon QuickSight
* Cloud data analytics
* Data visualization
* AWS architecture documentation
* Basic cloud security
* AWS cost awareness

## Project Status

Completed as an AWS Cloud Analytics portfolio project.

