# 📊 Investment Analysis Dashboard | Power BI

<p align="center">

### Turning Investor Survey Data into Actionable Business Insights

**Cognifyz Technologies Internship Project**

</p>

---

## 📌 Project Overview

This project analyzes investor survey data to understand **investment behavior, financial objectives, investment preferences, monitoring habits, reasons for investment, and sources of investment information**.

The project was developed using **Microsoft Power BI** to transform raw investor data into an interactive Business Intelligence dashboard.

The analysis covers **40 investors** and is organized into 7 analytical tasks, followed by a consolidated interactive dashboard.

---

# 🎯 Business Problem

Investment-related businesses and financial advisors need to understand:

- Who their investors are
- Which investment avenues they prefer
- What motivates their investment decisions
- What financial goals investors are targeting
- How long investors plan to hold investments
- How frequently investors monitor their investments
- Where investors obtain financial information
- Whether investment behavior differs across demographic groups

### Business Question

> **How can investor survey data be transformed into meaningful insights that help understand investor preferences, objectives, behavior, and information sources?**

This project addresses the problem by building an interactive Power BI solution that converts raw survey responses into **KPIs, comparative analysis, distributions, and business insights**.

---

# 🧩 Project Objectives

The project was divided into 7 analytical tasks:

| Task | Objective |
|---|---|
| Task 1 | Data Exploration & Summary |
| Task 2 | Gender-Based Investment Analysis |
| Task 3 | Investment Objective Analysis |
| Task 4 | Investment Duration & Monitoring Analysis |
| Task 5 | Investment Reasons Analysis |
| Task 6 | Investment Information Source Analysis |
| Task 7 | Consolidated Investment Analysis Dashboard |

---

# 🛠️ Tools & Technologies

| Technology | Usage |
|---|---|
| **Microsoft Power BI** | Dashboard development & visualization |
| **Power Query** | Data transformation and preparation |
| **DAX** | KPI and analytical measures |
| **Microsoft Excel** | Source dataset |
| **GitHub** | Version control and project documentation |

---

# 📊 Dataset Overview

The dataset contains information about **40 investors**.

### Major Data Categories

- Gender
- Age
- Investment Avenues
- Mutual Funds
- Equity Market
- Government Bonds
- Fixed Deposits
- PPF
- Investment Objective
- Savings Objectives
- Investment Duration
- Investment Monitoring Frequency
- Expected Returns
- Reasons for Investment
- Sources of Investment Information

---

# 📈 Key KPIs

| KPI | Value |
|---|---:|
| 👥 Total Investors | **40** |
| 🎂 Average Investor Age | **27.80 years** |
| 💰 Investment Participation | **92.50%** |
| 📈 Stock Market Participation | **87.50%** |
| 👨 Male Investors | **25** |
| 👩 Female Investors | **15** |

---

# 🔎 Task 1 — Data Exploration & Summary

## Business Problem

Before making investment-related decisions, businesses need a clear understanding of the investor population and their overall investment behavior.

## Analysis Performed

- Investor demographics
- Average investor age
- Investment participation
- Stock market participation
- Investment avenue distribution
- Savings objective distribution

## Dashboard

![Task 1 - Data Exploration & Summary](All%20Dashboards/Task%201.png)

## Key Insights

- The dataset contains **40 investors**.
- The average investor age is **27.80 years**.
- **92.50%** of investors reported investment avenues.
- **87.50%** reported stock market participation.
- **Mutual Funds** are the most common investment avenue with **18 investors (45%)**.
- **Equity** is selected by **10 investors (25%)**.
- **Fixed Deposits** are selected by **9 investors (22.5%)**.
- **PPF** is selected by **3 investors (7.5%)**.
- **Retirement Planning** is the most common savings objective with **24 investors (60%)**.

---

# 👥 Task 2 — Gender-Based Investment Analysis

## Business Problem

Investment businesses may need to understand whether investment choices and investment scores differ across demographic groups.

## Analysis Performed

- Investor distribution by gender
- Investment avenue by gender
- Average Mutual Fund score by gender
- Average Equity score by gender
- Average Government Bond score by gender

## Dashboard

![Task 2 - Gender-Based Analysis](All%20Dashboards/Task%202.png)

## Key Insights

### Investor Distribution

- **25 Male investors**
- **15 Female investors**

### Average Investment Scores

| Investment Type | Male | Female |
|---|---:|---:|
| Mutual Funds | 2.44 | 2.73 |
| Equity | 3.56 | 3.33 |
| Government Bonds | 4.84 | 4.33 |

### Investment Avenue Distribution

The dashboard also compares Mutual Funds, Equity, Fixed Deposits, and PPF across male and female investors.

> **Note:** The numerical investment fields are treated as investment scores. The analysis therefore reports average scores rather than interpreting them as percentages.

---

# 🎯 Task 3 — Investment Objective Analysis

## Business Problem

Different investors have different financial objectives. Understanding the relationship between objectives and investment avenues can help businesses better understand investment behavior.

## Analysis Performed

- Investment objective distribution
- Savings objective distribution
- Investment avenue by objective
- Objective × investment avenue matrix

## Dashboard

![Task 3 - Objective Analysis](All%20Dashboards/Task%203.png)

## Key Insights

### Investment Objectives

| Objective | Investors |
|---|---:|
| Capital Appreciation | **26** |
| Growth | **11** |
| Income | **3** |

### Investment Avenue by Objective

