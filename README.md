Prediction of Cyber Attacks using Machine Learning and Data Mining
Project Description
Cyber threats are increasing in frequency and complexity. This project addresses the need for up-to-date
cyber-attack forecasting using:
- Real-time data collection (via web scraping from Imperva)
- Temporal pattern extraction using sliding time windows
- Predictive modeling with ARIMA, SVR, Random Forest, XGBoost, KNN, CNN, and RNN
- Dashboard visualization with Microsoft Power BI
Dataset
Source: Imperva Cyber Threat Radar
Collected via: Selenium-based Web Scraping
Records ~144,000 cyber-attack entries with:
- Source Country
- Destination Country
- Industry
- Type of Attack
- Type of Malware
- Timestamp
Features
- Real-time data scraping and automated logging
- Data transformation using sliding window techniques
- Multiple model training, hyperparameter tuning, and evaluation (MAPE & RMSE)
- Power BI dashboards to visualize attack trends geographically and temporally
Machine Learning Models
Prediction of Cyber Attacks using Machine Learning and Data Mining
ARIMA: Time series forecasting baseline
Random Forest: Ensemble of decision trees
XGBoost: Gradient boosting with tree models
KNN Regression: Instance-based learning
SVR: Support Vector Machine for regression
CNN: Convolution-based pattern recognition
RNN: Sequential dependency modeling
Requirements
Python 3.8+
Jupyter Notebook
Install required libraries using:
pip install pandas numpy selenium scikit-learn matplotlib xgboost tensorflow
Also required:
- Google Chrome
- ChromeDriver added to PATH
Running the Project
1. Scrape Data from Imperva using the notebook.
2. Preprocess & Transform using sliding window method.
3. Train models (ARIMA, ML, or DL).
4. Evaluate using RMSE and MAPE.
5. Visualize with Power BI (if desired).
Power BI Integration
Includes a dashboard that:
- Shows top 10 attack trends
Prediction of Cyber Attacks using Machine Learning and Data Mining
- Maps source/target countries
- Filters by country, time, and type
Authors & Credits
Based on research by Nusrat Samia, Sajal Saha, and Anwar Haque (2024)
Implementation adapted and extended for academic use
Reference
Samia, N., Saha, S., & Haque, A. (2024). Predicting and mitigating cyber threats through data mining and
machine learning.
Computer Communications, 228, 107949. https://doi.org/10.1016/j.comcom.2024.107949
