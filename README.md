# data-analyst-aditya



Table of Contents:

1.	Exploratory Data Analysis

2.	Descriptive Analysis

3.	Diagnostic Analysis

4.	Data Wrangling

5.	Data Quality Control

6.	Data Governance




Exploratory Data Analysis

Project Description:
3-1-1 Inquiry Volume Dataset stored in Amazon S3. The dataset records information about various public inquiries happened in different neighborhoods by numerous people and comprises of the type of inquiry reported, the neighborhood and also the date when the Inquiry took place.

Project Title: Inquiry Volume Analysis with AWS Services

Objective:
Use of AWS Glue Data Catalog access.

Data Profiling and Cleaning:
•	Here, inconsistences in our dataset (missing values, wrong delimiters) were found using AWS Glue DataBrew.
•	Ensured proper data type on fields such as Date, InquiryType and VolumeCount.

Data Summarization and Analysis:

•	To find key insights, I used Amazon Athena to perform SQL queries for extraction.
•	Principal analysis consisted of looking for high frequency inquiry types and neighborhood specific trending times.

Tools and Technologies:
Amazon S3, AWS Glue DataBrew, Amazon Athena

Deliverables:
•	The Amazon S3 lists Spreadsheet with cleaned and Structured Dataset in it.
•	Descriptive Analysis Reports that describe findings of inquiry patterns.

 











Descriptive Analysis

Project Description:
Descriptive Analysis of the 3-1-1 Inquiry Volume Data set to summarize main characteristics and generate whatever insights related to kind of type of inquiry, frequency and neighborhood sensible patterns.

Project Title: Understanding 3-1-1 Inquiry Patterns

Objective:
In order to perform descriptive statistical analysis of the Inquiry Volume dataset and gain knowledge about the dispersion of many types of inquiries, the frequency over the time span of them, and distinctions between neighborhoods.

Dataset:
•	3-1-1 Inquiry Volume CSV File
•	The fields are Inquiry Type, Date, Neighborhood, and Volume Count.
•	Amazon S3 the data is stored in it and we will be accessing it with the help of Amazon Athena for the analytical queries.

Methodology:
Data Analysis using SQL Queries:
The summary statistics were generated using Amazon Athena.

Queries focused on:
•	Inquiry Type distribution.
•	Neighborhood-wise inquiry counts.
•	Trends over time (e.g., monthly/seasonal variations).


Visualization of Inquiry Patterns:
•	Key insights were related to graphs and chart forms to illustrate.
•	The inquiry volumes were represented with bar charts and line graphs.
•	High Frequency and low Frequency Inquiry Type Identification.
•	Using the dataset to filter out and discover what types of inquires were most common from the parent.
•	Understanding rare inquiries, which can be a clue of unique problems.

Tools and Technologies:
Amazon S3, Amazon Athena, Visualization Tools (e.g., Matplotlib, Power BI)

Deliverables:
Descriptive Analysis Reports comprised of trend, distribution and point of anomaly.




Diagnostic Analysis

Project Description:
Analysis of potential causes of unusual inquiry patterns or significant changes in volume within the 3-1-1 Inquiry Volume Dataset. A process which can help aid in identifying the underlying causals for sudden spikes or drops in volume of an inquiry over time.

The Title of the Project: Investigating Unusual Inquiry Patterns.

Objective:
Find, describe and explain why there are such variations in the inquiry volume (unusual spikes or drops in the dataset). Knowing the reason(s) for the anomaly will give to this diagnostic analysis will help in understanding bug candidates and help us with making data driven decision.

Dataset:
•	311 Inquiry Volume CSV File
•	Inquiry Type, Date, Neighborhood and Volume Count are the fields.
•	Data stored and processed in Amazon S3, with query run through Amazon Athena.

Methodology:
Comparative Analysis:
•	Comparing different periods by using Amazon Athena.
•	Finding timeframes with more often active events than the general trend.

Correlation Analysis:
•	Determining which inquiry categories have a disproportionate impact on the total volume.
•	Anomaly detection by looking into the neighborhood specific trends.

Anomaly Detection:
•	Outliers that are much greater than the typical pattern.
•	Classification of abnormal behavior using statistical thresholds.

Root Cause Identification:
•	Deciding which of your anomalies are caused by some special event, data quality situation, or some external situation
•	Trend analysis and correlation with historical data to valid findings.

Tools and Technologies:
Amazon S3, Amazon Athena, Visualization Tools (e.g., Power BI, Matplotlib)

Deliverables:
An identified anomalies with potential causes – Diagnostic Analysis Report.


Data Wrangling

Project Description:
Data Washing for the 3-1-1 Inquiry Volume Dataset to sanitize data so that it may be examined by structured analysis having cleaned, transformed and standardized the dataset into a usable format.

Title: Data Wrangling for Enhanced Inquiry Analysis

Objective:
We transform, clean, and prepare the 311 Inquiry Volume Dataset for further analyzing. This process makes the data accurate, consistent and structured in the way that gives meaningful insights.

Dataset:
•	3-1-1 Inquiry Volume CSV File
•	It consists of the columns, Inquiry Type, Date, Neighborhood and Volume Count.
•	Accessed and processed in Amazon S3 using AWS Glue DataBrew.

Methodology:
Data Collection:
The dataset was ingested into an Amazon S3 and stored reliably and correctly in different ways.

Data Profiling:
•	In order to assess data quality, I review the column distributions, lookup for missing values, and examine the data types with AWS Glue DataBrew.
•	Found that of missing values, invalid delimiters and mismatched data types.

Data Cleaning:
•	Using some applied transformations based on AWS Glue DataBrew:
•	Replacing missing values.
•	Removing duplicates.
•	Renaming columns for consistency.
•	Handling data types (ex-changing them to a convenient format like date formatting).

