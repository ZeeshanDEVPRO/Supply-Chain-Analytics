
---

## 🧪 Dataset Overview

The project uses multiple CSV datasets related to:

- **Customers** – customer IDs, locations, etc.
- **Orders** – order dates, delivery times, etc.
- **OrderItems** – products purchased per order
- **Payments** – payment methods, statuses, and values
- **Products** – product categories and IDs

> 📂 These files are expected to be in the same working directory as the notebook.

---

## 🔧 Steps Performed

### 1. Data Loading
Loaded datasets using Pandas and verified structure with `.info()` and `.head()`.

### 2. Data Cleaning & Transformation
- Removed missing and duplicate entries
- Converted data types (dates, strings)
- Merged tables using keys (`customer_id`, `order_id`, `product_id`)

### 3. Exploratory Data Analysis (EDA)
- Analyzed order frequency and delivery times
- Identified top-selling products and revenue contributors
- Visualized customer segmentation and regional trends using:
  - `matplotlib`, `seaborn` heatmaps, countplots, histograms

### 4. Feature Engineering
- Calculated metrics like:
  - Order delivery time
  - Payment value per product
  - Order frequency per customer

### 5. Machine Learning (optional/ongoing)
- (Add if applicable) Built a basic model for:
  - Predicting late deliveries or high-value customers
- Used:
  - `scikit-learn` for model training and evaluation

---

## 📊 Power BI Dashboard

- **Visuals Included**:
  - Monthly revenue trends
  - Top products by sales and revenue
  - Customer region breakdown
  - Payment method distribution
- **Purpose**: To provide stakeholders with real-time, actionable insights from the supply chain

---

## 📈 Key Insights

- Customers from Brazil had the highest purchase volume.
- Products in the toys contributed most to revenue.
- Most common delays were in diapers and hygiene.
- Preferred payment methods: credit card.

---

## 🧠 Skills Demonstrated

- Data wrangling and cleaning
- Business-oriented data analysis
- Building and interpreting visual dashboards
- End-to-end project execution using Python and Power BI

---

## 📎 How to Use

1. Clone the repo
2. Open the `.ipynb` file in Jupyter/Colab and run all cells
3. Open the `.pbix` file in Power BI Desktop for visual insights

---

## 📎 Author

Zeeshan Sayeed 
📧 Email: zeeshansayeedindia@gmail.com 

---

