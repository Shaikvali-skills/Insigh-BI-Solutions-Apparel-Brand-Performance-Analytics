# Insigh BI Solutions - Apparel Brand Performance Analytics

An interactive, cloud-connected Business Intelligence solution engineered in Power BI to evaluate inventory diversity, retail pricing strategies, discount impact, and profit margins across a diverse portfolio of apparel brands.

## 🔗 Live Interactive Dashboard
[View Interactive Power BI Dashboard](Insert_Your_Power_BI_Publish_Link_Here)

---

## 📌 Project Overview
Navigating modern retail data requires deep visibility into massive, scalable datasets. This project connects directly to an **Azure Cloud Data Platform** to ingest historical apparel metrics, analyzing pricing hierarchies, promotional discount dependencies, and catalog saturation levels across premium and economy market brands in near real-time.

### Key Features:
* **Cloud Data Architecture:** Fueled by a robust Azure data stream for seamless enterprise scaling and reliable refreshes.
* **Assortment Distribution Mapping:** Quantifies individual brand variety count relative to the total apparel portfolio.
* **Pricing Tier Stratification:** Segments premium market entries from low-margin, high-discount retail operators.
* **Profit Margin Auditing:** Visualizes peak average profit baselines alongside low-margin warning segments to simplify stock optimization decisions.

---

## 📊 Dashboard Architecture & Views

### 1. Welcome Splash Canvas
A high-fidelity landing plane establishing corporate brand alignment for an "Exclusive Men's Collection" lookup list.

![Men's Collection Splash Page](Screenshot%202026-06-23%20165841.png)

### 2. Brands Analysis Interface
An elegant gold-on-navy analytical command workspace exploring multi-tiered brand performance data.

![Brands Performance Analysis](Screenshot%202026-06-23%20165851.png)

#### Key Metric Breakdowns Captured:
* **Catalog Variety Leaders:** `The Indian Garage Co` leads stock keeping depth with **51 varieties (22.87%)**, while `SNITCH` sits at **36 varieties (16.14%)**.
* **Premium Pricing Tiers:** Top average sales prices are held by `Armani Exchange (6.1K)` and `Brooks Brothers (5.1K)`.
* **Discount Margin Exposures:** Highlights heavy promotional plays with average discount rates stretching up to **72%**.
* **Profit Variance Analysis:** Maps standard top-tier profitability targets holding flat at **17.00%** against underperforming baseline clusters leaking down to **2.00%**.

---

## 🛠️ Technical Stack & Cloud Architecture
* **BI Platform:** Power BI Desktop / Power BI Service
* **Cloud Infrastructure & Data Source:** **Azure SQL Database / Azure Data Lake**
* **Data Prep & ETL:** Power Query (orchestrating cloud data transformations, type casting, and schema enforcement)
* **Data Schema Context:** Cloud-hosted relational transactional nodes tracking product parameters.

### Core Data Fields Evaluated:
* `Brand` (Categorical naming identifiers)
* `Cost Price` / `Marked Price` / `Sales Price`
* `Discount %`
* `Profit %`
* `Title` (Product classification tracking)

---

## 🚀 Local Setup & Cloud Connection
1. Clone this repository to your local directory.
2. Open the `Insigh_BI_Brands_Project.pbix` file using **Power BI Desktop**.
3. To sync live data, navigate to **Home > Data source settings**.
4. Change the source path to point to your deployed **Azure SQL Server/Database** instance.
5. Provide your Azure credentials (or OAuth2 authorization tokens) and click **Refresh** to synchronize the cloud semantic structure.
