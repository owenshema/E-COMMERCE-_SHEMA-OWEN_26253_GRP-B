# E-COMMERCE-_SHEMA-OWEN_26253_GRP-B

# 🛍️ E-Commerce Business Insights in Rwanda – Capstone Project

**Course:** INSY 8413 – Introduction to Big Data Analytics  
**Academic Year:** 2024–2025, Semester III  
**Student:** Shema Owen (ID: 26253)  
**Instructor:** Eric Maniraguha  
**Dataset Source:** National Institute of Statistics of Rwanda (IBES 2023)  


---

## 📌 Project Overview

This capstone project explores the distribution and characteristics of formal and informal businesses in Rwanda using the 2023 Integrated Business Enterprise Survey (IBES). The goal is to gain insights that can inform the development of the e-commerce sector through regional, sectoral, and business size-based analysis.

---

## ❓ Problem Statement

> **How can we analyze and predict customer purchasing behavior in an e-commerce platform to improve product recommendations, increase customer retention, and boost overall sales performance?"
**

---

## 🗂️ Dataset Summary

| Attribute         | Description                             |
|------------------|-----------------------------------------|
| **Source**       | NISR ([https://statistics.gov.rw](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fstatistics.gov.rw%2Fsites%2Fdefault%2Ffiles%2Fdocuments%2F2025-06%2FIBES%25202023_Tables%2520and%2520Figures.xlsx&wdOrigin=BROWSELINK))        |
| **Dataset**      | IBES 2023 – Table 1.1 Summary            |
| **Format**       | CSV (converted from official table)      |
| **Scope**        | Business count and economic activity     |
| **Dimensions**   | Region, Sector, Formality, Size, Year    |

Key fields:
- **Region**: Kigali, South, West, North, East  
- **Sector**: Retail, Finance, Education, Manufacturing, etc.  
- **Formality**: Formal vs Informal  
- **Business Size**: Micro (1–3), Small (4–30), Medium, Big  
- **Formation Period**: 2000 or less to ≥2021

---

## 🛠️ Tools Used

- **Python (Jupyter Notebook)** – For data cleaning, analysis, and modeling  
  - `pandas`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Power BI** – For interactive dashboards and visual storytelling  
- **Excel** – For data entry conversion and preprocessing

---

## DATA WHERE IT STARTS
<img width="1148" height="353" alt="checking where data starts" src="https://github.com/user-attachments/assets/ec45c23d-6754-41d0-a315-63d0b27097f7" />



## 🔍 Python Data Analysis Tasks

1.** MACHINE LEARNING**
  **Data Cleaning**
   - Standardized region names and categories
   - Converted string numbers to numeric types
   - Handled missing or inconsistent values
  
   - <img width="993" height="446" alt="data cleanning" src="https://github.com/user-attachments/assets/dc7496c5-81b8-40d5-b065-429ae9cc6764" />

  
   - <img width="993" height="446" alt="data cleanning" src="https://github.com/user-attachments/assets/f4f9e23f-b219-46f2-a95f-c4aceb6a0a07" />


3. **Exploratory Data Analysis (EDA)**
   - Business count by region and sector
   - Formal vs informal comparison
   - Sector distribution by business size
  <img width="818" height="310" alt="codes for formal vs informal" src="https://github.com/user-attachments/assets/8ee10a3b-b08e-4628-b9a4-8e07770e073f" />

   - 
  <img width="1021" height="612" alt="formal vs informal" src="https://github.com/user-attachments/assets/9745a68a-c39e-4aaa-88da-614abe1a2792" />

  
<img width="553" height="228" alt="kigali distribution codes" src="https://github.com/user-attachments/assets/44d85cb0-bca6-4971-b7aa-134da012ca9e" />
<img width="1061" height="514" alt="kigali distribution" src="https://github.com/user-attachments/assets/cfffde59-326d-4d2b-836a-5d6fb16b5076" />

   - 

3. **Modeling (Optional)**
   - Clustering sectors by region to find e-commerce hotspots
   - 
  
   - <img width="1097" height="584" alt="clutter" src="https://github.com/user-attachments/assets/3fb16a14-d5ee-46be-bb3e-34afc516ffee" />


4. **Innovation**
   - Visual mapping of business potential by province
  <img width="928" height="165" alt="heatmapcodes" src="https://github.com/user-attachments/assets/0c21608d-dc83-4ba6-9b4a-c48b5d6fd4fd" />
<img width="973" height="611" alt="heatmap" src="https://github.com/user-attachments/assets/d81b370f-c01e-4866-b6c2-e94d6f808983" />

   - 
   - Use of custom functions for economic scoring
   - 
<img width="1282" height="598" alt="Screenshot 2025-08-01 070634" src="https://github.com/user-attachments/assets/ba63340d-8593-4a67-8738-ecb2023c684b" />

---

## 📊 Power BI Dashboard Highlights

- Bar charts showing **business count by sector**
- Slicers for filtering by **province**, **sector**, and **formality**
- Line chart for **enterprise formation trends over time**
- Pie chart comparison: **formal vs informal**
- Custom tooltips and bookmarks for cleaner user experience

<img width="750" height="406" alt="dashboard" src="https://github.com/user-attachments/assets/5c0cf9c5-e7bf-401a-a793-f5e33f4679f5" />


---

## 💡 Key Insights

- Kigali dominates in both formal and informal business presence.
- Wholesale & retail trade is the leading sector, followed by other services and accommodation/food.
- Informal businesses make up a majority in most regions, especially in micro-size enterprises.
- Newer business formation (2021+) is highly concentrated in Kigali and Eastern Province.

---

## 📈 Recommendations

- Focus e-commerce platform development in Kigali, East, and South provinces.
- Support digitization programs for **micro and small informal businesses**.
- Leverage retail sector strength to expand digital marketplaces.
- Introduce training programs to help informal businesses transition into formal, registered platforms.

---

## 🔮 Future Work

- Integrate **financial inclusion data** to enhance analysis
- Use **geo-mapping** for visual province comparison
- Apply **sentiment analysis** if survey feedback is available

---
