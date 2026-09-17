# Security

## Overview

Security is an important part of the AWS architecture.

This project uses Amazon S3 and Amazon QuickSight, so access to the data must be controlled using AWS permissions.

## S3 Access

The S3 bucket should not be publicly accessible unless public access is specifically required.

S3 Block Public Access should remain enabled for this project.

## IAM Permissions

AWS Identity and Access Management (IAM) is used to control access to AWS resources.

Permissions should follow the principle of least privilege.

Users and services should receive only the permissions required to perform their tasks.

## QuickSight Access

QuickSight requires permission to access the S3 data source.

The required AWS permissions should be configured without granting unnecessary access to other AWS resources.

## Sensitive Information

The repository should not contain:

* AWS access keys
* Secret keys
* Passwords
* API keys
* Private credentials
* Sensitive AWS configuration

Only documentation, screenshots, architecture diagrams, and non-sensitive project information should be committed to GitHub.

