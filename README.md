Loan Approval Data Automation Using Power Query
Project Overview

This project focuses on automating the ingestion, cleaning, and transformation of loan approval data using Advanced Excel and Power Query. The solution is designed to automatically merge multiple loan data files stored in a folder and prepare them for analysis and reporting.

Objective

To build a scalable folder-based data automation system that consolidates multiple loan datasets, applies structured data cleaning steps, and prepares the data for risk analysis and dashboard reporting.

Dataset Description

The dataset contains loan applicant information including credit score, income, employment details, loan amount, loan status, and other financial attributes. It is used to analyze applicant risk levels, approval patterns, and financial performance.

Automation Setup

All loan data files are stored inside a dedicated folder.

Power Query connects using the “From Folder” connector.

Multiple files are automatically combined into a single structured dataset.

Any new file added to the folder is included automatically upon refresh.

Data Cleaning Steps Performed

Corrected data types (Text, Whole Number, Decimal, Date).

Removed duplicate records.

Handled missing or null values.

Standardized column names.

Trimmed and cleaned text fields.

Removed irrelevant or blank rows.

Calculated Columns Created

Risk Category (based on credit score classification).

Approval Status indicator.

Income-to-Loan Ratio.

Month extracted from application date (if applicable).

Automation Validation

The automation process was validated by:

Adding a new loan data file to the folder.

Refreshing the query in Excel.

Confirming that new records were automatically appended without manual intervention.

Tools Used

Microsoft Excel

Power Query (Get Data – From Folder)

Power BI (for dashboard visualization, if applicable)

DAX for calculated fields

Outcome

The project successfully automates the consolidation and preparation of loan approval datasets. The system reduces manual processing effort, ensures data consistency, and supports efficient credit risk analysis and reporting.# Data_automation
