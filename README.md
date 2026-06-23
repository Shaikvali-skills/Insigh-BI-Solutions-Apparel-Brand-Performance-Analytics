# Insigh BI Solutions - Apparel Brand Performance Analytics

An interactive Business Intelligence solution engineered in Power BI to evaluate inventory diversity, retail pricing strategies, discount impact, and profit margins across a diverse portfolio of apparel brands.

## 🔗 Live Interactive Dashboard
[View Interactive Power BI Dashboard](https://app.powerbi.com/groups/b358022c-4af9-4f76-8416-30cbc584469b/reports/259a081f-8230-4faa-aaaa-67bac4c7fe88/31d7d7f6eeed6714331b?experience=power-bi)

---

## 📌 Project Overview
Navigating retail data requires deep visibility into product catalogs and financial performance metrics. This project breaks down transactional apparel metrics to analyze pricing hierarchies, promotional discount dependencies, and catalog saturation levels across premium and economy market brands.

### Key Features:
* **Assortment Distribution Mapping:** Quantifies individual brand variety count relative to the total apparel portfolio.
* **Pricing Tier Stratification:** Segments premium market entries from low-margin, high-discount retail operators.
* **Profit Margin Auditing:** Visualizes peak average profit baselines alongside low-margin warning segments to simplify stock optimization decisions.

---

## 📊 Dashboard Architecture & Views

### 1. Welcome Splash Canvas
A high-fidelity landing plane establishing corporate brand alignment for an "Exclusive Men's Collection" lookup list.

![Men's Collection Splash Page](Splash_Page.png)

### 2. Brands Analysis Interface
An elegant gold-on-navy analytical command workspace exploring multi-tiered brand performance data.

![Brands Performance Analysis](Brands_Dashboard.png)

#### Key Metric Breakdowns Captured:
* **Catalog Variety Leaders:** `The Indian Garage Co` leads stock keeping depth with **51 varieties (22.87%)**, while `SNITCH` sits at **36 varieties (16.14%)**.
* **Premium Pricing Tiers:** Top average sales prices are held by `Armani Exchange (6.1K)` and `Brooks Brothers (5.1K)`.
* **Discount Margin Exposures:** Highlights heavy promotional plays with average discount rates stretching up to **72%**.
* **Profit Variance Analysis:** Maps standard top-tier profitability targets holding flat at **17.00%** against underperforming baseline clusters leaking down to **2.00%**.

---

## 🛠️ Technical Stack & Data Model
* **BI Platform:** Power BI Desktop
* **Data Prep & ETL:** Power Query
* **Data Schema Context:** Built around unified transactional nodes containing structural product variables.

### Core Data Fields Evaluated:
* `Brand` (Categorical naming identifiers)
* `Cost Price` / `Marked Price` / `Sales Price`
* `Discount %`
* `Profit %`
* `Title` (Product classification tracking)

---

## 🚀 Local Setup Instructions
1. Clone this repository to your local directory.
2. Open the `Insigh_BI_Brands_Project.pbix` file using **Power BI Desktop**.
3. Place your raw dataset files into your target storage path or update your source configurations.
4. Click **Refresh** to synchronize the semantic structure.
