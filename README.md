# Customer_Behavior_Analysis
Data analytic project showcasing customer behavior analysis using Python,Sql and Power BI


# 🧠 Data Analytics Project — End-to-End Analysis & Dashboard

## 📋 Overview
This project showcases a complete **data analytics pipeline**, starting from raw data ingestion to business insights presentation.  
It involves **Python-based EDA**, **SQL querying**, and **Power BI dashboard creation**, followed by a **final report and presentation** using Gamma.

---

## 📂 Dataset
- **Name:** Customer Purchase Dataset *(example)*
- **Format:** CSV  
- **Description:** Contains customer demographic details, purchase amounts, discounts, and product reviews.
- **Objective:** To analyze customer purchasing behavior, sales performance, and product popularity.

---

## 🛠 Tools & Technologies

| Category | Tools |
|-----------|--------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database | MySQL Workbench / MySQL Server |
| Visualization | Power BI |
| Reporting | Gamma.app |
| Environment | Jupyter Notebook |

---

## 🚀 Project Workflow

### 1️⃣ Data Loading & Exploration (Python)
- Imported dataset using **Pandas**
- Conducted **Exploratory Data Analysis (EDA)**:
  - Checked missing values, outliers, and data types  
  - Generated descriptive statistics and visualizations  

### 2️⃣ Data Cleaning
- Handled missing values and duplicates  
- Standardized column names and formats  
- Removed outliers using IQR  
- Exported the cleaned dataset for SQL integration  

### 3️⃣ SQL Integration (MySQL)
- Created database: `customer_database`
- Loaded cleaned data into MySQL using **SQLAlchemy / MySQL Connector**
- Performed key queries:
  - Top 5 products by average rating  
  - Discount usage by gender  
  - Customer segmentation by previous purchases  

### 4️⃣ Dashboard Development (Power BI)
- Connected **Power BI** to MySQL
- Built an interactive dashboard featuring:
  - 📊 Revenue by Gender  
  - 🛍️ Top-Selling Products  
  - 🌟 Product Ratings  
  - 👥 Customer Segment Analysis  
- Added KPIs, slicers, and dynamic visuals for better insights  

### 5️⃣ Reporting & Presentation (Gamma)
- Summarized insights into a Power BI report
- Created a **Gamma presentation** highlighting:
  - Key findings  
  - Visual snapshots  
  - Business recommendations  

---

## 📊 Dashboard Highlights
- 📈 Total Revenue and Customer KPIs  
- 💸 Discount Effect on Sales  
- 👥 Customer Segment Distribution (New, Returning, Loyal)  
- 🌟 Average Product Ratings  
- 🧾 Sales Breakdown by Product and Gender  

---

## 💡 Key Insights
- Returning customers contribute **60%+** of total revenue  
- Discounted items achieve **25% higher sales** on average  
- Average customer satisfaction rating: **4.3 / 5**  
- Loyal customers drive the most consistent sales volume  

---

## ⚙️ How to Run the Project

### 🔹 Requirements
- Python 3.9+
- MySQL Server (Workbench)
- Power BI Desktop

### 🔹 Setup Steps
1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/data-analytics-project.git
   cd data-analytics-project
