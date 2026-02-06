# End_to_End_Data_Flow_ETL_Excel

## 📌 Problem Statement
Raw data collected from multiple business systems cannot be directly used for analytics due to quality issues, inconsistencies, and missing values. An ETL process is required to transform raw data into analytics-ready data.

## 🎯 Objective
To simulate an end-to-end data flow and ETL (Extract, Transform, Load) process using Excel, and understand how raw transactional data is converted into meaningful data for analytics and reporting.

## 🏗️ End-to-End Data Flow Architecture
![ETL Data Flow](visuals/etl_end_to_end_data_flow.png)

## 📊 Data Sources
The dataset represents customer transaction data originating from:
- Customer applications
- Payment systems
- Sales platforms

## 🗄️ Transactional Databases
Raw data is assumed to be stored in transactional systems that support:
- Real-time processing
- Batch processing

These systems are optimized for operations, not analytics.

## 🔄 ETL Process

### 1️⃣ Extract
Raw customer sales data was extracted from transactional systems and stored as an unprocessed dataset.

### 2️⃣ Transform
Data transformation was performed using Microsoft Excel:
- Removed duplicate records
- Cleaned missing and inconsistent values
- Standardized gender and date formats
- Handled invalid transaction values
- Renamed and formatted columns for clarity

### 3️⃣ Load
The cleaned and structured dataset was finalized as analytics-ready data, simulating loading into a data warehouse.

## 📈 Use Cases
- Business reporting
- Sales analysis
- Dashboard creation
- Data-driven decision making

## 🛠️ Tools Used
- Microsoft Excel (ETL simulation)
- Power BI (conceptual understanding)
- GitHub (project documentation)

## 🚀 Key Learnings
- Understood real-world data flow architecture
- Practiced ETL concepts using Excel
- Learned how raw data becomes analytics-ready
- Strengthened data analytics fundamentals
