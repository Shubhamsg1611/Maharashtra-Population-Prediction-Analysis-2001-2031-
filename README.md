# 📊 Maharashtra Population Prediction & Analysis (2001–2031)

## 📌 Project Overview
This project analyzes and predicts **district-wise population trends of Maharashtra** using historical census data and machine learning techniques. It combines **regression and classification models** with **Power BI dashboards** to forecast population for **2021 and 2031**, considering migration patterns, urban pressure, growth categories, and pandemic impact.

---

## 🎯 Objectives
- Analyze Maharashtra district-level population data (2001 & 2011)
- Perform feature engineering on demographic and urban indicators
- Predict future population using machine learning regression models
- Classify districts by growth and urban pressure categories
- Compare calculated vs ML-predicted population
- Visualize insights through interactive Power BI dashboards

---

## 🗂️ Dataset
**Source:** Maharashtra Census Data (2001 & 2011)

### Key Columns:
- Population (2001, 2011)
- Area (sq. km)
- Population Density (2001, 2011)
- Literacy Rate
- Sex Ratio
- Decadal & Annual Growth Rate
- Migration Zone
- Urban Pressure Category
- Growth Category

### Engineered Features:
- Density Growth Rate
- Literacy Factor
- Sex Ratio Index
- Adjusted Growth
- Pandemic Impact Adjustment
- Predicted Population (2021, 2031)

---

## 🧠 Machine Learning
### Problem Types:
- **Regression:** Population prediction (2021 & 2031)
- **Classification:** Growth category & urban pressure category

### Models Used:
- Linear Regression
- Random Forest Regressor
- Multi-Output Regression
- Random Forest Classifier

### Performance Highlights:
- Regression R² ≈ 0.93
- Population Error:
  - 2021 ≈ 1.53 Million
  - 2031 ≈ 2.72 Million

---

## 📊 Power BI Dashboard
The Power BI report includes:
- Executive overview KPIs
- Population comparison (2001 vs 2011)
- Migration & growth analysis
- Pandemic vs non-pandemic population (2021)
- Predicted vs calculated population (2021 & 2031)
- District-wise error analysis


---

## 🛠️ Tools & Technologies
- Python (pandas, numpy, scikit-learn, matplotlib)
- Machine Learning (Regression & Classification)
- Power BI Desktop
- Jupyter Notebook

---

## 📈 Key Insights
- High in-migration districts show rapid population growth
- Urban pressure strongly correlates with population density
- Pandemic impact slightly reduced 2021 population projections
- ML predictions closely align with demographic calculations

---

## 🚀 Future Scope
- Integrate official Census 2021 data
- Use advanced models (XGBoost, LightGBM)
- Apply time-series forecasting
- Add GIS-based spatial analysis

---

## 👤 Author
**Shubham S. Ghanwat**  
MBA (Data Science & Business Analytics)  
Machine Learning | Data Analytics | Power BI


