# 🌾 Global Sugarcane Production EDA

This project presents an in-depth Exploratory Data Analysis (EDA) on global sugarcane production data, aiming to understand patterns across countries and continents, including production volume, yield, land usage, and per-person metrics.

## 📁 Dataset Overview

- **Source**: Dataset of 100+ countries with sugarcane production data  
- **Features**:
  - `Country` and `Continent`
  - `Production(Tons)`
  - `Production_per_person(Kg)`
  - `Acreage(Hectare)`
  - `Yield(Kg/Hectare)`

## 🎯 Objectives

- Clean and preprocess real-world agricultural data
- Perform univariate and bivariate analysis on production-related features
- Identify top-producing countries and continents
- Analyze relationships between land, yield, and total production
- Use visualization to reveal insights and trends

## 🧰 Tools & Libraries

- **Python 3**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Visualization and plotting
- **Jupyter Notebook** – Interactive analysis

## 🧹 Data Cleaning Highlights

- Removed commas and periods from numeric fields
- Converted string columns to float
- Dropped null rows
- Renamed columns for consistency

## 📊 Key Insights

- **Brazil** and **India** are the top sugarcane producers globally
- **Uttar Pradesh (India)** is among the highest in production within Asia
- A strong correlation exists between `Acreage(Hectare)` and `Production(Tons)`
- **Africa** has the most countries growing sugarcane, but **South America** and **Asia** lead in overall production
- Higher yield per hectare doesn't always mean higher total production

## 🔍 Analysis Performed

- ✅ Univariate analysis with boxplots and distributions
- ✅ Bivariate relationships using scatter plots and correlation heatmaps
- ✅ Pie charts and bar graphs to show production distribution by continent and country
- ✅ Continent-wise aggregation and comparison
- ✅ Identification of outliers and high-yield countries

## 📌 Sample Questions Answered

- Which countries produce the most sugarcane?
- Does more land guarantee more production?
- Which countries have the highest yield per hectare?
- How is sugarcane production distributed across continents?
- What are the correlations between production, land, and yield?

