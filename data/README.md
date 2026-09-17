# Dataset

## Overview

This project uses an Amazon products/book dataset in CSV format.

The dataset is stored in Amazon S3 and consumed by Amazon QuickSight for analytics and visualization.

## File

```text
Amazon-Bestseller-Dataset.csv
```

## Storage

The dataset is stored in an Amazon S3 bucket.

```text
s3://amznabdelileh-project/Amazon-Bestseller-Dataset.csv
```

## Format

The dataset uses:

* Format: CSV
* Delimiter: comma `,`
* Header row: Yes

## Usage

The CSV file is used as the source data for Amazon QuickSight.

The data is not processed by an application in this project. QuickSight reads the data from S3 and uses it to create a dataset for analysis.

## Data Privacy

No personal or confidential user data is intentionally used in this project.

