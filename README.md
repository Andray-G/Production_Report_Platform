# Production Reporting Platform


This repository provides an overview of a Power BI-based data integration and reporting project designed to deliver actionable insights through automated dashboards and streamlined data processes.

## Overview

This project focuses on building a scalable and professional reporting solution. By leveraging ETL processes, data from multiple sources is consolidated into a structured relational data model, enabling effective decision-making and operational efficiency.

## Data Model

The relational data model includes the following components:

* CRM Data: Contains customer information such as Account Manager, Annual Revenue, and Contact Details.

* Machine Utilization: Includes machine performance metrics, job types, and downtime data.

* Inventory: Tracks inventory details, material costs, and operational sequences.

* Employees: Provides employee-related information such as department, job title, and hourly rates.

## Key Features

### Data Integration:
* Consolidates data from ERP systems and Python-extracted machine job data into two databases.

* Addresses inconsistencies, such as ID mismatches and decimal precision issues.

### Automated Reporting: 
Implements automated data refresh schedules, minimizing manual effort and ensuring timely updates.

### Interactive Dashboards:
Delivers actionable insights into:

  * Job Efficiency

  * Production and OOE Performance

  * Operational Quality

  * Lead Time and Downtime

  * Manufacturing Cost Analysis

### Security:
* Employs role-based access control for secure data sharing.

### Testing and Validation:
* Ensures data accuracy and dashboard performance through rigorous validation and testing.

## Data Privacy

All datasets (CRM, Machine Utilization, Inventory, and Employees) were randomized using Python to ensure sensitive information, such as customer details and employee names, is anonymized prior to uploading.

## Tools and Environment

* Tools Used: Python, Power BI, SQL


## Scope

This project encompasses:
* Data integration and transformation
* Dashboard development
* Automated reporting
* Security implementation
* End-user training and enablement

---
For more detailed technical requirements, refer to the dedicated requirements document in this repository.
