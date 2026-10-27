# 📦 Supply Chain & Fulfillment Performance Analytics Dashboard

## 📌 Project Overview
Designed to evaluate supply chain efficiency, analyze order fulfillment timelines, track shipping risk factors, and optimize regional order profit margins. This project utilizes the DataCo Smart Supply Chain dataset processed via Python (Pandas) for data transformation, MySQL for relational querying (`cleaned_supply_chain_data`), and Power BI for executive dashboarding.

## ⚙️ Analytical Workflow
* **Data Cleaning & Preprocessing:** Resolved missing key values, standardized order date structures, and calculated profit margins per order using Python (Pandas).
* **ETL & Database Querying:** Created relational tables in MySQL Workbench (`cleaned_supply_chain_data`) to query fulfillment delays, high-risk delivery regions, and order item volumes.
* **DAX & KPI Development:** Modeled key DAX measures in Power BI for Total Revenue, Total Profit, Late Delivery Rate, and Average Shipping Delay.
* **Interactive Dashboard Construction:** Built visual charts for shipping mode distributions, regional profit contributions, and order status tracking.

## 🛠️ Tools & Technologies Used
* **Dataset:** DataCo Smart Supply Chain Dataset (`DataCoSupplyChainDataset`)
* **Programming Language:** Python (Pandas, NumPy, Matplotlib)
* **Database & Querying:** MySQL Workbench (`cleaned_supply_chain_data`, `supply_chain_queries.sql`)
* **Data Visualization:** Power BI (`Supply Chain Dashboard`)
* **Development Environment:** Jupyter Notebook

## 📁 Repository & Folder Structure
```text
Supply_Chain_Analysis/
├── data/
│   ├── raw/
│   │   └── DataCoSupplyChainDataset.csv
│   └── cleaned/
│       └── cleaned_supply_chain_data.csv
├── sql/
│   └── supply_chain_queries.sql
├── Supply_Chain_Analysis.ipynb
├── Supply Chain Dashboard.png
└── README.md
```

## 📊 Dashboard Preview
## 📈 Impact & Core Results
Order Profitability: Isolated key high-profit product categories and mapped loss-making regional shipping lanes.

Fulfillment Risks: Evaluated late delivery frequencies across standard vs. express shipping methods to identify logistics bottlenecks.

Regional Distribution: Analyzed global order volumes to optimize warehouse stock allocation and reduce order cycle times.

## 🏁 Final Conclusion
Optimizing inventory allocation near high-volume customer centers and renegotiating logistics carrier contracts for high-delay shipping modes will significantly lower fulfillment risks and maximize overall supply chain profitability.
