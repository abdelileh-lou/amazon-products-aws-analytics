# AWS Cost

## Overview

This project uses AWS services that may generate charges depending on usage and account configuration.

The main services used are:

* Amazon S3
* Amazon QuickSight

## Amazon S3

S3 costs can be associated with storage and requests.

For a small CSV dataset and a learning project, the amount of stored data is expected to be small.

## Amazon QuickSight

QuickSight pricing depends on the account type, features, users, and usage.

The actual cost should be checked in the AWS Billing console because pricing and usage can vary.

## Cost Management

To avoid unexpected charges:

* Monitor AWS Billing.
* Delete unused resources.
* Avoid unnecessary QuickSight resources.
* Remove the S3 bucket and objects when the project is no longer needed, if they are not required.

## Important

AWS pricing can change over time. This document intentionally does not hard-code a specific price.

