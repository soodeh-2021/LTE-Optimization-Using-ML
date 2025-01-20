# LTE-Optimization-Using-ML  
**Optimizing LTE Network Performance Using Machine Learning Techniques**

---

## Overview  
This project focuses on improving LTE network performance by predicting and optimizing key performance indicators (KPIs) using machine learning models. The study leverages real-world data to analyze network performance trends and applies models like **Random Forest**, **Support Vector Regression (SVR)**, and **Linear Regression** to enhance throughput, reduce latency, and optimize resource allocation.

---

## Objectives  
- Investigate and compare machine learning techniques for KPI prediction and network performance analysis.  
- Conduct comprehensive data analysis to identify key patterns and trends in LTE network KPIs.  
- Optimize LTE network characteristics using machine learning predictions.  
- Validate model performance and compare them with traditional benchmarks.  
- Provide actionable recommendations for network operators.

---

## Dataset  
The dataset includes:  
- **Time Period**: 3 months of LTE network data.  
- **Metrics**: Downlink throughput, uplink throughput, PRB utilization, packet loss rate, and CQI across three diverse regions.  
- **Features**: Over 68,000 rows of data covering urban, semi-urban, and rural LTE environments.

---

## Methods  
### Data Preprocessing:  
- Cleaning, normalization, and outlier management.  

### Models Used:  
- **Random Forest**: High accuracy and feature importance analysis.  
- **Support Vector Regression (SVR)**: Effective for non-linear relationships.  
- **Linear Regression**: Baseline model for comparison.  

### Evaluation Metrics:  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R-squared  

### Tools:  
- Python libraries: **Scikit-Learn**, **Pandas**, **Matplotlib**

---

## Results  
- **Best Model**: Random Forest outperformed SVR and Linear Regression in accuracy and adaptability.  
- **Key Findings**:  
  - **CQI** was identified as the most critical KPI influencing throughput.  
  - **PRB utilization** and **latency** also significantly impacted performance.
