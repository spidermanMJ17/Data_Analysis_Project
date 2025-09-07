# 🌍 Exploratory Data Analysis on Foreign Tourist Arrivals (FTAs) and Their Economic Impact on India  

This project focuses on analyzing **Foreign Tourist Arrivals (FTAs)** in India from **2001 to 2023** and exploring their **economic impact** through **Foreign Exchange Earnings (FEE)**. By performing Exploratory Data Analysis (EDA), we identified patterns, trends, and future projections that contribute to India’s global tourism competitiveness.

---

## 📌 Project Overview
- 📊 Conducted an in-depth EDA on multiple datasets from [data.gov.in](https://data.gov.in).
- 🔍 Analyzed **regional, demographic, and seasonal trends** in FTAs.
- 💰 Studied the correlation between **FTAs and Foreign Exchange Earnings (FEE)**.
- 🧹 Performed **data cleaning, missing value analysis (MCAR test), and imputation**.
- 📈 Forecasted FTA growth for **2022 and 2023** using proportional distribution methods.
- 🗺️ Created interactive and static **visualizations** (heatmaps, barplots, choropleths, regression plots, etc.).
- 🤖 Applied **machine learning models** (Linear Regression, Random Forest, Gradient Boosting) for predictions.

---

## 📂 Dataset Details
- **FTA 2001–2016**: Yearly distribution of foreign tourist arrivals by country & region.  
- **FTA 2017–2021**: Extended dataset including arrivals, percentage shares, and changes.  
- **FEE Dataset**: Foreign Exchange Earnings from tourism (2001–2023).  
- **Quarterly FTA Data**: Seasonal tourist arrival trends.  
- **Age Group Distribution**: Demographic split of tourists.  
- **Global Tourism Rank**: India’s rank and % share in world tourism.  

📌 Source: [data.gov.in](https://data.gov.in)

---

## 🛠️ Tech Stack & Libraries
- **Python** 🐍
- **Libraries**:  
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn`, `plotly` → Visualization  
  - `missingno` → Missing data analysis  
  - `sklearn` → Feature engineering & ML models  

---

## 🚀 Key Steps in Analysis
1. **Data Preprocessing**  
   - Imported & merged multiple datasets  
   - Dropped redundant/irrelevant columns  
   - Renamed columns for clarity  

2. **Data Cleaning**  
   - Detected missing values  
   - Applied **Little’s MCAR test** (p = 1 → data is MCAR)  
   - Imputed missing values using proportional distribution  

3. **Exploratory Data Analysis (EDA)**  
   - 📊 Univariate & Multivariate analysis  
   - 🔎 Outlier detection (2001–2023 trends)  
   - 🌍 Region & country-wise FTA distribution  
   - 👥 Age-group analysis  
   - 📆 Quarterly arrival trends  

4. **Visualization Highlights**  
   - Heatmaps of missingness & correlations  
   - Outlier plots for different year groups  
   - Choropleth maps (region-based density of FTAs)  
   - FTA vs FEE trend comparisons  

5. **Feature Engineering & Modeling**  
   - Selected key features (FTA year-wise, region, demographics, FEE)  
   - Applied **Linear Regression, Random Forest, Gradient Boosting**  
   - Evaluated models using **MSE, MAE, R² Score**  

---

## 📊 Results & Findings
- **North America & Europe** contribute the largest share of FTAs.  
- **COVID-19 (2020–2021)** caused a drastic decline in arrivals (~75%).  
- **Post-pandemic recovery** is visible in 2022 & 2023.  
- FTAs have a **strong positive correlation** with Foreign Exchange Earnings (FEE).  
- Seasonal trends indicate **Q4 (Oct–Dec)** as the peak tourist season.  

---

## 🖼️ Sample Visualizations
![Heatmap Example](assets/heatmap.png)  
![FTA Trends](assets/fta_trends.png)  
*(Add generated plots/screenshots in the `assets/` folder)*  

---

## 📌 Future Scope
- Improve predictions with **advanced ML/DL models** (e.g., LSTM for time series).  
- Expand dataset with **domestic tourism** insights.  
- Build an **interactive dashboard** using Power BI / Streamlit.  

---

## 👨‍💻 Contributors
- **Dishant Patel (202201260)** – BTech ICT  
- **Madhav Kanjilimadom (202203018)** – BTech MnC  
- **Shravan Kakadiya (202201333)** – BTech ICT  

📖 Under the guidance of **Prof. Gopinath Panda**, DA-IICT Gandhinagar  

---

## 📜 License
This project is for **academic and research purposes only**. Data is sourced from **data.gov.in** and adheres to its terms of use.

---
