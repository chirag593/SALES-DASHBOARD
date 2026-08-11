# SALES-DASHBOARD

# 💻 Computer & Electronics Sales Dashboard — Excel

An interactive **Computer & Electronics Sales Dashboard** built using Microsoft Excel to analyze revenue, order volume, product demand, and sales performance across various technology products.

The project focuses primarily on **computer hardware, networking devices, storage devices, gaming products, laptops, and other technology-related products**.

---

## 📊 Project Overview

This project analyzes a sales dataset containing **2,001 records and 12 columns** representing individual transactions across different computer and electronics products.

The objective was to transform raw transactional data into an interactive dashboard that provides a clear overview of sales performance and enables users to explore the data using interactive filters.

### Key Metrics

The dashboard tracks five major KPIs:

* **Total Revenue**
* **Total Orders**
* **Total Quantity Sold**
* **Average Order Value**
* **Average Quantity Sold**

---

## 🗂️ Dataset

The dataset contains **2,001 rows and 12 columns** covering sales transactions for technology-related products.

Products include categories such as:

* 💻 Laptops & Computers
* 🎮 Gaming Products
* 💾 Storage Devices
* 🧠 Memory Cards & Memory Products
* 🌐 Networking Devices
* 🖥️ Computer Accessories
* 🔌 Other Computer & Electronic Products

---

## 🔄 Data Cleaning & Transformation

The raw dataset was initially imported into **Microsoft Excel** and then loaded into **Power Query** for data preparation.

The following transformations were performed:

* Imported the raw dataset into Excel.
* Loaded the dataset into **Power Query**.
* Reviewed and corrected the **data types** for each column.
* Created a calculated **Net Revenue** column using Unit Price, Quantity, and Discount.

### Net Revenue Calculation

```text
Net Revenue = Unit Price × Quantity × (1 − Discount)
```

* Cleaned and transformed the dataset.
* Loaded the processed data back into Excel for analysis.

---

## 📈 Key Performance Indicators

Five KPI cards were created to provide a quick overview of sales performance.

| KPI                       | Description                                       |
| ------------------------- | ------------------------------------------------- |
| **Total Revenue**         | Total net revenue generated from all transactions |
| **Total Orders**          | Total number of orders/transactions               |
| **Total Quantity Sold**   | Total number of units sold                        |
| **Average Order Value**   | Average revenue generated per order               |
| **Average Quantity Sold** | Average number of units sold per order            |

---

## 📊 Dashboard

The dashboard was developed using **Pivot Tables, Pivot Charts, KPI cards, and Slicers**.

### Pivot Tables

Five Pivot Tables were created to support the dashboard's visualizations and analyze different dimensions of the sales data.

### Charts

The Pivot Tables were used to create multiple charts for analyzing areas such as:

* Product performance
* Revenue performance
* Quantity sold
* Order trends
* Sales distribution across different product segments

### Interactive Slicers

Slicers were added to allow users to dynamically filter the dashboard and analyze specific segments of the dataset.

---

## 🔧 Project Workflow

```text
Raw Sales Dataset
        ↓
Import into Excel
        ↓
Load Data into Power Query
        ↓
Format & Validate Data Types
        ↓
Create Net Revenue Column
        ↓
Clean & Transform Data
        ↓
Load Processed Data into Excel
        ↓
Create Pivot Tables
        ↓
Calculate KPIs
        ↓
Create Pivot Charts
        ↓
Add Slicers
        ↓
Dashboard Design & Formatting
        ↓
Interactive Computer & Electronics Sales Dashboard
```

---

## 🛠️ Tools Used

* **Microsoft Excel**
* **Power Query**
* **Pivot Tables**
* **Pivot Charts**
* **Slicers**
* **Calculated Columns**
* **Data Cleaning & Transformation**

---

## 🎯 Skills Demonstrated

* Data cleaning and transformation using Power Query
* Data type management
* Creation of calculated columns
* Business KPI development
* Pivot Table analysis
* Pivot Chart creation
* Interactive dashboard development
* Slicer-based data filtering
* Excel data visualization
* Converting raw transactional data into actionable business information

---

## 💼 Business Value

The dashboard provides a consolidated view of computer and electronics sales performance.

It allows users to quickly evaluate:

* Overall revenue generation
* Number of orders
* Product demand
* Quantity sold
* Average order value
* Average quantity per order
* Sales performance across different filtered segments

The interactive dashboard makes it easier to explore thousands of individual transactions without manually analyzing the raw dataset.

---

## 📁 Project Structure

```text
Computer-Electronics-Sales-Dashboard/
│
├── Dataset/
│   └── computer_electronics_sales.xlsx
│
├── Dashboard/
│   └── computer_electronics_sales_dashboard.xlsx
│
├── Screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 How to Use

1. Download the Excel dashboard from this repository.
2. Open the `.xlsx` file using Microsoft Excel.
3. Navigate to the **Dashboard** sheet.
4. Use the available **Slicers** to filter the data.
5. Analyze the KPI cards and charts to explore sales performance.

---

## 📷 Dashboard Preview

Add a screenshot of the completed dashboard below:

![Computer & Electronics Sales Dashboard](Screenshots/dashboard.png)

---

## 📌 Project Outcome

Transformed a **2,001-row computer and electronics sales dataset** into an interactive Excel dashboard using **Power Query, Pivot Tables, Pivot Charts, KPI cards, and Slicers**, providing an efficient way to monitor and analyze technology product sales performance.
