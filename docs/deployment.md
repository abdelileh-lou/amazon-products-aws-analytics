# Deployment Guide

## Prerequisites

The project requires:

* An AWS account
* An Amazon S3 bucket
* The CSV dataset
* Amazon QuickSight access

## Step 1: Create the S3 Bucket

An S3 bucket was created to store the project dataset.

The CSV file was uploaded to the bucket.

Example:

```text
S3 Bucket
└── Amazon-Bestseller-Dataset.csv
```

## Step 2: Configure QuickSight

Amazon QuickSight was opened and configured to access the S3 data.

The S3 data source was created using the appropriate S3 configuration.

## Step 3: Create the Dataset

A QuickSight dataset was created from the CSV file.

QuickSight reads the CSV structure and makes the fields available for analysis.

## Step 4: Create the Analysis

The dataset was used to create a QuickSight analysis.

Charts and visualizations were created based on the available data fields.

## Step 5: Create the Dashboard

The completed analysis was published as a QuickSight dashboard.

The dashboard provides an interactive view of the analyzed data.

## Screenshots

Screenshots of the deployment and configuration are stored in the `screenshots/` directory.

