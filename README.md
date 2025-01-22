# Dallas-Food-Inspection-PowerBI-Dashboard

---

## Overview

This project focuses on analyzing food inspection data from various establishments in Dallas, Texas. The dataset includes comprehensive information on inspection results, detailing the number and types of violations recorded during each inspection. The goal of this project is to uncover insights into food safety compliance, identify trends, and propose actionable recommendations to improve food safety practices in the city.

## Table of Contents
- [Overview](#overview)
- [Purpose](#purpose)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Corrective Actions](#corrective-actions)
- [Tech Stack](#tech-stack)
- [How to Run](#how-to-run)
- [Acknowledgments](#acknowledgments)

---

## Purpose

The primary objective of this analysis is to:
1. Assess the scale of food inspection operations in Dallas.
2. Understand the compliance level of food establishments based on their inspection scores.
3. Address critical business questions such as:
   - Which establishments have the highest violations?
   - What patterns emerge in compliance scores across different types of establishments?
   - Which violations are most common, and how can they be mitigated?

---

## Dataset

The dataset includes:
- Inspection dates
- Establishment details
- Inspection scores
- Types of violations

Score classifications are as follows:
- **100-90**: Very Good (Regular 6-month inspection)
- **89-80**: Good (Regular 6-month inspection)
- **79-70**: Passing (Re-inspection required within 30 days)
- **69-60**: Failing (Follow-up inspection within 10 days or closure)
- **Below 59**: Unacceptable (Closure and mandatory inspection before reopening)

---

## Methodology

### Data Cleaning
- Loaded the dataset using Python libraries such as Pandas and NumPy.
- Reviewed and cleaned the data by:
  - Removing duplicates.
  - Handling missing values.
  - Formatting and standardizing columns for consistency.

### Exploratory Data Analysis (EDA)
- Conducted pivot analyses to understand relationships between inspection scores and violations.
- Analyzed distribution patterns and trends using descriptive statistics.

### Visualizations
- Created insightful visualizations using Power BI to:
  - Highlight trends in compliance scores over time.
  - Show the frequency and types of violations.
  - Identify establishments with consistently poor performance.

---

## Key Findings

1. Establishments with inspection scores below 70 require immediate follow-up to ensure public health safety.
2. Common violations include improper food storage, hygiene issues, and lack of employee training.
3. Seasonal trends were observed, with higher violations recorded during peak restaurant activity periods.

---

## Corrective Actions

To address these findings, the following recommendations were proposed:
- Regular training programs for staff on food safety protocols.
- Introduction of a digital alert system for establishments nearing compliance deadlines.
- Public awareness campaigns about food safety standards.

---

## Tech Stack

- **Power BI**: For interactive data visualizations.
- **Python**: For data cleaning and exploratory analysis.
- **Microsoft Excel**: For exporting and reviewing clean datasets.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/username/dallas-food-inspection-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dallas-food-inspection-analysis
   ```
3. Open the `Power BI` file in Power BI Desktop to explore visualizations.
4. View the Python notebook for data cleaning and exploratory analysis.

---

## Acknowledgments

Special thanks to the Dallas City Council for making this data publicly available.
