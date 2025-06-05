# PEI_Assignment
Data modeling and analysis project for PEI Group case study

# Sales Data Analytics & Domain Modeling Project
## 👋 Introduction

Hi, I’m Muskaan Sinha, and this project was completed as part of the interview selection process for a Senior Data Analyst role. The objective was to validate source datasets, define a robust domain model, and prepare detailed documentation that would allow data engineers and QA teams to implement pipelines and enable key reporting use cases.

The challenge involved working with sales data sourced from three files—customer profiles, orders, and shipping status—and converting them into a usable structure that can support cross-functional reporting.

# 🧠 Sales Data Analytics and Domain Modeling Assignment

## 📌 Overview

This repository presents the end-to-end solution to a business analytics case study aimed at evaluating the capability to work across data quality validation, domain modeling, and communication with data engineering and other stakeholders.

The dataset comprises three source files:
- `Customer.csv`: Basic customer demographics
- `Order.csv`: Transactional sales records
- `Shipping.json`: Delivery status records

## 🎯 Objective

The key deliverables were:

1. Verify- the accuracy, completeness, and reliability of raw data using Python and SQL.
2. Define- A scalable domain model that maps cleanly to the business’s reporting needs.
3. Prepare- A data engineering story that outlines field-level transformations and QA checks.

> The goal was to make this solution implementation-ready—allowing engineers to build pipelines and reports without looping back for clarifications.

---

## 👤 Role

As the Data Analyst, my responsibilities included:
- Verifying accuracy, completeness, and reliability of the data
- Designing a scalable domain model to meet key reporting needs
- Writing a detailed technical story for Data Engineering
- Mapping dataset fields to business reporting requirements

---

## 📊 Reporting Requirements (Business Needs)

The following business questions must be supported by the data model:

1. Total amount spent and country for the "Pending" delivery status.
2. Customer-level view with:
   - Total number of transactions
   - Total quantity sold
   - Total amount spent
   - Product details
3. Maximum product purchased per country.
4. Most purchased product by age category:
   - Under 30
   - 30 and above
5. Country with minimum transactions and lowest sales amount.

---

## 🧠 Approach

My process was broken into four clear phases:

### Phase 1: Data Audit  
Each dataset was validated for:
- Missing/null values
- Duplicate records
- Schema consistency
- Referential integrity (e.g. foreign key alignment)

### Phase 2: Domain Modeling  
Using insights from the audit, I created:
- A clean, joined entity-relationship model
- Mappings of business keys and foreign keys
- Sample queries to validate model integrity

### Phase 3: Technical Story  
A markdown-based spec was created for engineers, including:
- Source-to-target field mapping
- Transformation rules (e.g. age buckets, aggregations)
- Sample data and test case logic for QA

### Phase 4: Business Mapping  
Each of the 5 reporting asks was linked back to specific fields and tables in the model.

---

## 📂 Supporting Files
- PEI_Assignment.py: Contains Python code for data audit checks including null validations, join integrity, and aggregation testing.
- PEI_Assignment_Documentation.pdf: A detailed write-up covering problem understanding, data model, transformations, QA logic, and business mapping.
