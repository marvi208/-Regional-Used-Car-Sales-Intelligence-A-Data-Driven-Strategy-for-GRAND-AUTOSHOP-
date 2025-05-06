# -Regional-Used-Car-Sales-Intelligence-A-Data-Driven-Strategy-for-GRAND-AUTOSHOP-
This project analyzes regional sales data for GRAND AUTOSHOP to identify trends in pricing, location performance, and vehicle attributes. It delivers actionable insights and recommendations to optimize inventory, boost revenue, and align with market demand.
# 🚗 GRAND AUTOSHOP Regional Analytical Sales Report

---

## 📑 Outline

- [Introduction](#introduction)
- [Story of Data](#story-of-data)
- [Data Splitting and Preprocessing](#data-splitting-and-preprocessing)
- [Pre-Analysis](#pre-analysis)
- [In-Analysis](#in-analysis)
- [Post-Analysis and Insights](#post-analysis-and-insights)
- [Data Visualizations & Charts](#data-visualizations--charts)
- [Recommendations and Observations](#recommendations-and-observations)
- [Conclusion](#conclusion)
- [References & Appendices](#references--appendices)

---

## 📘 Introduction

### 🎯 Objective of the Project

To analyze regional car sales data and extract actionable insights that can guide inventory, pricing, and marketing strategies.

### 🔧 Problem Being Addressed

Which locations, fuel types, and car characteristics are most profitable, and how can GRAND AUTOSHOP adjust its focus accordingly?

### 📊 Key Datasets and Methodologies

- Internal sales dataset with attributes such as brand, location, fuel type, and year.
- Excel tools used: Pivot Tables, Advanced Filters, COUNT, SUM, SUMIF, formatting, and dashboards.

---

## 🧾 Story of Data

### 🗂 Data Source

Internal dealership sales dataset from GRAND AUTOSHOP.

### 🛠 Data Collection Process

Collected via dealership logs across multiple city branches.

### 🧱 Data Structure

Each row represents a vehicle listing with the following attributes:  
Location, Brand, Price, Year, Fuel Type, Transmission, Kilometers Driven.

### ⭐ Key Features

- Price and Year for value tracking.
- Fuel Type and Transmission for demand segmentation.
- Location for regional performance analysis.

### ⚠️ Limitations

- No customer demographics.
- No data on unsold listings.
- Only listing prices available.

---

## 🧹 Data Splitting and Preprocessing

- Removed duplicates and fixed inconsistent labels.
- Grouped and aggregated data by location, fuel type, year, and mileage.
- Separated Price as the dependent variable; others as independent.
- Industry: Used Automotive Retail in India.
- Stakeholders: Sales managers, marketers, and inventory planners.
- Relevance: Drives smarter pricing, sourcing, and campaign planning.

---

## 🔍 Pre-Analysis

### 📊 Early Trends

- Mumbai has the highest listing count.
- Coimbatore generates the highest revenue.
- Diesel vehicles lead in total price contribution.

### 🔗 Initial Relationships

- Fewer listings ≠ lower revenue.
- Manual transmission is dominant.
- Listings peak around 60,000 km mileage.

---

## 🔬 In-Analysis

### 🧠 Discovered Patterns

1. **Mumbai** tops listing count (949), but **Coimbatore** earns the most (₹9589.75K).
2. **Mercedes-Benz GLE 350d** is the highest-priced car listed.
3. Revenue peaked between **2015–2017** models.
4. **Diesel** is the top fuel type by revenue.
5. Most listed cars have ~**60,000 km** mileage.
6. Manual cars (4299) significantly outnumber automatics (1720).

### ✅ Suggested Actions

- Reevaluate Mumbai’s sales model.
- Increase premium car inventory.
- Replicate Coimbatore’s pricing strategy in other regions.
- Source more 2015–2017 model cars.
- Focus marketing around diesel vehicles (while staying future-proof).
- Prioritize cars in the 60k km range.
- Slowly increase automatic car stock.

---

## ✅ Post-Analysis and Insights

### 🔍 Key Findings

- High listings ≠ high revenue.
- Premium brands hold resale value.
- Year of manufacture directly affects price.
- Transmission type skews manual.

### 🧭 Final Matched Insights

- **Mumbai** needs quality control.
- **Luxury brands** add value.
- **Diesel fuel** drives majority sales.
- **2015–2017** are golden resale years.
- **Automatics** may gain future traction.

---

## 📊 Data Visualizations & Charts

Visualizations were created in Excel using:

- Dashboard (Interactive KPI summary)

> All visuals include legends, titles, and percentage labels for clarity.
![Dashboard 5](https://github.com/user-attachments/assets/6b567e7e-4302-4608-8dff-6b73190000b5)

---

## 🧩 Recommendations and Observations

### 📌 Actionable Steps

- Restructure Mumbai’s inventory approach.
- Push premium listings across cities.
- Scale Coimbatore’s high-efficiency model.
- Stock and spotlight 2015–2017 models.
- Track shift toward automatics.

### ❗ Notable Surprises

- Low-listing cities performed better than high-volume ones.
- Manual transmission still dominates despite rising automatic trends.

---

## 🏁 Conclusion

### 🔍 Key Learnings

- Regional focus yields sharper strategy than global metrics.
- Data-driven sourcing can outperform traditional sales forecasting.
- Excel remains a powerful tool for descriptive analytics.

### 🚧 Limitations

- Lacked buyer demographics and real transaction price data.
- Potential aggregation bias in grouped values.

### 🔮 Future Work

- Add buyer persona and conversion data.
- Integrate profit margin tracking.
- Explore pricing elasticity based on features.

---

## 📚 References & Appendices

- Internal Sales Data – GRAND AUTOSHOP
- Excel Dashboard & Pivot Table Features
- Microsoft Excel Documentation

> Charts, pivot screenshots, and additional Excel formulas are available in the `/assets` folder of this repository.
