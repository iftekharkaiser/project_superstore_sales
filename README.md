# 🧪 H2O AutoML Regression – Supermarket Sales

## 📌 Project Overview
This project uses **H2O AutoML** to build and evaluate multiple machine learning regression models for predicting supermarket sales-related outcomes. The workflow leverages H2O Flow to automate model training, hyperparameter tuning, and leaderboard ranking.

The project demonstrates an end-to-end **regression pipeline**, from data ingestion to model comparison, using a real-world supermarket sales dataset.

---

## 🎯 Project Objectives
- Perform regression modeling using H2O AutoML
- Compare multiple algorithms automatically
- Identify the best-performing model using RMSE
- Understand key factors influencing supermarket sales behavior
- Showcase AutoML capabilities for scalable machine learning

---

## 📂 Dataset
- **Dataset Name:** Supermarket Sales (Regression)
- **Rows:** 1,000
- **Columns:** 18

### Key Features
- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Total
- Date
- Time
- Payment Method
- Cost of Goods Sold
- Gross Margin Percentage

> The dataset is commonly used for educational and analytical purposes.

---

## 🛠️ Tools & Technologies
- **H2O.ai**
- **H2O Flow (Web UI)**
- **H2O AutoML**
- **Python (H2O backend)**
- **CSV Dataset**

---

## ⚙️ Methodology
1. Imported CSV data into H2O
2. Parsed and inspected column types
3. Performed an 80/20 train-test split
4. Selected a regression response variable
5. Ran H2O AutoML with default settings
6. Trained multiple models automatically:
   - Deep Learning
   - GBM
   - DRF
   - XGBoost
   - Stacked Ensembles
7. Ranked models using RMSE on the leaderboard

---

## 📊 Model Evaluation
- **Evaluation Metric:** RMSE (Root Mean Squared Error)
- **Additional Metrics:** MSE, MAE
- **Cross-Validation:** Enabled (Auto)

### Best Model
- **Algorithm:** Deep Learning
- **Best RMSE:** ~1.29
- Multiple deep learning models dominated the leaderboard, indicating strong nonlinear relationships in the data.

---

## 🏆 AutoML Leaderboard Highlights
- Deep Learning models consistently outperformed tree-based models
- Ensemble models performed competitively but not best-in-class
- Automatic feature handling and preprocessing improved efficiency

---

## 🧠 Key Insights
- AutoML efficiently identifies high-performing models with minimal manual tuning
- Sales-related variables exhibit nonlinear behavior
- Discount-independent variables strongly influence predictions
- Deep Learning performs well on structured retail datasets

---

## 🚀 How to Reproduce
1. Install H2O:
   ```bash
   pip install h2o