| Objective | Equity | Fixed Deposits | Mutual Funds | PPF |
|---|---:|---:|---:|---:|
| Capital Appreciation | 6 | 6 | 13 | 1 |
| Growth | 2 | 3 | 4 | 2 |
| Income | 2 | 0 | 1 | 0 |

### Insight

**Capital Appreciation** is the largest investment objective group, with Mutual Funds being the most frequently selected avenue within this group.

---

# ⏳ Task 4 — Investment Duration & Monitoring Analysis

## Business Problem

Investment businesses need to understand how long investors intend to hold investments and how frequently they monitor their portfolios.

## Analysis Performed

- Investment duration distribution
- Investment avenue by duration
- Monitoring frequency
- Investment avenue by monitoring frequency
- Expected return distribution

## Dashboard

![Task 4 - Duration & Monitoring Analysis](All%20Dashboards/Task%204.png)

## Key Insights

### Investment Duration

| Duration | Investors |
|---|---:|
| Less than 1 year | 2 |
| 1–3 years | 18 |
| 3–5 years | **19** |
| More than 5 years | 1 |

### Monitoring Frequency

| Frequency | Investors |
|---|---:|
| Monthly | **29** |
| Weekly | 7 |
| Daily | 4 |

### Expected Returns

| Expected Return | Investors |
|---|---:|
| 20%–30% | **32** |
| 30%–40% | 5 |
| 10%–20% | 3 |

### Insight

The largest group of investors reports a **3–5 year investment duration**, while **monthly monitoring** is the most common monitoring behavior.

---

# 💡 Task 5 — Investment Reasons Analysis

## Business Problem

Understanding why investors select particular investment products can help financial businesses better understand investor motivations.

## Analysis Performed

- Reasons for Equity investment
- Reasons for Mutual Fund investment
- Reasons for Bond investment
- Reasons for Fixed Deposit investment

## Dashboard

![Task 5 - Investment Reasons](All%20Dashboards/Task%205.png)

## Key Insights

### Equity

| Reason | Investors |
|---|---:|
| Capital Appreciation | **30** |
| Dividend | 8 |
| Liquidity | 2 |

### Mutual Funds

| Reason | Investors |
|---|---:|
| Better Returns | **24** |
| Fund Diversification | 13 |
| Tax Benefits | 3 |

### Bonds

| Reason | Investors |
|---|---:|
| Assured Returns | **26** |
| Safe Investment | 13 |
| Tax Incentives | 1 |

### Fixed Deposits

| Reason | Investors |
|---|---:|
| Risk Free | **19** |
| Fixed Returns | 18 |
| High Interest Rates | 3 |

### Insight

Different investment products show different dominant reasons:

- Equity → **Capital Appreciation**
- Mutual Funds → **Better Returns**
- Bonds → **Assured Returns**
- Fixed Deposits → **Risk Free**

---

# 📚 Task 6 — Investment Information Source Analysis

## Business Problem

Financial businesses need to understand where investors obtain investment-related information in order to understand the information channels used by their target audience.

## Analysis Performed

- Information source distribution
- Information source by gender
- Investment avenue by information source
- Information source share

## Dashboard

![Task 6 - Information Source Analysis](All%20Dashboards/Task%206.png)

## Key Insights

| Information Source | Investors | Share |
|---|---:|---:|
| Financial Consultants | **16** | **40%** |
| Newspapers & Magazines | 14 | 35% |
| Television | 6 | 15% |
| Internet | 4 | 10% |

### Insight

**Financial Consultants** are the most frequently reported information source, followed by **Newspapers & Magazines**.

---

# 🚀 Task 7 — Final Investment Analysis Dashboard

## Business Problem

Individual analyses are useful, but decision-makers need a single dashboard where multiple aspects of investor behavior can be reviewed together.

## Solution

A consolidated interactive Power BI dashboard was created combining:

- Investor demographics
- Investment participation
- Investment avenues
- Investment objectives
- Investment duration
- Monitoring frequency
- Information sources
- Gender-based comparisons

## Dashboard

![Task 7 - Final Investment Analysis Dashboard](All%20Dashboards/Task%207.png)

## Interactive Filters

The final dashboard includes slicers for:

- **Gender**
- **Age**
- **Investment Avenue**
- **Objective**
- **Duration**

These filters allow users to explore different investor segments interactively.

---

# 📌 Overall Business Insights

The complete analysis provides the following high-level observations:

### 1. Strong Investment Participation

**92.50%** of respondents reported investment avenues, indicating that investment participation is high within this sample.

### 2. Mutual Funds Have the Highest Representation

Mutual Funds account for **18 of the 40 investors**, making them the most frequently selected investment avenue in the dataset.

### 3. Retirement Planning Is a Major Savings Objective

**24 investors (60%)** selected Retirement Planning as their savings objective.

### 4. Capital Appreciation Is the Largest Investment Objective

**26 investors** reported Capital Appreciation as their investment objective.

### 5. Medium-Term Investment Horizons Are Common

The **3–5 year** duration group contains **19 investors**, followed by the **1–3 year** group with 18 investors.

### 6. Monthly Monitoring Is Most Common

**29 investors** reported monitoring investments monthly.

### 7. Investment Motivations Differ by Product

The leading reported reasons vary across investment types:

**Equity → Capital Appreciation**  
**Mutual Funds → Better Returns**  
**Bonds → Assured Returns**  
**Fixed Deposits → Risk Free**

### 8. Financial Consultants Are a Major Information Channel

Financial Consultants account for **40%** of the reported information sources.

---

# Author
**Bhavesh Kumbhare**
