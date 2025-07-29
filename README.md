# Maximo Asset Work Order Analysis – Tableau Story

This project showcases a simulated enterprise-level Tableau solution built on a mock SQL Server dataset that mimics **IBM Maximo** work order and asset management data. The goal is to visualize work orders across locations, assets, and supervisors using interactive KPIs, maps, and a story-driven presentation.

🔗 **[View the Live Tableau Dashboard](https://public.tableau.com/app/profile/ajith5151/viz/maximoassetworkorderanalysis/Maximomaintenanceanalytics)**

---

## 📊 Dashboards Included

### 🔹 Work Order Overview
- KPIs: Total Work Orders, Avg. Labor Hours, % Completed
- Interactive Map: Work Orders by City (with filter actions)
- Line Chart (with trend line): Work Orders per Month
- Bar Chart: Work Orders by Type
- Highlight Table: Labor Hours by Supervisor

### 🔹 Asset-Level Insights
- Circle Plot: Avg. Labor Hours per Asset
- Line Chart with Trend Line: Work Order Completion Trend (based on Actual Finish Date)
- Bar Chart: Work Orders by Asset & Supervisor

---

## 📖 Story Included

- Tableau Story combining both dashboards:
  - **Work Order Overview**
  - **Asset-Level Insights**
- Filter-aware layout with guided captions for storytelling

---

## 🗃️ Dataset & Project Structure

- `data/Workorders_Maximo.csv`: Exported from a SQL Server view
- `sql/Create_MaximoDemo_1000Rows_Updated.sql`: Creates and seeds base tables:
  - `WorkOrders`
  - `Assets`
  - `Locations` (includes `City`, `State`, `Country` for geocoding)
- `tableau/maximo asset workorder analysis.twbx`: Packaged Tableau workbook with all dashboards and story points

---

## 🛠️ Tools Used

- **SQL Server 2022** – Data modeling and seeding
- **Tableau Desktop** – Dashboard and story creation
- **Tableau Public** – Final publishing and sharing
- **Git & GitHub** – Version control and project documentation

---

## ⚖️ License

This project is open-source for demonstration purposes.  
Feel free to use or adapt with attribution.
