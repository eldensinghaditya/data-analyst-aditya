3-1-1 Inquiry Volume Analysis Portfolio

AWS Cloud Foundations Badge: Credly Badge Link
 Table of Contents

    Exploratory Data Analysis

    Descriptive Analysis

    Diagnostic Analysis

    Data Wrangling

    Data Quality Control

    Data Governance

    Data Security

 Exploratory Data Analysis

Project Title: Inquiry Volume Analysis with AWS Services
 Dataset: 3-1-1 Inquiry Volume Dataset stored in Amazon S3
🔹 Objective

Leverage AWS Glue Data Catalog and AWS Glue DataBrew to explore and profile public inquiry data.
🔹 Key Steps

    Identified missing values and inconsistent delimiters using AWS Glue DataBrew

    Ensured correct data types for Date, InquiryType, and VolumeCount

    Used Amazon Athena for SQL-based querying to uncover patterns

🔹 Tools & Technologies

Amazon S3, AWS Glue DataBrew, Amazon Athena
🔹 Deliverables

    Cleaned dataset in S3 (spreadsheet format)

    Summary reports with key insights on inquiry trends

Descriptive Analysis

Project Title: Understanding 3-1-1 Inquiry Patterns
🔹 Objective

Perform descriptive statistical analysis to examine type, frequency, and neighborhood-level trends.
🔹 Dataset

    Inquiry Type, Date, Neighborhood, Volume Count

    Stored in Amazon S3, queried using Athena

🔹 Methodology

    SQL-based aggregation using Amazon Athena

    Visualization via Matplotlib and Power BI

    Identified high-frequency and rare inquiry types

🔹 Tools & Technologies

Amazon S3, Amazon Athena, Matplotlib, Power BI
🔹 Deliverables

Descriptive reports with trend lines, seasonal patterns, and anomalies
 Diagnostic Analysis

Project Title: Investigating Unusual Inquiry Patterns
🔹 Objective

Identify causes of unusual spikes or drops in inquiry volume.
🔹 Dataset

    Stored in Amazon S3, analyzed via Amazon Athena

🔹 Methodology

    Comparative analysis of different time periods

    Correlation analysis of inquiry types and volume

    Outlier detection and root cause analysis

🔹 Tools & Technologies

Amazon S3, Amazon Athena, Power BI, Matplotlib
🔹 Deliverables

Diagnostic Analysis Report identifying anomalies and potential causes
 Data Wrangling

Project Title: Data Wrangling for Enhanced Inquiry Analysis
🔹 Objective

Clean, transform, and standardize the dataset for accurate and meaningful analysis.
🔹 Methodology

    Data Profiling: Used AWS Glue DataBrew to detect issues

    Data Cleaning: Removed duplicates, handled missing values, standardized formats

    Data Transformation: Normalized values, aggregated by category and time

    Data Consolidation: Saved cleaned data back to S3 for analysis

🔹 Tools & Technologies

Amazon S3, AWS Glue DataBrew
🔹 Deliverables

    Cleaned dataset ready for analysis

    Data Wrangling Report documenting the transformation pipeline

 Data Quality Control
🔹 Objective

Ensure data completeness, accuracy, and reliability throughout the analysis pipeline.
🔹 Methodology

    Profiling: Identified issues using AWS Glue DataBrew

    Cleansing: Handled nulls, duplicates, and data types

    Validation: Implemented automated rules and checks

    Reporting: Documented all cleaning steps and generated exception reports

🔹 Tools & Technologies

AWS Glue DataBrew, Amazon S3
🔹 Deliverables

Data Quality Control Report detailing profiling, cleaning, and validation efforts
 Data Governance
🔹 Objective

Design a framework for structured metadata management and secure access to datasets.
🔹 Methodology

    Metadata Management: Built a centralized metadata repository using AWS Glue Data Catalog

    Access Control: Enforced IAM policies and role-based permissions

    Consistency: Standardized naming conventions and applied dataset versioning

    Discovery: Used Glue Data Catalog for dataset search and integration

🔹 Tools & Technologies

AWS Glue Data Catalog, Amazon S3, IAM
🔹 Deliverables

Governance Documentation outlining metadata structure, access policies, and consistency rules
 Data Security

Project Title: Data Security for 311 Inquiry Volume Dataset
🔹 Objective

Secure the data pipeline from ingestion to analysis against unauthorized access and threats.
🔹 Methodology

    Encryption: Used AWS KMS and SSE for S3 bucket encryption

    Access Control: Applied IAM roles, S3 policies, and ACLs

    Integrity: Enabled versioning, logging via AWS CloudTrail

    Monitoring: Deployed AWS CloudWatch and SNS for alerts on suspicious activities

    Compliance: Documented policies and adhered to AWS best practices

🔹 Tools & Technologies

Amazon S3, AWS KMS, IAM, CloudTrail, CloudWatch, SNS
🔹 Deliverables

Security Report detailing encryption, access controls, monitoring systems, and compliance
