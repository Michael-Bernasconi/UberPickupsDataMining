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

## 🖼️ Resulting Images
<img width="795" height="667" alt="Screenshot 2026-02-19 183456" src="https://github.com/user-attachments/assets/2788d5c8-e382-4eae-ac93-46ac38aaaef5" />
<img width="1568" height="665" alt="Screenshot 2026-02-19 183507" src="https://github.com/user-attachments/assets/abc7ee2b-fa63-4105-8062-203be293bca1" />
<img width="910" height="519" alt="Screenshot 2026-02-19 183516" src="https://github.com/user-attachments/assets/4869c807-e8f6-4cc9-9fc1-85b352322cd9" />
<img width="863" height="566" alt="Screenshot 2026-02-19 183525" src="https://github.com/user-attachments/assets/fca38e63-0eba-400a-96b2-e090f06dcea9" />
<img width="862" height="585" alt="Screenshot 2026-02-19 183535" src="https://github.com/user-attachments/assets/d51ab87d-d254-49f7-b8e4-a4cf6a591b41" />
<img width="885" height="615" alt="Screenshot 2026-02-19 183542" src="https://github.com/user-attachments/assets/61d8e308-b801-42eb-b834-1c4c49a4541d" />
<img width="814" height="488" alt="Screenshot 2026-02-19 183548" src="https://github.com/user-attachments/assets/25dc5a9b-9c7b-474c-9a2c-7f7781749d5d" />

## 👤 Author
**Michael Bernasconi**
* Master in Computer Science
* University of Trento

---
*This project was developed as part of the Data Mining course at the University of Trento.*
