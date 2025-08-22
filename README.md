# prior-auth-automation
Insurance prior-authorization

This project automates tracking insurance prior authorization requests for patients. It reads new request data from CSV files, stores them in an SQLite database, and generates summary reports.

## Features

- Load new request data from CSV
- Store data in SQLite database (`prior_auth.db`)
- Append new requests or update existing ones by `request_id`
- Generate summary reports:
  - `status_report.csv`: Overall Approved / Denied / Pending counts
  - `insurance_status_report.csv`: Breakdown by insurance provider
- Ready for visualization in Tableau or Python

## Project Structure

