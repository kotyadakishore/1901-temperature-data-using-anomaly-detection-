🌡️ Anomaly Detection in Climate Data using Isolation Forest & PCA

 
 Project Overview

This project focuses on detecting anomalies (outliers) in climate data using machine learning techniques. The dataset contains daily temperature records, and the goal is to identify unusual temperature values.

🎯 Objectives
Detect abnormal temperature values
Apply Isolation Forest for anomaly detection
Use PCA (Principal Component Analysis) for visualization
Understand data patterns through graphs


📂 Dataset
File: ghcn_daily_1901_kaggle.csv
Contains:
date → Date of observation
element → Type (TMAX, TMIN, PRCP)
value → Measured value




⚙️ Technologies Used

Python 🐍
Pandas
Scikit-learn
Matplotlib
Seaborn



🔍 Methodology

1. Data Preprocessing
Convert date to datetime
Filter TMAX values
Remove missing data
2. Feature Selection
Use value column for analysis
3. Anomaly Detection
Apply Isolation Forest
