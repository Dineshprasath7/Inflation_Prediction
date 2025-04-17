#  Inflation Forecasting System

This project presents a **Streamlit-based interactive web application** designed to predict inflation trends using **Consumer Price Index (CPI)** data collected from **January 13 to January 25**. By leveraging **machine learning techniques—specifically a Random Forest Regressor**, the application enables users to choose between **Rural, Urban, or Combined CPI values** as the target for prediction.

---

## Technical Overview

- **Data Preprocessing**:
  - Missing and malformed data are handled gracefully.
  - Categorical features are **label-encoded**.
  - Numerical features are **standard scaled** for optimal model performance.

- **Model**:  
  - Trained using **Random Forest Regressor** from **scikit-learn**.
  - Supports multiple **train-test split options** (70/30, 80/20, and 90/10).
  
- **Visualization**:
  - Real-time predictions are displayed alongside actual CPI values.
  - **Plotly** is used to generate **dynamic line charts** for enhanced interpretability.

- **Frontend**:  
  - Built with **Streamlit**, offering an intuitive and interactive interface.
  - Users can:
    - Explore raw and preprocessed datasets.
    - Select CPI targets to predict.
    - View model performance metrics and feature importance.

- **Performance Optimization**:
  - **Caching** is used to improve data loading performance.
  
- **Deployment**:
  - The application is **exposed publicly using LocalTunnel**, enabling remote access and testing.

---

##  Prediction Targets

- Rural CPI
- Urban CPI
- Combined CPI

---

##  Model Accuracy

| Train-Test Split | R² Score (Accuracy)     |
|------------------|--------------------------|
| 70/30            | **0.9836664648322104**   |
| 80/20            | **0.983847948466591**    |
| 90/10            | **0.98441929698824**     |

---

##  Use Cases

- **Policy Analysts**: Evaluate how CPI trends evolve over time.
- **Economists**: Predict inflation patterns for planning and reporting.
- **Data Enthusiasts**: Learn how ML can be applied to economic indicators.

---

##  Summary

This application demonstrates how **machine learning** can generate **actionable insights** from public economic data. It showcases the full ML pipeline—from preprocessing to model deployment—within an accessible web interface. It serves as both a **practical forecasting tool** and an **educational resource** for anyone interested in CPI-based inflation prediction.

---
