# Supplier Quality Analysis & Downtime Analysis

## Project Overview

This project uses Microsoft Power BI to analyse supplier quality performance, defect quantities, rejected defects, and operational downtime.

The objective is to develop visibility into supplier-related quality issues and understand how defect quantities and downtime are distributed across vendors, material types, categories, plants, and time periods.

The dashboard combines supplier quality analysis with downtime monitoring to support data-driven supplier evaluation, quality control, and operational improvement.

---

## Business Objectives

- Analyse total defect quantities and reported defect records.
- Evaluate rejected defect quantities.
- Compare defect performance across categories and material types.
- Examine defect distribution across plants.
- Analyse downtime across different vendors.
- Compare supplier-related defect quantities with downtime minutes.
- Identify areas requiring further quality investigation and operational improvement.

---

## Tools & Techniques

| Category | Tools / Techniques |
|---|---|
| Data Analysis & Visualization | Microsoft Power BI |
| Data Modelling | Power BI Data Model |
| Calculations | DAX |
| Supplier Analysis | Vendor-level performance analysis |
| Quality Analysis | Defect quantity and rejection analysis |
| Downtime Analysis | Downtime measurement and vendor comparison |
| Analytical Approach | Category, material, plant and time-based analysis |

---

## Dashboard Structure

The Power BI report consists of two major analytical sections.

### 1. Supplier Quality Analysis

This section evaluates defect quantities and quality-related performance across different dimensions.

**Key KPIs and measures:**
- Total Downtime Minutes
- Total Defect Quantity
- Defects with No Impacts
- Defects Rejected Reports
- Total Defect Reports

**Analysis performed:**

**Defect Analysis by Plant**
- Examines reported defect quantities across plants.
- Provides visibility into plant-level quality performance.

**Material Type Analysis**
- Compares defect quantities and downtime minutes across material types.
- Helps identify material categories requiring further investigation.

**Category-wise Defect Analysis**
- Analyses defect quantities and defect reports across categories.
- Helps understand how quality issues are distributed across product or material categories.

**Defect Trend Analysis**
- Examines monthly defect quantities.
- Includes comparison between current defect quantities and the same period in the previous year (SPLY).

### 2. Downtime Analysis

This section focuses on understanding operational downtime and its distribution across vendors and material categories.

**Key KPIs and measures:**
- Total Defect Quantity
- Downtime Minutes
- Total Downtime Minutes

**Analysis performed:**

**Vendor-wise Downtime**
- Compares downtime minutes across vendors.
- Provides visibility into vendor-level downtime distribution.

**Vendor and Category Analysis**
- Examines downtime across vendors and categories.
- Helps identify segments requiring further operational investigation.

**Defect Quantity vs Downtime**
- Compares total defect quantity and downtime minutes across vendors.
- Provides a combined view of quality-related and downtime indicators.

**Material-wise Downtime**
- Analyses downtime minutes across different material types.
- Helps identify material segments associated with higher recorded downtime.

**Vendor Downtime Comparison**
- Provides a vendor-level view of total downtime minutes.

---

## Key Analytical Dimensions

The dashboard uses the following dimensions for segmentation:

| Dimension | Analytical Purpose |
|---|---|
| Vendor | Supplier-level comparison |
| Defect Type | Defect classification |
| Material Type | Material-level quality and downtime analysis |
| Category | Category-wise defect and downtime distribution |
| Plant | Plant-level defect reporting |
| Month | Time-based defect trend analysis |

---

## Business Applications

The analysis can support:

- Supplier quality monitoring.
- Identification of vendors requiring further investigation.
- Defect trend monitoring.
- Material-level quality evaluation.
- Plant-level quality visibility.
- Downtime monitoring.
- Prioritisation of quality improvement initiatives.
- Evidence-based supplier performance discussions.

---

## Potential Improvement Opportunities

Based on the analytical structure, the dashboard can support further investigation into:

1. Vendors associated with higher recorded defect quantities.
2. Material types contributing to defect and downtime indicators.
3. Categories with comparatively higher defect reporting.
4. Monthly changes in defect quantities.
5. Vendors showing both higher defect quantities and downtime.

These are investigation areas rather than confirmed root causes. Establishing causality would require additional operational investigation and supporting process data.

---

## Lean Six Sigma Application

The dashboard provides a foundation for applying the DMAIC framework to supplier quality and downtime problems.

| DMAIC Phase | Application |
|---|---|
| Define | Define the supplier quality or downtime problem. |
| Measure | Establish defect quantity, defect reporting and downtime baselines. |
| Analyze | Segment defects and downtime by vendor, category, material and plant. |
| Improve | Develop corrective-action proposals based on validated root causes. |
| Control | Monitor defect quantities and downtime trends over time. |

Potential improvement approaches include supplier corrective action plans, material quality checks, defect prevention measures, and structured downtime monitoring.

These should be validated against the actual operational causes before implementation.

---

## Dashboard Screenshots

### Supplier Quality Analysis

![Supplier Quality Analysis](Screenshots/Supplier_Quality_Analysis.png)

### Downtime Analysis

![Downtime Analysis](Screenshots/Downtime_Analysis.png)

---

## Repository Structure

```text
Supplier-Quality-and-Downtime-Analysis/
│
├── README.md
│
├── Dashboard/
│   └── Project_3_Supplier_Quality_Analysis_and_Downtime.pbix
│
├── Screenshots/
│   ├── Supplier_Quality_Analysis.png
│   └── Downtime_Analysis.png
│
└── Documentation/
    └── Project_Analysis.pdf
```

---

## Conclusion

This project demonstrates the use of Power BI and DAX to analyse supplier quality indicators and operational downtime.

By combining defect analysis, vendor-level comparisons, material segmentation, and downtime monitoring, the dashboard provides a structured view of quality-related operational performance.

The analysis can help supply chain and operations teams identify areas requiring further investigation, improve supplier quality monitoring, and support continuous improvement initiatives.
