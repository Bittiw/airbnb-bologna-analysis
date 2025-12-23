# Airbnb Bologna Data Analysis

## Project Overview

This project analyzes Airbnb listings in **Bologna, Italy** to understand the key factors influencing pricing, occupancy, and demand patterns. The analysis follows a complete data analysis workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, and insight generation.

The goal is to demonstrate practical data analysis skills using real-world data and to extract actionable insights relevant to hosts, travelers, and market analysts.

---

## Key Questions Addressed

1. **Which features most influence listing prices?**
2. **What differentiates high-occupancy listings from low-performing ones?**
3. **How do location and seasonality affect demand?**

---

## Dataset

- Source: Airbnb listings dataset
- Scope: Listings in Bologna, Italy
- Key features include price, room type, availability, reviews, host activity, and location coordinates.

---

## Analysis Workflow

### 1. Data Cleaning & Preprocessing

- Removed invalid and missing price entries
- Handled missing values in reviews and host information
- Removed extreme price outliers using the IQR method
- Converted date fields to proper datetime format

### 2. Feature Engineering

- Log-transformed price to handle skewness
- Created host type categories (single vs professional)
- Engineered occupancy levels from availability
- Derived seasonal features from review dates
- Calculated distance from Bologna city center using geospatial coordinates
- Bucketed reviews and minimum nights for comparative analysis

### 3. Exploratory Data Analysis (EDA)

- Distribution analysis of prices and availability
- Price comparison across room types and neighborhoods
- Correlation analysis for price drivers
- Occupancy analysis by host behavior and booking constraints
- Seasonal demand patterns based on review activity

---

## Key Insights

- Prices are **right-skewed**, with most listings concentrated in lower price ranges.
- **Entire homes** and **hotel rooms** command higher prices than private rooms.
- Listings closer to the **city center** tend to be more expensive and have higher demand.
- Professional hosts typically price higher but also maintain stronger occupancy.
- Demand shows clear **seasonal patterns**, peaking in warmer months.

---

## Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Geopy
- Jupyter Notebook
- Git & GitHub

---

## Repository Structure

airbnb-bologna-analysis/
├── notebooks/
│ └── airbnb-analysis-bologna.ipynb
├── data/
│ └── listings.csv
├── requirements.txt
├── README.md

---

## How to Run the Project

1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies:
   pip install -r requirements.txt
4. Run the notebook from top to bottom

---

## Author

**Bita Koohestani**  
Computer Engineering Student | Data Analysis & Visualization