Data Transformation:
•	Ensured consistent labeling of normalized inquiry types.
•	Summary of counts by date, type and neighborhood using aggregated data.

Data Consolidation:
Cleaned and transformed the dataset in Amazon S3 and stored back for further analysis on Amazon Athena.

Tools and Technologies:
Amazon S3, AWS Glue DataBrew

Deliverables:
•	Cleaned Dataset ready for analysis.
•	This is the Data Wrangling Report that documents the entire process.

 



Data Quality Control

Project Description:
This vacancy is to ensure data accuracy, consistency, and reliability across the data analysis pipeline for the 311 Inquiry Volume Dataset.

Objective:
Therefore, developing the overall data quality framework to address data integrity, completeness, accuracy, and integrity before analysis is performed.

Methodology:
1.	Data Profiling:
•	To examine the dataset structure to detect potential problems like missing values, bad type of data etc., it used AWS Glue DataBrew.
•	Data was generated for summary statistics to assess data completeness and unusual data.

2.	Data Cleansing:
•	Some of the applied data cleaning transformations using AWS Glue DataBrew like:
•	To remove null values or were replaced by suitable defaults.
•	Eliminating duplicate entries.
•	Data types were made correct and formats were standardized.

3.	Validation Rules and Checks:
•	We established validation rules to ensure consistency of the data and to make the data conform to expected standards.
•	Automated checks were implemented to alert and identify possible problems before analysis.

4.	Data Quality Reporting:
•	Performed documented all cleaning steps and validation rules applied.
•	Reported prepared reports with data quality improvement and exceptions reports, if any.

Tools and Technologies:
AWS Glue DataBrew, Amazon S3

Deliverables:
Data Quality Control Report, documenting the phases of the data Profiling, cleaning and validation.

 

Data Governance

The structure of the given sentence is changed. In this case, it ensures reliable data usage during the different stages that are part of the entire data analysis pipeline.

Objective: Design a framework that has a strong data governance, which shall maintain and facilitate the organization of metadata and data access, thereby facilitating an easy fit within the data analysis processes.

Methodology:
Metadata Management:
•	It was configured to create a centralized metadata repository using AWS Glue Data Catalog.
•	The data clarity and usability have been enhanced by naming the meaningful table and column names with descriptions.

Access Control Management:
•	I applied IAM policies to limit what data someone can access via roles and permissions.
•	Prevents people with fake WhaleSharks credentials from accessing the buckets or the whale shark specific datasets.

Data Consistency:
•	The application has standardized datasets, tables, and columns all with a known and unchanging naming convention.
•	Enforced an applied versioning to hold historical integrity of datasets.

Data Discovery:
•	To aid in data discovery, structured query was used through the use of AWS Glue Data Catalog.
•	It enabled efficient datasets searching and cataloging for further analysis to be done.

Tools and Technologies:
AWS Glue Data Catalog, Amazon S3, IAM Policies

Deliverables:
Metadata structure, access management, data consistency processes are documented in Governance Documentation.



Data Security

Project Description:
Data Security Measurements for the 311 Inquiry Volume dataset is to protect the dataset during its lifecycle from ingestion to analysis against unauthorized access, tampering, loss.

Title of the project: Data Security for 311 Inquiry Volume Dataset

Objective:
The main use would be to set up a secure environment for storing, accessing and analyzing the 311 Inquiry Volume dataset using encryption, access control mechanism and studying monitoring system to maintain the confidentiality, integrity and availability of the data.


Dataset:
•	311 Inquiry Volume CSV File
•	Inquiry Type, Date, Neighborhood, Volume Count are the fields.
•	Amazon S3 stores data and AWS Glue Data Catalog and Amazon Athena are available to access it.


Methodology:
Data Encryption:
•	Used AWS Key Management Service (KMS) to encrypt the datastore of the dataset to Amazon S3.
•	It automatically encrypted data as it is uploaded using Enabled Server Side Encryption (SSE) with KMS keys.
•	Ashley configured bucket policies to mandate that all data uploaded is encrypted.

Access Control:
•	IAM Policies were defined and applied as well to restrict the access to the dataset.
•	Different user group, such as Data Analysts, Data Engineers, and Administrators, got role based access controls on.
•	S3 Bucket Policies and ACLs were implemented for controlling the data access permissions.
•	Only authorized users and services would be able to access or modify the dataset.

Data Integrity:
•	Facilitated security through the enabling of S3 Versioning for maintaining historical versions of datasets in order to recover the same in case we accidentally modify or delete them.
•	Installed AWS CloudTrail to log every access request made on the dataset as well as any modifications for auditing purposes.
•	Monitor the logs to see which attempt or suspicious act is unauthorized.

Monitoring and Alerts:
•	I picked up AWS services for monitoring the dataset accesses and performance metrics on Amazon CloudWatch.
•	I created CloudWatch Alerms to detect suspicious access attempts or untypical looking query patterns.
•	I configured Amazon SNS (Simple Notification Service) to send alerts to interested party when anomalies were detected.

Documentation and Compliance:
•	Kept a maintained documentation on all security policies, encryption standards and access controls.
•	Ensured adherence to AWS best practices and compliance requirements for data security.

Tools and Technologies:
Amazon S3, AWS KMS, IAM Policies, AWS CloudTrail, Amazon CloudWatch, Amazon SNS

Deliverables:
Data Security Report describing security measures used to be applied, policies to be followed and configurations that have been implemented.


 

 





 
AWS Cloud Foundations Badge Link:
https://www.credly.com/badges/1f862a47-8e76-4ba9-9fa9-d9651268f021/public_url

 
