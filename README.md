# airbnb-pricing-strategy-analysis
End-to-end Airbnb NYC data analysis project with Python EDA and Power BI dashboard, providing pricing insights, demand trends, and business recommendations.
# Airbnb Pricing Strategy Analysis

## 📌 Project Overview

This project focuses on analyzing Airbnb listings in New York City to uncover pricing patterns, demand trends, and key factors influencing listing prices. The goal is to derive actionable insights that can help hosts optimize their pricing strategy.
The analysis combines **Python-based Exploratory Data Analysis (EDA)** and an **interactive Power BI dashboard** to generate actionable business insights.
---

## ⭐ Project Highlights

* End-to-end data analysis workflow from data cleaning to dashboarding
* Business-focused insights for Airbnb pricing strategy
* Interactive Power BI dashboard with location-based analysis
* Feature engineering for deeper demand and pricing insights
* Clear storytelling with insights and business recommendations

---

## 🎯 Business Problem

Airbnb hosts often struggle to determine the optimal price for their listings.
This project aims to identify the factors that influence pricing and demand to support better pricing strategies.

---

## ❓ Business Questions

* Which neighborhoods have the highest number of Airbnb listings?
* How does price vary across different room types?
* Which neighborhoods have the most expensive listings?
* What factors influence Airbnb listing prices?
* Which areas have the highest demand based on reviews?
* Which availability level has the most listings?
* Which demand level dominates across NYC?
* How do price categories vary by borough?

---

## 🛠 Tools & Technologies

* Python (Pandas, NumPy)
* Matplotlib & Seaborn
* Power BI

---

## 📊 Dashboard Preview

![Dashboard] ![image alt](https://github.com/panditrobin514-art/airbnb-pricing-strategy-analysis/blob/2a31e0a58ef849ae9a1470d02d543d14e8fb81a6/images/airbnb_dashboard_image.png)

## 📸 Dataset Snapshot

![Dataset Preview] ![image alt](https://github.com/panditrobin514-art/airbnb-pricing-strategy-analysis/blob/d09f83b62c9b2af9206c6096834c3f0f83853433/images/dataset_preview.png)

---

📁 Dataset Information

**The dataset contains Airbnb listings with features such as:**
* Location (neighbourhood, latitude, longitude)
* Room type
* Price and price category
* Reviews and ratings
* Availability and demand level

---

## 📊 Dataset Preview

| id | neighbourhood_group | neighbourhood | room_type | price | rating | bedrooms | price_category | demand_level |
|----|--------------------|--------------|----------|-------|--------|----------|----------------|--------------|
| 1312228 | Brooklyn | Clinton Hill | Private room | 55 | 5.0 | 1 | Budget | Low |
| 45277537 | Manhattan | Hell's Kitchen | Entire home/apt | 144 | 4.67 | 2 | Standard | Low |
| 971000000 | Manhattan | Chelsea | Entire home/apt | 187 | 4.17 | 1 | Standard | Medium |
| 3857863 | Manhattan | Washington Heights | Private room | 120 | 4.64 | 1 | Standard | Medium |
| 40896611 | Manhattan | Murray Hill | Entire home/apt | 85 | 4.91 | Studio | Budget | Low |

---

## 📌 Key KPIs from Dashboard

* Total Listings: ~19K
* Average Price: ~$175
* Average Reviews per Month: ~44
* Average Availability: ~207 days

These KPIs provide a quick overview of the Airbnb market in New York City.

---

## 📊 Key Insights

* Manhattan and Brooklyn have the highest number of Airbnb listings, dominating the NYC market.
* Entire homes/apts are the most expensive, while private and shared rooms are cheaper.
* Manhattan has the most expensive listings compared to other boroughs.
* Location, room type, and number of beds strongly influence prices.
* Manhattan and Brooklyn have the highest demand, with more reviews per month than other boroughs.
* Most listings fall into the High and Very High availability categories, showing year‑round supply.
* The majority of listings are in the Low and Medium demand categories, with only a small share achieving very high demand.
* Budget and Standard listings dominate Brooklyn and Queens, while Luxury and Ultra Luxury listings are concentrated in Manhattan.

---
** Mid-priced listings (around $100–$300) show the highest demand, making them the most competitive segment in the market.
---

## 💡 Business Recommendations

* Hosts in high-demand areas like Manhattan can charge premium prices
* New hosts should consider offering private rooms to stay competitive
* Focus on mid-priced listings to maximize bookings
* Pricing strategy should depend on location and room type

---

## ▶️ How to Use This Project

1. Open the Jupyter Notebook to explore data cleaning and analysis
2. Review visualizations and insights in the notebook
3. Open the Power BI dashboard (.pbix file) for interactive analysis
4. Use filters (room type, neighborhood, price range) to explore patterns

---

## 📂 Project Structure

```id="struct_final"
airbnb-pricing-strategy-analysis
│
├── data/
│   ├── new_york_listing.csv
│   └── clean_airbnb_data.csv
│
├── notebook/
│   └── airbnb_analysis.ipynb
│   └── airbnb_analysis.html
│
├── dashboard/
│   └── airbnb_dashboard.pbix
│
├── images/
│   ├── airbnb_dashboard.png
│   └── dataset_preview.png
│   └── price_distribution.png
│   └── Room_Type_Distribution_Across_NYC_Neighborhood.png
│
└── README.md
```

---

## 📚 Learning Outcomes

* Improved skills in data cleaning and preprocessing
* Gained hands-on experience in exploratory data analysis (EDA)
* Learned to extract business insights from real-world data
* Built interactive dashboards using Power BI
* Developed a structured and professional project workflow

---

## 🚀 Future Improvements

* Build a machine learning model for price prediction
* Add advanced feature engineering techniques
* Deploy dashboard online (Power BI Service / Streamlit)

---

## 👨‍💻 Author

Robin Pandit
Aspiring Data Analyst
