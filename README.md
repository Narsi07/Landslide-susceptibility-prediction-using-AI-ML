## Overview

This project presents a comprehensive approach to **Landslide Susceptibility Prediction (LSP)** by leveraging geospatial analysis, remote sensing data, and advanced machine learning techniques. The system analyzes critical environmental and geological factors to identify vulnerable zones, providing actionable insights for disaster risk reduction and urban planning.

The study specifically focuses on **Zhushan County, Shiyan City, Hubei Province, China**, utilizing a dataset of 1,844 points and 23 environmental features.

## Key Features

* **Multi-Model Evaluation**: Comparative analysis of multiple machine learning algorithms including **XGBoost, Random Forest, LightGBM, and Logistic Regression**.

* **Geospatial Factor Analysis**: Evaluation of factors such as slope, elevation (DEM), Land Use Land Cover (LULC), Distance from River, and NDVI.

* **Interactive Interface**: A user-friendly **Gradio** dashboard for real-time risk assessment and manual feature input.

* **Optimized Performance**: Implementation of **XGBoost** as the lead model, achieving superior predictive performance and AUC scores.

* **Automated Spatial Calculation**: Uses pandas-vectorized distance calculations to determine the nearest risk locations based on latitude and longitude coordinates.

## Tech Stack

* **Languages**: Python 

* **Libraries**: Scikit-learn, XGBoost, LightGBM, Pandas, NumPy, Matplotlib, Seaborn 

* **Interface**: Gradio 

* **Analysis**: GIS Spatial Analysis, Hyperparameter Tuning (RandomizedSearchCV) 



## Outcomes

The system successfully identifies high-risk zones, enabling government bodies and disaster management authorities to prioritize regions for proactive monitoring and mitigation efforts.

