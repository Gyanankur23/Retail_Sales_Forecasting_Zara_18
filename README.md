# Retail_Sales_Forecasting_Zara_18 CaseCraft Analytics Project Sprint Project 18


## 🛍️ Overview  
This project models Zara’s monthly retail sales using synthetic data across categories and regions. It blends seasonal decomposition, exponential smoothing, and regression modeling to forecast revenue and guide inventory planning.

## 🎯 Objective  
To analyze monthly revenue trends, decompose seasonal patterns, and predict future sales using time series and regression techniques.

## 📅 Dataset & Features  
- Timeframe: Jan 2023 – Dec 2024 (24 months)  
- Categories: Tops, Bottoms, Outerwear, Accessories  
- Regions: North, South, East, West  
- Features: revenue, month, category, region  
- Derived: seasonal component, trend, residuals, month number

## 📊 Visual Explorations  
- **Facet Grid**: Monthly revenue by category and region  
- **Seasonal Decomposition**: Trend, seasonality, residuals for Tops  
- **Waterfall Chart**: Revenue breakdown by category (latest month)  
- **Forecast Plot**: Outerwear revenue projection using Exponential Smoothing

## 🔮 Forecasting & Modeling  
- **Exponential Smoothing**: Forecasted Outerwear revenue for 6 months  
- **Regression Model**:  
  - Input: category, region, month  
  - Target: revenue  
  - Model: Gradient Boosting Regressor  
  - Performance: MAE ≈ **2,593**

## 🧠 Key Insights  
1. **Seasonal Patterns**: Tops and Outerwear show strong seasonality  
2. **Regional Spikes**: Accessories peak in Q4 across regions  
3. **Revenue Drivers**: Tops dominate latest month’s revenue  
4. **Forecast Alignment**: Smoothing and decomposition models agree  
5. **Model Utility**: Regression predicts monthly revenue with low error

## ✅ Final Conclusion  
Zara’s retail sales exhibit clear seasonal and regional dynamics. This framework supports inventory planning, campaign timing, and revenue forecasting—ideal for retail teams seeking data-driven decision support.