# sql-data-warehouse-project
=====================================
Data Warehouse Of E-commerce
=====================================
Project Overview: 
- The Project demonstrates the Creation of a data warehouse.
- collection data from CRM and ERP table of an online shopping and creating a centralized database
- Incorporate a warehouse architecture to make data usable for Business Analysis

- Create an account in Notion for tracking project progress
- SMSS for DDL and DML
- Github for uploading project to repository
- Draw.io for Architecture and Entity Diagrams

Step 1 : Create Project Plan
- Requirement Analysis
- Designing Data Architecture
- Implementing project Architecture
- Creating Database Schema
- Inserting Data
- Creating Views

Step 2 : Create Task in Notion with all description
Step 3 : Create DDL Schema in MS SQL using Medillion Architecture
- create schema bronze
- create schema silver 
- create schema Gold

BRONZE LAYER
- Create Tables provided from CRM and ERP tables
- Insert data from csv files
- Create Stored Procedure bronze.bronze_load

SIVER LAYER
- to load data from Bronze layer we need to perform quality checks
- data cleaning 
- data standardization
- Column Derivation
- Integration model
- Insert Into tables after quality checks
- Create Stored Procedure silver.silver_load

GOLD LAYER
- Draw a datamart diagram for sales, product and customers
- Provide data to be consumed for reporting and analysis
- Creating views and joins
- Using star schema for fact and dimension tables
- provides objects for data objects
