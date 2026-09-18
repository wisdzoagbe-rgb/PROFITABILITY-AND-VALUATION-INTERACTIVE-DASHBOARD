# PROFITABILITY-AND-VALUATION-ANALYSIS

<img width="2531" height="2025" alt="image" src="https://github.com/user-attachments/assets/8fb59958-8d24-4e8e-9df8-816aca819cb4" />

This dataset provides a comprehensive collection of financial statement data from various companies, covering key financial metrics used for financial statement analysis. It includes information from income statements, balance sheets, and cash flow statements, enabling users to perform ratio analysis, trend analysis, and predictive modeling.

## 1. Project Overview

This project analyzes the financial performance and relative valuation of a selected group of publicly traded companies using historical financial and market data.

The analysis focuses on three broad areas:

* **Profitability:** Gross margin and operating margin
* **Operating performance:** Historical operating-margin trends and periods of negative operating margin
* **Relative valuation:** Price-to-Earnings (P/E) and Price-to-Book (P/B) ratios compared with peer-group benchmarks

The objective is to turn the underlying financial data into clear, decision-useful insights through structured analysis, interpretation, and visualization.

---

## 2. Business Questions

The project was designed to answer the following five questions:

1. **Which company has the highest latest operating margin?**
2. **Which company has the highest latest gross margin?**
3. **Which company recorded the most years of negative operating margin?**
4. **Which profitable companies appear undervalued relative to peer P/E and P/B medians?**
5. **Which profitable companies appear overvalued relative to peer P/E and P/B medians?**

These questions form the basis for the analysis and dashboard outputs.

---

## 3. Workbook Structure

The workbook is organized into six main worksheets.

### 3.1 Business Questions

This sheet defines the key questions the analysis is intended to answer.

It provides the analytical framework for the project and ensures that the subsequent calculations and visualizations remain focused on specific business questions.

---

### 3.2 Data

This is the underlying data sheet.

It contains historical observations for each company, including:

* Year
* Company
* Gross Margin
* Operating Margin
* Price-to-Earnings Ratio
* Price-to-Book Ratio
* Valuation Index
* Valuation Status
* Profitability Status

The dataset covers multiple years for the selected companies and provides the foundation for all subsequent analysis.

The companies included are:

* AAPL
* AIG
* AMZN
* BCS
* GOOG
* INTC
* MCD
* MSFT
* NVDA
* PCG
* PYPL
* SHLDQ

The data should be treated as the source layer of the workbook. Analytical outputs should be updated when the underlying data changes.

---

### 3.3 Analysis

This sheet contains the analytical outputs used to answer the five business questions.

It uses summary tables and charts to identify:

* The latest year available for each company
* Latest operating margins
* Latest gross margins
* Companies with negative operating-margin years
* Companies classified as undervalued
* Companies classified as overvalued

The analysis is structured so that company-level results can be compared consistently across the selected peer group.

---

### 3.4 Interpretation of Analysis & Valuation

This sheet translates the numerical analysis into business observations.

The purpose is to move beyond simply displaying figures and explain what the results indicate about:

* Relative profitability
* Operating performance
* Historical losses
* Relative valuation
* Differences between companies within the peer group

The interpretation should be read together with the underlying analysis rather than treated as a replacement for the source data.

---

### 3.5 Executive Summary

The Executive Summary provides a condensed view of the project for readers who need the key findings without reviewing every analytical table.

It covers:

* Project purpose and scope
* Key findings
* Overall observations
* Conclusion

This section is intended to provide a quick understanding of the main financial patterns identified in the analysis.

---

### 3.6 Dashboard

The Dashboard provides a visual presentation of the analysis.

It is designed to make comparisons between companies easier by presenting the most relevant analytical outputs in a consolidated format.

The dashboard should be used as the starting point for reviewing the results, with the Analysis and Data sheets used for supporting detail.

---

## 4. Key Analytical Concepts

### Operating Margin

