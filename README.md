# 🚗 Car Price Analysis – Exploratory Data Project

Welcome to my data science project on used car listings! This notebook explores a dataset of 301 cars with attributes like price, fuel type, transmission, ownership, and more. The goal is to uncover patterns in pricing, ownership, and resale trends using Python and pandas.

---

## 📦 Dataset Overview

- *Source*: car_data.csv
- *Shape*: 301 rows × 9 columns
- *Features*:
  - Car_Name, Year, Selling_Price, Present_Price, Kms_Driven
  - Fuel_Type, Seller_Type, Transmission, Owner

---

## 🔍 Key Questions & Insights

### 1. What is the average selling price?
- *₹4.66 lakhs* across all listings.

### 2. What is the most common fuel type?
- *Petrol* dominates with *79.4%* of cars.

### 3. How many cars were manufactured before 2010?
- *26 cars*, mostly petrol and diesel.

### 4. What year had the most listings?
- *2015, with **61 cars* listed.

### 5. How many cars had 0 previous owners?
- *290 cars*, indicating mostly first-hand vehicles.

### 6. Are any cars sold above their present price?
- *None* — all were sold below or equal to market value.

---

## 📊 Visualizations

- *Pie Charts*: Fuel type and seller distribution
- *Bar Charts*: Year-wise manufacturing and listing trends
- *Scatter Plot*: Selling vs Present Price correlation
- *Grouped Analysis*: Ownership, fuel type, and transmission combinations

---

## 📈 Statistical Highlights

| Metric                  | Value            |
|------------------------|------------------|
| Max Present Price      | ₹92.6 lakhs      |
| Max Selling Price      | ₹35.0 lakhs      |
| Highest Mileage (Diesel)| 197,176 km       |
| Unique Fuel × Seller × Transmission | 8 combinations |

---

## 🛠 Tools Used

- Python (Jupyter Notebook)
- pandas, matplotlib, seaborn
- Exploratory Data Analysis (EDA)

---

## 📁 Project Structure


├── car_data.csv
├── EDA_Car_data.ipynb
└── README.md
