# 📊 Power BI Assignment: Supply Chain Data Exploration

## 📌 Project Overview  
This project involves building an **interactive dashboard** in Power BI based on the **Orders dataset**.  
The dashboard provides insights into **sales, costs, and order trends** with interactive filters for deeper analysis.  

---

## 📂 Datasets Used  
- **Orders.xlsx** → Contains order-related information including:  
  - Order ID  
  - Product ID  
  - Product Category  
  - Supplier  
  - Order Date  
  - Delivery Date  
  - Quantity Ordered  
  - Unit Price  
  - Total Cost  
  - Delivery Status  
  - Region  
  - Warehouse  

### ❌ Datasets Not Used  
- **Products_Table.xlsx** → Product details (Product ID, Product Name, Category, Price, Supplier).  
  - Not used because product-related columns such as `Product Category`, `Supplier`, and `Unit Price` are already included in the **Orders table**.  

- **Suppliers.xlsx** → Supplier information (Supplier ID, Name, Contact, Region).  
  - Not used because supplier details are already available in the **Orders table**.  

- **Warehouses.xlsx** → Warehouse details (ID, Location, Capacity).  
  - Not used because warehouse details (Warehouse column) are already included in the **Orders table**.  

---

## 🎯 Dashboard Features  

### 🔑 KPI Cards  
- 🛒 **Total Orders** → Total number of orders placed  
- 📦 **Total Quantity Ordered** → Sum of items ordered  
- 💰 **Total Sales (Revenue)** → Sum of `Total Cost`  
- 💲 **Average Unit Price** → Average of `Unit Price`  
- 🚚 **On-time Delivery %** → % of orders delivered on time  

### 📊 Charts & Visuals  
1. 📈 **Orders Trend Over Time** (Line Chart) – Order trends by month/year  
2. 🏷 **Sales by Product Category** (Bar/Column Chart) – Compare revenue across categories  
3. 📊 **Quantity Ordered vs. Sales** (Clustered Column Chart) – Highlights demand and revenue relationship  
4. 💹 **Average Unit Price by Product Category** (Column Chart) – Category-level price comparison  
5. 🗺 **Sales by Region** (Pie Chart) – Regional sales distribution  

### 🎛 Filters / Slicers  
- 🌍 Region  
- 📅 Year  
- 🏬 Warehouse  
- 🤝 Supplier  

---

## 🚀 Insights You Can Gain  
- Seasonal and yearly **order trends**  
- Which **product categories** drive the most sales and revenue  
- Supplier and warehouse performance analysis  
- Regional contribution to sales  
- Efficiency in delivery (**on-time vs delayed**)  

---

## 🛠 Tools Used  
- **Power BI** → Data visualization and dashboard building  
- **Excel** → Data source  

---

## 📷 Dashboard Preview  
https://github.com/Sanketkshirsagar05/PowerBI-Assignment-Supply-Chain-Data-Exploration/blob/main/Screenshot/Dashboard.png