Operating margin measures the proportion of revenue remaining after operating expenses.

**Operating Margin = Operating Income ÷ Revenue**

A higher operating margin generally indicates that a company retains more operating profit from each unit of revenue.

---

### Gross Margin

Gross margin measures the proportion of revenue remaining after the cost of goods sold.

**Gross Margin = Gross Profit ÷ Revenue**

It provides an indication of the company's gross-level profitability before operating expenses.

---

### Negative Operating Margin

A negative operating margin indicates that operating expenses exceed operating profit for the period.

The project counts the number of years in which each company recorded a negative operating margin to identify companies with recurring operating losses within the available historical data.

---

### Relative Valuation

The project uses P/E and P/B ratios to compare companies against peer-group valuation benchmarks.

The analysis combines these valuation measures into a **Valuation Index**.

The resulting index is used to classify companies into valuation categories:

* **Undervalued**
* **Fairly Valued**
* **Overvalued**
* **Not Applicable**, where the valuation calculation cannot meaningfully be applied

The valuation classification is relative to the selected peer group and should not be interpreted as an absolute measure of a company's intrinsic value.

---

## 5. Important Interpretation Considerations

The analysis should be interpreted with several limitations in mind.

### Historical Data

The conclusions are based on the historical periods available in the dataset. Companies do not necessarily have identical data histories.

For example, most companies have a latest year of 2022, while some companies have data extending to 2023 or ending earlier.

Therefore, comparisons should distinguish between the **latest available observation** and a common reporting year.

### Peer-Based Valuation

The valuation analysis is relative to the selected peer group.

An "undervalued" classification means that the company's calculated valuation measures are relatively lower than the relevant peer benchmarks. It does not, by itself, prove that the company's shares are intrinsically undervalued.

Similarly, an "overvalued" classification indicates a relatively higher valuation compared with the peer benchmark, not necessarily that the market price is incorrect.

### Profitability

A company can have strong gross or operating margins while still having other financial characteristics that affect its overall investment profile.

Profitability should therefore be considered alongside valuation, growth, financial position, cash flows, and industry conditions.

## 6. Recommended Workflow

For users reviewing or updating the workbook, the recommended sequence is:

**1. Review Business Questions**
Understand what the project is designed to answer.

**2. Review Data**
Check the source data, company names, years, margins, and valuation ratios.

**3. Review Analysis**
Examine the calculations, summary tables, and charts generated from the data.

**4. Review Interpretation**
Read the explanation of what the analytical results mean.

**5. Review Executive Summary**
Obtain the main conclusions from the analysis.

**6. Review Dashboard**
Use the visual presentation to communicate the key results quickly.

---

## 7. Updating the Project

When new financial-year data becomes available:

1. Add the new observations to the **Data** sheet.
2. Ensure company names and column structures remain consistent.
3. Confirm that the latest-year calculations identify the new reporting period correctly.
4. Refresh the relevant PivotTables and charts.
5. Review the valuation classifications.
6. Recheck the interpretation and executive summary.
7. Review the Dashboard for consistency with the updated analysis.

Do not rely on a refreshed chart alone. The underlying calculations and classifications should also be checked.

---

## 8. Project Output

The completed workbook provides a structured financial-analysis framework that moves from:

**Raw Data → Business Questions → Analytical Calculations → Interpretation → Executive Summary → Dashboard**

This structure separates the source data from the analysis and presentation layers, making the project easier to review, explain, and update.


## 9. Intended Use

This workbook is intended for financial analysis, peer comparison, management presentation, academic/project evaluation, and investment-analysis research.

The results are analytical outputs based on the data and methodology contained in the workbook. They should not be interpreted as standalone investment advice or as a definitive measure of the intrinsic value of any company.

Interested in financial analysis, valuation, financial modelling, or building practical Excel and Power BI solutions?
Let's connect for more projects in financial analysis.
Contact: wisdzoagbe@gmail.com
