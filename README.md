# 📈 Acme Electronics Sales & Profitability Intelligence (2014–2018)
### *A Data-Driven Evaluation of Growth, Efficiency & Market Optimization in the U.S. Consumer Electronics Sector*

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)
![SQL](https://img.shields.io/badge/Database-MySQL-orange?logo=mysql)
![Analytics](https://img.shields.io/badge/Focus-Business%20Intelligence-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🏢 Company Background

**Acme Electronics**, founded in **2010**, is a U.S.-based electronics manufacturer and distributor specializing in **consumer devices**, **home appliances**, and **tech accessories**.  
Operating through **Wholesale**, **Distributor**, and **Export** channels, Acme aims to balance **steady revenue growth** with **profitability and market diversification**.

This project analyzes **2014–2018 U.S. sales data** to uncover revenue drivers, margin patterns, and channel efficiency.  
Insights powered an **EDA report in Python** and a **Power BI executive dashboard**.

---

## 🔎 Problem Statement

Despite stable revenue, Acme’s **profit margins** and **channel diversity** have plateaued.  
This project aims to deliver a unified analytical framework to:

- Identify **top-performing products, channels, and regions**.
- Understand **seasonal and outlier trends** impacting growth.
- Inform **pricing, promotion, and expansion strategies**.

---

## 🎯 Project Objectives

| Strategic Pillar | Objective (OKR) | Key Metrics (KPIs) |
|------------------|-----------------|--------------------|
| **Revenue Growth** | Expand sales volume and product penetration | Total Revenue, Order Volume, Top 10 Product Revenue |
| **Profitability** | Improve unit economics and operational efficiency | Profit Margin %, Avg. Profit per Product |
| **Channel Diversification** | Reduce dependency on domestic wholesale | Channel Mix %, Export Contribution, Regional Share |

---

## 🌟 North Star Metric (NSM)

> **Profit Margin %** – The single most critical measure of sustainable growth.  
A rising margin signals **pricing discipline**, **operational efficiency**, and **healthy scaling**.

---

## 🧠 Analytical Framework

This analysis was executed in two complementary stages:

1. **Exploratory Data Analysis (Python)** – uncovering patterns, correlations, and revenue drivers.  
2. **Power BI Dashboard Suite** – transforming findings into actionable business intelligence.

---

## 🧮 Exploratory Data Analysis (EDA)

The Python-based EDA notebook dives deep into Acme’s sales data from 2014–2018.  
You can explore the full analysis here ➡️ [View Python Notebook](https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/EDA%20and%20Performance%20Analysis%20.ipynb)

---

### 📅 Monthly Sales Trend Over Time
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/monthly%20sales%20trend%20over%20time.png" alt="Monthly Sales Trend" width="80%">
</p>

**Insights:**  
- Revenue fluctuates between **$24M–$26M**, peaking in **May–June**.  
- A sharp dip in **early 2017** suggests market or campaign disruptions.  
- Overall stability highlights a reliable seasonal sales pattern.

---

### 💰 Top 10 Products by Revenue
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/top%2010%20products%20by%20revenue.png" alt="Top Products by Revenue" width="80%">
</p>

**Insights:**  
- **Products 26 and 25** lead with **$118M and $110M** respectively.  
- Mid-tier performers range **$68M–$75M**, lower group **$52M–$57M**.  
- Target mid-range products for margin and volume uplift initiatives.

---

### 💸 Top 10 Products by Average Profit Margin
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/top%2010%20products%20by%20average%20profit%20margin.png" alt="Top Products by Profit Margin" width="80%">
</p>

**Insights:**  
- **Products 18 and 28** yield the highest margins (**8.0–8.3K**).  
- **Products 12, 26, 21** cluster around **7.7–7.8K**—good uplift potential.  
- Replicate pricing and cost tactics from top performers across product tiers.

---

### 🧾 Sales by Channel
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/sales%20by%20channel.png" alt="Sales by Channel" width="80%">
</p>

**Insights:**  
- **Wholesale** contributes **54%**, **Distributors 31%**, **Exports 15%**.  
- Revenue is concentrated domestically — diversification recommended.  
- Expand exports and optimize distributor contracts for growth.

---

### 💳 Average Order Value (AOV) Distribution
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/AOV%20distribution.png" alt="AOV Distribution" width="80%">
</p>

**Insights:**  
- Majority of orders fall between **$20K–$120K**, peaking near **$50K–$60K**.  
- Few high-value orders (**$400K–$500K**) drive disproportionate revenue.  
- Strategy: boost medium-ticket transactions for balanced growth.

---

### 🗺️ Total Sales by U.S. Region
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/Total%20sales%20by%20US%20region.png" alt="Regional Sales" width="80%">
</p>

**Insights:**  
- **West** leads (~**$360M**, 35%) followed by **South & Midwest** (~**$320M** each).  
- **Northeast** lags (~**$210M**), offering investment potential.  
- Prioritize regional promotions in underpenetrated zones.

---

### 📍 Top 10 States by Revenue and Order Count 
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/top%20and%20bottom%2010%20customers%20by%20revenue.png" alt="Top States" width="80%">
</p>

**Insights:**  
- **California** dominates with **$230M revenue** and **7,500+ orders**.  
- **Illinois, Florida, Texas** form second tier (~**$85M–$110M**).  
- Scale mid-tier states via regional incentives and brand visibility.

---

### 🧩 Revenue vs Profit Margin Correlation
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/revenue%20vs%20profit%20margin.png" alt="Revenue vs Profit Margin" width="80%">
</p>

**Insights:**  
- Strong correlation (**r = 0.87**) between revenue and profit.  
- Margins remain consistent (~36–40%) across high-revenue customers.  
- Small accounts show higher variance—target pricing stability.

---

### 🔗 Correlation Heatmap
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/insights/correlation%20matrix.png" alt="Correlation Heatmap" width="80%">
</p>

**Insights:**  
- **Revenue ↔ Profit (0.87)** indicates tight linkage.  
- **Unit Price ↔ Revenue (0.91)** confirms pricing as primary driver.  
- **Quantity** correlations are minimal—volume secondary to price efficiency.

---

## 📊 Power BI Dashboard Suite

The interactive **Power BI dashboard** translates EDA findings into business-ready intelligence.  
It consists of three interconnected pages designed for executives, product teams, and sales strategists.

---

### 1️⃣ Executive Overview & Trends
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/Dashboard/Performance%20Summary%20.png" alt="Performance Summary Dashboard" width="80%">
</p>

**Highlights:**  
- Total Revenue: **$1.2B**, Profit: **$462M**, Margin: **37.4%**  
- Reveals seasonality patterns and margin consistency.  
- Supports leadership in revenue forecasting and budgeting.

---

### 2️⃣ Product & Channel Performance
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/Dashboard/Customer%20Segmentation%20.png" alt="Revenue Scenarios Dashboard" width="80%">
</p>

**Highlights:**  
- **Products 26 & 25** lead sales; **Products 9 & 30** dominate margins.  
- Channel mix breakdown: **Wholesale (54%)**, **Distributor (31%)**, **Export (15%)**.  
- Strategic product positioning matrix reveals profitability clusters.

---

### 3️⃣ Geographic & Customer Insights
<p align="center">
  <img src="https://github.com/Manya-singh2001/Acme-Sales-Evaluation/blob/main/Dashboard/Revenue%20Scenarios%20.png" alt="Customer Segmentation Dashboard" width="80%">
</p>

**Highlights:**  
- **California** drives **19.5% of revenue ($228.8M)**.  
- **West region** delivers top profit margin (37.5%).  
- Identifies top and bottom 5 states/customers for growth targeting.

---

## 💡 Key Takeaways

| Focus Area | Insight | Recommended Action |
|-------------|----------|--------------------|
| **Revenue Stability** | Steady $23–26M/month pattern | Align supply chain & inventory with seasonal peaks |
| **Channel Mix** | 54% wholesale dependency | Expand export distribution & digital B2B sales |
| **Product Leaders** | Top 3 drive 40%+ of sales | Invest in mid-tier growth & bundling |
| **Regional Spread** | West dominates, Northeast lags | Target underperforming regions |
| **Margin Range** | 18–60% variation | Apply best-practice pricing from top-margin SKUs |

---

## 🧭 Strategic Recommendations

1. **Outlier Strategy:** Separate promotional/bulk SKUs in margin analysis.  
2. **Margin Uplift:** Transfer pricing learnings from top performers to weaker tiers.  
3. **Export Expansion:** Strengthen partnerships in overseas markets.  
4. **Seasonal Optimization:** Focus marketing during **January troughs** and **May–June peaks**.  
5. **Dashboard Automation:** Create aggregated Power BI tables for product, time, and channel performance.

---



## 👩‍💼 Author

**Manya Singh**  
*Data Analyst | Business Intelligence | SQL | Power BI | Data Storytelling*  
📍 India  
🔗 [LinkedIn](YOUR_LINKEDIN_URL)  
📧 manyasinghsingh16699@gmail.com

