# Dirty-Financial-Data-Generator
# 🗑️ Dirty Data Generator

> Synthetic financial data generator designed to simulate real-world data anomalies for machine learning preparation.

## 📖 Project Overview

This project is being developed for a University of Birmingham MSc course (170 students). It addresses a critical gap in data science education: the jump between perfectly sanitized Kaggle datasets and messy, real-world data. 

By generating synthetic, realistic financial transaction data with configurable errors, this tool provides students with essential, hands-on data preparation and cleaning experience required for machine learning pipelines.

## 🎯 Target Timeline

* **Hard Deadline:** Tool required by **April 29th, 2026** for student presentations.

## ⚙️ Technical Requirements & Features

### Core Data Generation
* **Volume:** Generate large-volume financial transaction data.
* **Domains:** Initial focus on two financial sectors: 
  * Banking statements/transactions
  * Loan/mortgage repayments
* **Output:** `CSV` and `Excel` files generated via a Command Line Interface (CLI) in the initial release.

### Error Simulation Engine
* **Adjustable Error Rates:** Configurable percentage of corrupted data.
* **Multiple Error Types:** Range from subtle anomalies to obvious data corruption.
* **Realistic Scenarios:** Simulate manual entry typos, missing values, duplicated entries, format inconsistencies, and systemic errors caused by legacy system transitions.

## 🛠️ Use Cases

* **Educational Assignments & Workshops:** Allows instructors to generate reproducible, messy datasets with specific error profiles for student data-wrangling assignments.
* **ETL Pipeline Stress-Testing:** Provides data engineers with unpredictable, corrupted files to test the resilience and exception-handling of data ingestion (Extract, Transform, Load) pipelines.
* **ML Model Robustness Evaluation:** Enables data scientists to test how a machine learning model's accuracy degrades when exposed to noisy data, helping to build more fault-tolerant models.
* **Anomaly Detection Training:** Creates environments where algorithms must distinguish between typical manual entry errors (like a misplaced decimal) and actual fraudulent transactions.

## 🏗️ Project Scope & Approach

1. **Phased Development:** Initially limit generation strictly to banking and mortgage sectors to ensure high-quality error simulation.
2. **Reverse Engineering Approach:** Study the desired "dirty" end-state first, build the error-generation logic, and then establish the clean data baselines.
3. **Continuous Research:** Investigate existing techniques and Python libraries for synthetic error generation to avoid reinventing the wheel.
4. **Agile & Flexible:** Maintain flexibility to adjust data parameters based on industry partner requirements stemming from the Birmingham event.
