# 🛍️ Myntra Enterprise Fashion Supply Chain & Inventory Audit (EORS Simulation)

## 📌 Project Overview & Purpose
During massive e-commerce festive events like Myntra's **End of Reason Sale (EORS)**, supply chains experience severe spikes in user traffic, transaction volume, and operational strain. 

The purpose of this project is to build an **enterprise-scale data audit and simulation portfolio pipeline** modeling **25,000 SKU variants** across real fashion brands (*Mast & Harbour*, *Roadster*, *House of Pataudi*, *Anouk*, *Sangria*, etc.). The goal is to audit inventory vulnerability, regional fulfillment bottlenecks, and logistics health under high-stress festive conditions.

---

## 🏗️ Architecture & Deliverables
1. **Python Simulation Engine (`myntra_enterprise_simulation.py`):** Generates 25,000 structured SKU variant records incorporating brand portfolios, category matrices, stock statuses, return rates, and fulfillment metrics.
2. **Multi-Tab Excel Strategy Model (`myntra_eors_strategy_report.xlsx`):** A professional workbook structured into four core tabs:
   * **Executive_Summary:** Category-level performance aggregations tracking critical stockout rates and daily sell-through velocities.
   * **Regional_Hub_Telemetry:** Operational breakdown across four regional distribution hubs (`WH-North`, `WH-South`, `WH-West`, `WH-Central`).
   * **Strategic_Solutions:** A comprehensive executive matrix outlining root problems and engineering solutions.
   * **Raw_Enterprise_Data:** The complete 25,000-row telemetry dataset.

---

## 🔍 Key Findings & Analytical Insights
* **The Stockout Crisis:** Across the 25,000 SKUs, **48.16% of variants** hit a **Critical Stockout** status during the EORS simulation, revealing that festive demand heavily outpaced initial safety stock allocations.
* **Top Impacted Brands:** High-volume labels like **Mast & Harbour** (1,640 critical stockouts) and **Roadster** (1,155 stockouts) absorbed the heaviest inventory depletion.
* **Category Vulnerability:** **Denim Jeans** (48.8%) and **Ethnic Kurtas** (48.7%) recorded the highest risk of running out of stock.
* **Fulfillment SLA Resilience:** Despite severe inventory bottlenecks, regional distribution centers maintained a strong **~82% dispatch SLA compliance rate**, led by **WH-North (Delhi)** at 82.88%.

---

## 📊 Visual Telemetry & Analytics

### 1. Inventory Stock Status Breakdown by Fashion Category
![Category Stock Status Breakdown](detailed_category_status_chart.png)
* **Analysis:** Across all major categories, Critical Stockouts consistently consume ~46% to 49% of total variant stock, exposing widespread safety stock deficits.

### 2. Top Brands Impacted by Critical Stockouts
![Top Brands Stockout Chart](detailed_brand_stockout_chart.png)
* **Analysis:** Fast-fashion and mass-market private labels absorbed the highest volume of depletion under peak surge traffic.

---

## 🛠️ Strategic Solutions & Engineering Recommendations
To mitigate these operational bottlenecks in future sale events, the following solutions are proposed:
1. **Dynamic Safety Stock & Predictive Allocation Models:** Replace static pre-season planning with machine learning models adjusting buffers 2–4 weeks prior to EORS based on real-time wishlist and cart velocity.
2. **Multi-Echelon Inventory Optimization (MEIO):** Deploy algorithms to dynamically rebalance inventory across regional fulfillment hubs in real time and establish cross-docking centers closer to Tier-2/Tier-3 cities.
3. **Intelligent Reverse Logistics:** Introduce automated grading and AI-powered visual quality checks at fulfillment returns docks to restock unopened or undamaged items within 4 hours (mitigating the ~31% return rate pressure).
4. **Supplier Agility & Fast Replenishment:** Secure raw material fabric capacity 60 days prior to EORS with key vendors to enable 5-to-7 day rapid re-order turnarounds mid-sale.

---

## 📁 Download Executive Reports
* [Download Multi-Tab Executive Strategy Report (.xlsx)](myntra_eors_strategy_report.xlsx)
* [Download Brand-Level Audit Report (.xlsx)](myntra_brand_audit_report.xlsx)
