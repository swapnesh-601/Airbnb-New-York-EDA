# Airbnb-New-York-EDA
Exploratory Data Analysis (EDA) of New York City Airbnb listings using Python to uncover insights on pricing, room types, availability, and host behavior.

![Uploading New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg…]()


# 🏙️ Airbnb Listings EDA Project – New York (2024)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-lightblue)
![EDA](https://img.shields.io/badge/Project-EDA-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of Airbnb listings in **New York City** to identify trends, patterns, and insights related to pricing, room types, availability, and host behavior.  
The analysis leverages Python data analysis and visualization libraries to support **data-driven decision-making** for both guests and hosts.

---

## 🎯 Project Objectives
The main objectives of this project are to:
- Analyze **room types**, **prices**, and **availability** across different neighborhoods.
- Understand **host behavior** and listing distribution.
- Detect and handle **price outliers**.
- Provide **actionable recommendations** for Airbnb guests and hosts.

---

## 📂 Dataset Description
- **Total Records:** 20,765  
- **Total Features:** 22  

### Key Columns
- `id` – Unique identifier for each listing  
- `name` – Listing title  
- `host_name` – Name of the host  
- `neighborhood_group` – Borough (Manhattan, Brooklyn, etc.)  
- `latitude`, `longitude` – Geographical coordinates  
- `price` – Nightly rental price  
- `room_type` – Entire home/apt, Private room, Shared room  
- `reviews_per_month` – Average monthly reviews  
- `availability_365` – Number of available days per year  

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced statistical visualizations
- **Jupyter Notebook** – Analysis environment

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Handled missing values in `price`, `neighborhood`, and `beds`.
- Converted `last_review` column to **datetime** format.
- Treated extreme outliers by **capping prices above $1,000** to prevent skewed analysis.

---

### 2️⃣ Exploratory Data Analysis (EDA)

#### 🏠 Room Type Analysis
- Bar plots used to visualize room type distribution.
- **Entire home/apt** identified as the most common room type.

#### 📍 Neighborhood Group Insights
- Price comparison across boroughs.
- **Manhattan** shows the highest average prices, followed by **Brooklyn**.

#### 📆 Availability Analysis
- Correlation heatmaps used to analyze relationships between:
  - Price
  - Availability (`availability_365`)
  - Number of reviews
  - Beds

#### 💰 Price Distribution
- Histograms show that most listings are priced between **$50 – $300**.

#### 👤 Host Behavior
- Boxplots reveal that some hosts manage multiple listings, indicating **professional hosting trends**.

#### ⭐ Review Patterns
- Pair plots highlight relationships between price, availability, and number of reviews.

---

## 📊 Visualizations Included
- **Bar Charts** – Room type & neighborhood distribution  
- **Histograms** – Price distribution  
- **Boxplots** – Price outlier detection  
- **Heatmaps** – Feature correlations  
- **Pair Plots** – Review, price, and availability relationships  

---

## 🔍 Key Findings & Insights

### Price Trends
- Manhattan listings are the most expensive.
- Entire homes/apartments are significantly costlier than private or shared rooms.

### Room Type Distribution
- Entire homes dominate the market.
- Private rooms provide budget-friendly alternatives.

### Outliers
- A small number of listings priced above **$10,000** were detected and filtered.

### Availability Patterns
- Higher availability listings generally have **lower prices** and **more reviews**.

### Host Behavior
- Multiple-listing hosts indicate commercialization of Airbnb properties.

---

## ✅ Recommendations

### For Guests
- Prefer listings with **high availability** and **good reviews**.
- Private rooms in **Brooklyn** offer better affordability than Manhattan.

### For Hosts
- Improve availability and actively manage reviews.
- Adopt competitive pricing within the borough market.

---

## 🧾 Conclusion
This EDA project delivers meaningful insights into the New York Airbnb market using structured data analysis and visualization techniques. The findings support informed decision-making for both travelers and property owners.  
Future enhancements may include **predictive modeling** and **advanced statistical analysis**.

---

## 🙏 Credits
This project was developed with learning support from **YouTube – Zero Analyst**.  
Special thanks for the tutorial guidance that helped in understanding and building this analysis.

