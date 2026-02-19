# Uber NYC Pickup Analysis: Spatial Patterns & Predictive Insights

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Data Mining](https://img.shields.io/badge/Field-Data%20Mining-orange)](https://github.com/topics/data-mining)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
This project presents a comprehensive data mining analysis of **Uber pickup data in New York City**. Using a dataset of over **3.9 million records** (covering May to September 2014), the study identifies geographic hotspots, analyzes temporal mobility trends, and implements a machine learning model to predict future demand.

The goal is to provide actionable insights for fleet optimization and urban planning in high-density metropolitan areas.

## 🚀 Key Features & Methodology
The analysis follows a structured data science pipeline:

* **Data Pre-processing:** Integration of monthly CSV files, timestamp normalization, and feature engineering (extracting hour, day of the week, and month).
* **Spatial Clustering (K-Means):** Identification of **10 demand hotspots** across NYC. Calculated centroids serve as central points for high-frequency pickup zones.
* **Density Visualization:** Interactive mapping using **Folium** to visualize pickup intensity and cluster distribution.
* **Flow Analysis (Graph Theory):** Modeled transitions between clusters using **NetworkX** (undirected graphs) to understand how demand moves across the city.
* **Predictive Modeling:** Built a **Random Forest Regressor** to forecast hourly demand based on temporal features.

## 📊 Results & Performance
* **Predictive Accuracy:** The Random Forest model achieved an **R² score of 0.854**, explaining 85% of the variability in hourly pickups.
* **Temporal Insights:** Peak demand was identified during Thursday evenings and late-night weekend slots.
* **Spatial Insights:** Clear identification of major hubs (Midtown Manhattan, JFK Airport, etc.) as primary flow nodes.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `Pandas`, `NumPy` (Data Manipulation)
    * `Scikit-learn` (Clustering & Regression)
    * `Folium` (Geospatial Visualization)
    * `NetworkX` (Graph Analysis)
    * `Matplotlib`, `Seaborn` (Data Viz)

## 📁 Project Structure
* `Data-Mining-Michael-Bernasconi-Colab.ipynb`: Full source code and interactive analysis.
* `Data-Mining-Michael-Bernasconi-Report.pdf`: Detailed technical documentation.
* `Data-Mining-Michael-Bernasconi-PowerPoint.pdf`: Executive summary and visual presentation of findings.

## 👤 Author
**Michael Bernasconi**
* Master in Computer Science
* University of Trento

---
*This project was developed as part of the Data Mining course at the University of Trento.*
