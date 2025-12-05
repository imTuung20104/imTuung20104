# 📦 Automated Freight Rate Calculator

> **A Python-based tool to optimize logistics cost calculation and eliminate manual data entry errors.**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)]()

## 🚩 The Problem
In daily Logistics operations, calculating freight costs involves comparing rates from multiple forwarders manually. This process is:
* **Time-consuming:** Taking hours to process weekly quotations.
* **Error-prone:** Manual data entry in Excel often leads to calculation mistakes.

## 💡 The Solution
I developed a Python script utilizing the **Pandas** library to automate the calculation process.
* **Input:** Reads raw Excel/CSV quotation files from various carriers.
* **Processing:** Automatically cleans data, maps charges, and calculates total costs based on Incoterms.
* **Output:** Generates a clean comparison report highlighting the best option.

## 🚀 Key Results
* **Efficiency:** Reduced reporting time by **50%** (from 2 hours to ~1 hour/week).
* **Accuracy:** Eliminated manual calculation errors.
* **Scalability:** Can handle hundreds of rows of data instantly.

## 💻 How to use
1.  Place your rate sheet in the `input/` folder.
2.  Run the script:
    ```bash
    python freight_calculator.py
    ```
3.  Check the `output/` folder for the final report.

---
*Created by [Bui Xuan Tung](https://github.com/imTuung20104)*
