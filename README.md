# Power BI - Fraud Analytics Dashboard

An end-to-end Power BI dashboard that analyzes banking transaction data to identify fraudulent activities, uncover fraud drivers, evaluate risk exposure, and provide actionable business recommendations through interactive visualizations and executive reporting.

---

## Project Highlights

- End-to-end Fraud Analytics Dashboard
- Executive KPI Dashboard
- Fraud Driver Analysis
- Risk Segmentation & Fraud Exposure
- Interactive Investigation Workbench
- Drill-through Navigation
- Business Recommendations
- Professional multi-page dashboard design
- Interactive slicers and cross-filtering

---

## Table of Contents

1. Project Overview
2. Business Problem
3. Project Objectives
4. Dataset Overview
5. Dashboard Architecture
6. Tools Used
7. Skills Demonstrated
8. Dashboard Pages
9. Key KPIs
10. Business Insights
11. Dashboard Preview
12. Project Setup
13. Repository Structure

---

## 1. Project Overview

Financial institutions process thousands of transactions every day, making fraud detection a critical business requirement. Detecting suspicious activities quickly helps reduce financial losses while improving customer trust.

This project develops an end-to-end Fraud Analytics Dashboard in Power BI that enables business users to monitor fraud exposure, investigate fraud patterns, identify key fraud drivers, evaluate risk segmentation, and support operational decision-making through interactive dashboards.

---

## 2. Business Problem

Fraudulent financial transactions lead to significant financial losses and operational risks.

Business stakeholders require answers to questions such as:

- Which payment channels experience the highest fraud?
- Which authentication methods are most vulnerable?
- Which customer segments contribute most to fraud losses?
- Which transactions require immediate investigation?
- Which factors are strongest predictors of fraudulent activity?
- How should fraud prevention resources be prioritized?

This dashboard answers these questions through interactive Power BI visualizations.

---

## 3. Project Objectives

- Monitor overall fraud exposure
- Measure fraud rate and fraud losses
- Analyze fraud across payment channels
- Investigate authentication methods
- Evaluate device risk categories
- Perform anomaly analysis
- Segment fraud by risk level
- Support fraud investigations
- Generate business recommendations

---

## 4. Dataset Overview

The project uses a simulated banking transaction dataset containing transaction-level fraud information.

### Dataset includes:

| Column | Description |
|---------|-------------|
| Transaction ID | Unique transaction identifier |
| Payment Channel | ATM, POS, Mobile App, Web Banking |
| Authentication Type | OTP, Password, Biometric, Two-Factor Authentication |
| Device Risk Category | Low, Medium, High, Critical |
| Velocity Category | Low, Medium, High, Critical |
| Anomaly Category | Low, Medium, High, Critical |
| Transaction Amount | Transaction value |
| Fraud Flag | Fraudulent or Genuine transaction |

### Dataset Characteristics

- Industry: Banking & Financial Services
- Records: 10,000 Transactions
- Data Type: Financial Transaction Data

---

## 5. Dashboard Architecture

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Modeling
      │
      ▼
DAX Measures
      │
      ▼
Executive Dashboard
      │
      ▼
Fraud Driver Analysis
      │
      ▼
Risk Segmentation
      │
      ▼
Detailed Investigation
      │
      ▼
Business Recommendations
```

---

## 6. Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Interactive Visualizations

---

## 7. Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- KPI Development
- Dashboard Design
- Executive Reporting
- Fraud Analytics
- Business Intelligence
- Interactive Filtering
- Drill-through Navigation
- Business Storytelling

---

## 8. Dashboard Pages

## Introduction

Project background, objectives, and dashboard overview.

---

## Executive Overview

Provides a high-level view of fraud exposure through KPIs including:

- Total Transactions
- Fraud Transactions
- Fraud Rate
- Total Fraud Loss
- Average Fraud Value
- Fraud Distribution by Payment Channel
- Fraud Distribution by Authentication Method

---

## Fraud Driver Analysis

Analyzes key factors influencing fraudulent transactions.

Includes:

- Fraud Rate by Anomaly Category
- Fraud Rate by Authentication Type
- Fraud Rate by Payment Channel
- Device Risk Analysis
- Decomposition Tree for Root Cause Investigation

---

## Risk Segmentation

Evaluates fraud across different risk levels.

Includes:

- Fraud Transactions by Risk Segment
- Fraud Loss by Risk Segment
- Risk Segment Summary
- Fraud Composition Analysis

---

## Investigation Workbench

Detailed operational dashboard supporting fraud investigations.

Includes:

- Fraud Rate Tables
- Authentication Summary
- Device Risk Summary
- Velocity Analysis
- Payment Channel Analysis
- Interactive Filtering

---

## Business Recommendations

Summarizes findings from all dashboard pages and provides actionable recommendations for fraud prevention, authentication improvements, transaction monitoring, and resource allocation.

---

## 9. Key KPIs

- Total Transactions
- Fraud Transactions
- Fraud Rate
- Total Fraud Loss
- Average Fraud Value
- Fraud Distribution
- Fraud Loss by Channel
- Fraud Rate by Authentication
- Fraud Rate by Risk Segment

---

## 10. Business Insights

- Mobile App transactions contribute the largest share of fraudulent activity.
- Critical anomaly transactions exhibit exceptionally high fraud rates.
- Two-Factor Authentication demonstrates lower fraud exposure compared to Password-only authentication.
- Higher risk segments account for the majority of fraud losses.
- Device risk scoring is strongly associated with fraud occurrence.
- Interactive investigation enables rapid identification of high-risk transaction patterns.

---

## 11. Dashboard Preview

## Executive Dashboard

<img width="977" height="620" alt="Screenshot 2026-07-13 230245" src="https://github.com/user-attachments/assets/62a87a66-b690-414b-8df9-13daf1c20765" />

---

## Fraud Driver Analysis

<img width="977" height="617" alt="Screenshot 2026-07-13 230300" src="https://github.com/user-attachments/assets/5529f630-6140-422a-8f8e-997b1c1d80d4" />

---

## Risk Segmentation

<img width="977" height="621" alt="Screenshot 2026-07-13 230313" src="https://github.com/user-attachments/assets/d8ed6915-55dd-4536-8666-d093176d0d69" />

---

## Investigation Workbench

<img width="978" height="620" alt="Screenshot 2026-07-13 230326" src="https://github.com/user-attachments/assets/0b967603-ddc1-4a38-9c2b-eca5de16d472" />

---

## Business Recommendations

<img width="983" height="617" alt="Screenshot 2026-07-13 230341" src="https://github.com/user-attachments/assets/64987033-1552-4047-8919-cd8bf7422d25" />

---

## Project Setup

1. Clone the repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the dashboard using filters and interactive visuals.

---

## Repository Structure

```text
powerbi-fraud-analytics-dashboard/
│
├── images/
│   ├── overview.png
│   ├── fraud-driver-analysis.png
│   ├── risk-segmentation.png
│   ├── detailed-analysis.png
│   └── business-recommendations.png
│
├── dataset/
│   └── fraud_dataset.csv
│
├── Fraud Analytics Dashboard.pbix
└── README.md
```

---

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811)

![DAX](https://img.shields.io/badge/DAX-Measures-blue)

![Status](https://img.shields.io/badge/Status-Completed-success)
