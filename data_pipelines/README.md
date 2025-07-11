# Data Pipelines Overview

This folder contains the code and documentation for data ingestion pipelines.

## Python Scripts

- [SFTP to GCS](./sftp_to_gcs): Fetches daily CSV reports from an SFTP server and uploads to Google Cloud Storage (GCS)
- [SFTP to GCS All Files](./sftp_to_gcs_all): Adhoc function to fetch all files from an SFTP server to GCS

## Native Transfers

- GA4
- GoogleAds
- Google Search Console
- REC Reports (Internal BI) - Google Storage to BigQuery
- Meta Ads
- [Fiscal Calendars](./native_documenation/GCS_fiscal_calendar.md): - Google Storage to BigQuery
