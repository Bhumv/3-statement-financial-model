# 3-statement-financial-model
5-year integrated 3-statement financial model with historical analysis, forecast financial statements, working capital, PP&E, debt and equity schedules, and Best/Base/Worst case scenario analysis built in Excel.

## 🎯 Project Overview

Developed an **integrated three-statement financial model** using historical financial data from **2014–2016** to forecast financial performance through **2021**.

The model is designed to demonstrate how operating assumptions flow through the **Income Statement, Balance Sheet, and Cash Flow Statement**, while supporting analysis of profitability, liquidity, leverage, working capital, and cash generation.

| | |
|---|---|
| **Historical Period** | 2014–2016 |
| **Forecast Period** | 2017–2021 |
| **Currency** | $ in millions |
| **Tool** | Microsoft Excel |

---

## 🎯 Objective

The objective of the model is to build a **fully linked financial forecasting framework** rather than treating each financial statement independently.

The project focuses on:

- Forecasting financial performance using operating drivers
- Integrating the three primary financial statements
- Modelling working capital and supporting schedules
- Assessing different operating scenarios
- Evaluating financial performance through key ratios
- Validating the integrity of the model through reconciliation checks
- Presenting key outputs through a concise dashboard

---

## 📐 Model Architecture

The workbook follows a structured modelling flow:

```text
Historical Financial Data
          ↓
Operating Assumptions & Scenarios
          ↓
   Income Statement
          ↓
 Supporting Schedules
   ┌──────┼──────┐
   ↓      ↓      ↓
  PP&E   Debt   Equity
          ↓
    Balance Sheet
          ↓
  Cash Flow Statement
          ↓
   Financial Analysis
          ↓
       Dashboard
```

The supporting schedules feed the primary statements to maintain consistency across the model.

---

## 📑 Financial Statements

### Income Statement

Historical and forecast P&L covering:

- Revenue
- Cost of Goods Sold
- Gross Profit
- Operating Expenses
- EBITDA
- Depreciation & Amortization
- EBIT
- Interest Expense
- EBT
- Taxes
- Net Income

The forecast is driven by operating assumptions and can be switched between Best, Base, and Worst Case scenarios.

### Balance Sheet

The model forecasts key operating, investing, and financing accounts, including:

- Trade Receivables
- Inventory
- PP&E
- Cash
- Other Assets
- Trade Payables
- Provisions
- Financial Liabilities
- Other Liabilities
- Equity

Working-capital assumptions include **DSO, DIO, and DPO**.

### Cash Flow Statement

The Cash Flow Statement integrates:

**Operating Activities**
- EBITDA
- Interest
- Taxes
- Working-capital movements
- Changes in other operating assets and liabilities

**Investing Activities**
- Capital expenditure

**Financing Activities**
- Financial liabilities / borrowings
- Equity movements
- Dividends

Ending cash is linked to the Balance Sheet to maintain three-statement integration.

---

## 🛠️ Supporting Schedules

### 🏗️ PP&E Schedule

Models the fixed-asset roll-forward:

**Beginning PP&E + Capex − D&A = Ending PP&E**

### 💳 Financial Liabilities Schedule

Includes:

- Beginning debt
- New debt
- Principal repayments
- Ending debt
- Interest expense
- Repayment schedule
- Residual debt

### 📈 Equity Schedule

Includes:

- Beginning equity
- Capital additions
- Net income
- Dividends
- Ending equity

### 💰 Cash Schedule

Links operating, investing, and financing movements to:

**Net Cash Flow → Ending Cash**

---

## 🎛️ Scenario Analysis

The model includes a dynamic scenario selector for:

| Scenario | Description |
|---|---|
| 🟢 **Best Case** | More favorable operating assumptions |
| 🔵 **Base Case** | Central operating assumptions |
| 🔴 **Worst Case** | More conservative operating assumptions |

Scenario assumptions are applied to key forecast drivers including:

- Revenue Growth
- COGS as % of Revenue
- Operating Expenses as % of Revenue

This allows the model to assess how changes in operating assumptions flow through to **revenue, EBITDA, net income, and cash generation**.

---

## 📊 Financial Analysis

A dedicated Financial Analysis section evaluates the forecast using:

### Growth
- Revenue Growth
- EBITDA Growth
- Net Income Growth

### Profitability
- Gross Margin
- EBITDA Margin
- EBIT Margin
- Net Profit Margin

### Liquidity & Leverage
- Current Ratio
- Debt / Equity
- Interest Coverage

### Efficiency
- Cash Conversion Cycle

**Cash Conversion Cycle = DSO + DIO − DPO**

This analysis provides a view of the company's operating performance beyond the underlying financial statements.

---

## 📌 Dashboard

The dashboard summarizes the model's key forecast outputs through:

### Key Performance Indicators
- 2021 Revenue
- 2021 EBITDA
- 2021 Net Income
- 2021 Free Cash Flow

### Visual Analysis
- Revenue & EBITDA Trend
- Free Cash Flow Trend

The dashboard provides a concise view of the model's historical-to-forecast trajectory and key financial outputs.

---

## ✅ Model Validation

The workbook includes reconciliation checks to monitor model integrity, including:

- **Balance Sheet Check:** Assets = Liabilities + Equity
- **Cash Check:** Cash Flow Statement ending cash = Balance Sheet cash
- **Beginning Cash Check:** Current-year beginning cash = prior-year ending cash
- **PP&E Check:** PP&E roll-forward reconciles to ending PP&E
- **Debt Check:** Debt schedule reconciles to Balance Sheet financial liabilities
- **Historical Cash Flow Check:** Historical cash movements reconcile to ending cash

These checks are designed to identify broken links or inconsistencies before relying on model outputs.

---

## 🧠 Key Skills Demonstrated

`Three-Statement Modelling` · `Financial Forecasting` · `Scenario Analysis` · `Working Capital Modelling` · `Cash Flow Modelling` · `Ratio Analysis` · `PP&E Modelling` · `Debt Modelling` · `Excel Dashboards` · `Model Validation`

---

## 💼 Tool

**Microsoft Excel**

---

## 🚀 How to Review the Model

For the quickest overview:

1. Start with the **Dashboard** for key outputs and trends.
2. Review **Financial Analysis** for profitability, liquidity, leverage, and efficiency metrics.
3. Review the **P&L, Balance Sheet, and Cash Flow Statement** to understand the integrated forecast.
4. Use the **scenario selector** to assess alternative operating assumptions.
5. Review the supporting schedules to understand how PP&E, debt, equity, and cash are modelled.
6. Review the **model checks** to confirm that the statements reconcile.

---

## 📁 Repository Structure

```text
5-Year-3-Statement-Financial-Model/
│
├── 5-Year_3-Statement_Financial_Model.xlsx
└── README.md
```

---

## ⭐ Project Summary

This project demonstrates the construction of an **integrated five-year financial forecast** from historical financial information.

It combines financial statement modelling, operating assumptions, supporting schedules, scenario analysis, ratio analysis, cash-flow forecasting, model validation, and dashboard reporting into a single Excel-based framework.

The project is intended as a practical demonstration of **financial modelling, financial analysis, and Excel skills**.

