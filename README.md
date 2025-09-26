# bigdata-road-accident-analysis
Big Data analysis of UK 2020 road accident dataset — includes time analysis, clustering, SARIMA forecasting, Apriori, and social network analysis.
This project applies **big data analytics and predictive modelling** to the 2020 UK road accident dataset. It explores **temporal patterns, spatial clustering, forecasting models, association rule mining, and social network analysis** to understand when, where, and under what conditions accidents occur.

## 📌 Project Overview
- **Dataset:** UK Road Accident Data (2020)  
- **Focus Areas:**  
  1. Accident timing (hour/day/week analysis)  
  2. Vehicle- and pedestrian-specific accident trends  
  3. Spatial clustering of accidents in Kingston upon Hull and surrounding areas  
  4. Time series forecasting of weekly and daily accident counts (SARIMA)  
  5. Accident severity analysis with Apriori algorithm (weather, surface, light conditions)  
  6. Social network analysis on Facebook dataset (community detection and centrality measures)  

## ⚙️ Tools & Libraries
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn, Statsmodels (SARIMA), Mlxtend (Apriori)  
- **Network Analysis:** NetworkX, Louvain, Girvan-Newman algorithms  
- **Clustering:** K-Means, Elbow Method  

## 📊 Key Results
- **Time analysis:** Peak accidents during commuting hours (8 AM, 5–6 PM) and Fridays.  
- **Motorcycle accidents:** Engine size strongly linked to usage patterns (commute vs leisure).  
- **Pedestrian accidents:** Morning (7–9 AM) and afternoon (3–6 PM) peaks, especially Fridays.  
- **Clustering:** 4 distinct accident hotspots identified in Hull region.  
- **SARIMA forecasts:** Seasonal accident patterns visible (higher in summer, lower in winter).  
- **Apriori:** Dry conditions linked with slight accidents; poor lighting & wet/icy roads linked with serious accidents.  
- **Network analysis:** Facebook dataset shows highly modular communities; Louvain detected 103 sub-groups.  

## 📂 Repository Contents
- `notebooks/Bigdata_Project.ipynb` — Full Jupyter Notebook with code, analysis, and visualisations  
- `reports/BIGDATA_project.pdf` — Final project report (academic format)  
- `README.md` — Project overview (this file)  

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/Glad-analytics/bigdata-road-accident-analysis.git
2.	Open BigData_Project.ipynb in Jupyter Notebook.
3.	Install dependencies with: 'pip install -r requirements.txt'
4.  Run cells step by step to reproduce analysis, clustering, forecasting, and network modelling.

📖 Reference

Project completed as part of MSc Artificial Intelligence & Data Science coursework at the University of Hull (2025).
