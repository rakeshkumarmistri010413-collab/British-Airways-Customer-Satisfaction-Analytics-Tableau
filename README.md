# ✈️ British Airways Customer Satisfaction Analytics — Tableau

![Data Source](https://img.shields.io/badge/Data_Source-CSV-blue?style=flat&logo=spreadsheet)
![Domain](https://img.shields.io/badge/Domain-Aviation%20%26%20Travel-orange)
![Level](https://img.shields.io/badge/Level-Intermediate-green)
![Tools](https://img.shields.io/badge/Tools-Tableau-yellow)
![Tools](https://img.shields.io/badge/Tools-Excel-red)

## 📌 Project Overview
**British Airways Customer Satisfaction Analytics** is a data visualization project designed to analyze airline service quality, passenger sentiment, and recommendation patterns. By integrating review metrics with geographic data, this project identifies key drivers of customer loyalty and areas requiring operational improvement.

---

## ✈️ Business Problem
In the highly competitive aviation industry, maintaining high service standards is critical. British Airways needs to understand which specific touchpoints (Seat Comfort, Staff Service, Food, etc.) most influence a passenger's decision to recommend the airline and how satisfaction varies across different traveler segments and global regions.

---

## 🎯 Business Objectives
- Identify the primary drivers of **"Recommended"** status  
- Compare satisfaction levels across different **Seat Types** (Economy vs. Business)  
- Analyze the correlation between specific service ratings (e.g., Food & Beverage) and **Overall Rating**  
- Track geographic sentiment to identify regional service gaps  
- Segment traveler behavior (**Business vs. Leisure**) to tailor service offerings  

---

## 📂 Dataset Information
- **Main File:** `British Airways Reviews.twbx` (Tableau Packaged Workbook)  
- **Supplemental File:** `Countries.csv` (Mapping for Continent/Region analysis)  
- **Industry:** Aviation / Customer Experience  

### Attributes
- Ratings (1–5)  
- Review Text  
- Aircraft Type  
- Traveller Type  
- Seat Type  
- Recommendation Status  

---

## 🧾 Dataset Schema (Key Fields)

| Column Name               | Description |
|--------------------------|-------------|
| Overall Rating            | General score given by the passenger (1–10) |
| Seat Comfort              | Rating for seating quality (1–5) |
| Cabin Staff Service       | Rating for crew performance (1–5) |
| Food & Beverages          | Rating for catering quality (1–5) |
| Inflight Entertainment    | Rating for movie/wifi options (1–5) |
| Value For Money           | Perception of price vs. service (1–5) |
| Recommended               | Binary (Yes/No) indicating customer loyalty |
| Type Of Traveller         | Business, Couple Leisure, Family Leisure, Solo Leisure |
| Seat Type                 | Economy, Premium Economy, Business, First Class |
| Origin Country            | Passenger’s home country |

---

## 📊 Visualizations & Analysis

### 1. Executive Summary Dashboard
A high-level view showing the **Net Recommendation Rate** and average scores for key service dimensions.  
**Purpose:** Enables stakeholders to quickly assess overall performance.

### 2. Service Performance Matrix
A comparative **bar chart or radar chart** showing service categories (Staff, Food, Comfort) versus a 4-star benchmark.

### 3. Geographic Sentiment Map
Using `Countries.csv`, this map visualizes satisfaction by **continent**.  
**Insight:** Highlights regions where long-haul routes show lower *Value for Money* scores.

### 4. Traveller Segment Analysis
A **heat map** cross-tabulating **Seat Type** and **Traveller Type**.  
**Key Question:** Do Business Class travelers value *Staff Service* more than *Seat Comfort* compared to Economy travelers?

### 5. Recommendation Correlation
A **scatter plot / trend line** illustrating the relationship between **Value for Money** and **Recommendation status**.

---

## 💡 Key Insights
- **Staff as a Differentiator:** Cabin Staff Service consistently scores higher than Food & Beverage.  
- **The Value Gap:** *Value for Money* is the strongest predictor of a positive recommendation.  
- **Leisure vs. Business:** Solo Leisure travelers are more critical of Inflight Entertainment than Business travelers.  
- **Regional Variance:** Certain regions show higher Seat Comfort satisfaction on newer aircraft types.

---

## 🛠️ How to View This Project
1. Download the `British Airways Reviews.twbx` file  
2. Open it using **Tableau Desktop** or **Tableau Public**  
3. Use the **Dashboard Filters (Top Right)** to explore different Traveller Types and Years  

---

## 👨‍💻 Author
**Rakesh Kumar Mistri**  
Aspiring Data Analyst  

- **GitHub:** https://github.com/rakeshkumarmistri010413-collab  
- **LinkedIn:** https://www.linkedin.com/in/rakesh-kumar-mistri-07ab15334/
- **Email:** rakeshkumarmistri010413@gmail.com
