📦 Supply Chain Vendor Performance Dashboard (Excel)

A fully interactive Excel-based dashboard that analyzes vendor delivery performance using PivotTables, slicers, KPIs, and automated status calculations.
This project helps supply chain teams quickly identify unreliable vendors, track delivery delays, and make data-driven decisions.

🚀 Features

✔ Automatic delivery delay calculation (Expected vs Actual dates)

✔ Status classification using formulas (Early / On-Time / Late)

✔ PivotTables for vendor performance analysis

✔ Interactive slicers for Vendor & Delivery Status

✔ Charts & KPIs showing delay trends and vendor reliability

✔ Clean, professional Excel dashboard layout

📊 Dataset Description
Column	Description
Order ID	Unique shipment ID
Vendor Name	Supplier name
Expected Delivery	Planned delivery date
Actual Delivery	Actual received date
Delay (Days)	Actual – Expected
Status	Early / On-Time / Late
🛠️ Steps Performed
1️⃣ Data Preparation

Cleaned data & formatted dates

Converted dataset to Excel Table (Ctrl + T)

Added conditional formatting for status (Early / On-Time / Late)

2️⃣ Formula Setup

Delay (Days):

=ActualDelivery - ExpectedDelivery


Status Classification:

=IF(E2<0,"Early",IF(E2=0,"On-time","Late"))

3️⃣ PivotTables

Created PivotTables for:

Vendor-wise performance summary

Delivery status distribution

4️⃣ Dashboard Design

Added bar chart, donut chart & KPI cards

Inserted slicers for Vendor and Status

Arranged everything into a clean dashboard layout

📈 Key Insights

Identify vendors with frequent late deliveries

Compare early/on-time/late performance

Track delivery reliability trends

Support supplier evaluation & corrective actions

🧰 Tools Used

Microsoft Excel

PivotTables

Slicers

Charts

Conditional Formatting

📁 File Included

Vendor_Performance_Analysis.xlsx

🙌 About This Project

A beginner-friendly supply chain analytics project ideal for:

📄 Resumes

💼 Portfolio

🔗 LinkedIn posts

🎓 Academic or internship submissions
