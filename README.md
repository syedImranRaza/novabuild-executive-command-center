# NovaBuild Executive Command Center

## End-to-End Microsoft Fabric Analytics Platform

### Project Overview

NovaBuild Executive Command Center is an end-to-end enterprise analytics solution built using Microsoft Fabric, Azure SQL, Azure Blob Storage, and Power BI.

The project demonstrates how multiple business systems can be integrated into a modern analytics platform using Medallion Architecture (Bronze, Silver, Gold), Lakehouse, Warehouse, Semantic Models, and Executive KPI Reporting.

The objective was to simulate a real-world construction and project management organization and provide executive stakeholders with a centralized command center for monitoring project performance, financial health, procurement activities, and workforce productivity.

---

## Business Domains

The platform integrates data from four key business functions:

### Project Management

* Project performance
* Completion tracking
* Schedule delays
* Project health monitoring

### Finance

* Budget management
* Expense tracking
* Budget variance analysis
* Cost control

### Procurement

* Purchase orders
* Vendor performance
* Procurement spend
* Delivery delays

### Workforce Analytics

* Attendance
* Utilization
* Overtime
* Department productivity

---

## Technology Stack

### Data Sources

* Azure SQL Database
* Azure Blob Storage
* CSV Files
* Excel Files

### Data Engineering

* Microsoft Fabric Pipelines
* Microsoft Fabric Lakehouse
* Dataflow Gen2
* T-SQL

### Data Modeling

* Star Schema
* Dimensional Modeling
* Semantic Models

### Reporting

* Power BI
* DAX
* Executive Dashboards

---

## Architecture

Source Systems

* HRMS Database
* Finance Database
* ERP Project Data
* Procurement Files

↓

Fabric Pipelines

↓

Bronze Layer

↓

Dataflow Gen2 Transformations

↓

Silver Layer

↓

Enterprise Data Warehouse

↓

Semantic Model

↓

Power BI Executive Reporting

---

## Medallion Architecture

### Bronze Layer

Raw ingestion layer containing source system data.

### Silver Layer

Data cleansing, standardization, validation, and transformation layer.

### Gold Layer

Business-ready dimensional model and reporting layer.

---

## Data Model

Dimensions:

* DimDate
* DimProject
* DimEmployee
* DimDepartment
* DimVendor

Facts:

* FactProjectPerformance
* FactFinance
* FactProcurement
* FactLaborUtilization

---

## Dashboard Pages

### Executive Command Center

Executive KPI overview and strategic insights.

### Project Performance Analytics

Project health, completion tracking, and delay analysis.

### Financial Analytics

Budget vs Actual analysis, margin monitoring, and expense trends.

### Procurement Analytics

Vendor performance and procurement efficiency.

### Workforce Analytics

Attendance, utilization, overtime, and productivity metrics.

---

## Key Features

* End-to-End Microsoft Fabric Implementation
* Medallion Architecture
* Lakehouse and Warehouse Design
* Semantic Modeling
* Star Schema Data Modeling
* DAX Measures and KPI Framework
* Executive Reporting
* Cross-functional Analytics
* Interactive Power BI Dashboards

---

## Learning Outcomes

This project demonstrates practical implementation of:

* Data Engineering
* Analytics Engineering
* Data Modeling
* Business Intelligence
* Enterprise Reporting
* Microsoft Fabric Architecture
* Power BI Development

---

## Author

Imran Raza
Data Analyst | Business Intelligence Analyst | Microsoft Fabric & Power BI Enthusiast
