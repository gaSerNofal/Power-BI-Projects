# 📊 Power BI Projects Portfolio

> A collection of end-to-end Power BI dashboards covering data transformation, modeling, DAX measures, and interactive visualizations across multiple business domains.

---

## 👤 About

**Author:** Gaser Ashraf Nofal
**Tool:** Microsoft Power BI Desktop & Python
**Topics:** Data Modeling · DAX · Power Query (M) · Star Schema · Interactive Visuals

---

## 📁 Projects Overview

| #   | Project                                             | Domain                  | Data Source                      | Connectivity |
| --- | --------------------------------------------------- | ----------------------- | -------------------------------- | ------------ |
| 1   | [AdventureWorks v1](./AdventureWorks-v1/)           | Sales & Operations      | SQL Server (AdventureWorks)      | Import Mode  |
| 2   | [AdventureWorks v2](./AdventureWorks-v2/)           | Sales & Operations      | SQL Server (AdventureWorks)      | Direct Query |
| 3   | [Airline Delays & Cancellations](./Airline-Delays/) | Operations & Transport  | CSV (Kaggle) + Python Cleaning   | Import Mode  |
| 4   | [Kickstarter Projects](./Kickstarter-Projects/)     | Finance & Marketing     | CSV Files (2016 & 2018 – Kaggle) | Import Mode  |
| 5   | [Top 250 Movies – IMDb](./Top250-Movies-IMDb/)      | Entertainment Analytics | IMDb Dataset                     | Import Mode  |

---

## 🛠️ Skills & Techniques Demonstrated

- ⭐ **Star Schema** data modeling
- 🔗 **Relationships** — active & inactive (USERELATIONSHIP)
- 📅 **Date Table** built with DAX
- 🧮 **DAX Measures** — KPIs, calculated columns, measure tables
- 🔄 **Power Query (M Language)** — data transformation, append, custom columns
- 📊 **Advanced Visuals** — Drill Down, Drill Through, Bookmarks, Synced Slicers, Q&A
- 🧹 **Python** — data cleaning before loading into Power BI (Airline project)
- 📐 **Hierarchies** — Product, Date, Category hierarchies

---

## 📂 Repository Structure

```
Power-BI-Projects/
│
├── README.md                        ← You are here
│
├── AdventureWorks-v1/
│   ├── README.md
│   ├── AdventureWorks_v1.pbix
│   └── screenshots/
│
├── AdventureWorks-v2/
│   ├── README.md
│   ├── AdventureWorks_v2.pbix
│   └── screenshots/
│
├── Airline-Delays/
│   ├── README.md
│   ├── Airline_Delays.pbix
│   ├── Data_Cleaning.ipynb
│   └── screenshots/
│
├── Kickstarter-Projects/
│   ├── README.md
│   ├── Kickstarter.pbix
│   └── screenshots/
│
└── Top250-Movies-IMDb/
    ├── README.md
    ├── Top250_Movies.pbix
    └── screenshots/
```

---

## 🚀 How to Open a Project

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Power-BI-Projects.git
   ```
3. Navigate to any project folder and open the `.pbix` file in Power BI Desktop
4. For the **AdventureWorks** projects, you'll need to update the SQL Server connection to point to your local instance

---

## 📬 Contact

Feel free to connect or reach out if you have feedback or questions!

- GitHub: [@gaSerNofal](https://github.com/gaSerNofal)
- LinkedIn: [Gaser Nofal](https://linkedin.com/in/gaser-nofal)
