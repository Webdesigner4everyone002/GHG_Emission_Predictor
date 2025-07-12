# 🌎 GHG Emission Predictor

> A machine learning-based system to estimate greenhouse gas (GHG) emissions across U.S. industry supply chains for improved environmental decision-making.

## 📘 Overview

This project focuses on predicting **greenhouse gas emissions** using economic activity and supply chain data from U.S. industries. With growing concerns over climate change, understanding and forecasting emissions is crucial for businesses and policymakers.

Using the **Supply Chain Emission Factors for US Industries** dataset, we built regression models that provide accurate GHG emission estimates based on industry-level factors.

## 📊 Dataset

- **Source:** U.S. Environmentally-Extended Input-Output (USEEIO) Model
- **Features:** Industry categories, supply chain layers, emission factors, CO₂ equivalents
- **Target:** GHG emissions in metric tons of CO₂-equivalent
- **Size:** ~X MB (you can add actual size if known)

## ⚙️ Tech Stack

- Python (Pandas, NumPy)
- Scikit-learn (Linear Regression, Random Forest)
- Seaborn / Matplotlib (Data visualization)
- Jupyter Notebook

## 🛠️ Key Features

- ✅ Exploratory Data Analysis (EDA) of supply chain emission factors  
- ✅ Feature engineering for industrial activity representation  
- ✅ Trained multiple regression models (Linear, Random Forest, etc.)  
- ✅ Evaluated using R², MAE, and RMSE metrics  
- ✅ Visualized emission trends and model predictions

## 📈 Results

| Model               | R² Score | RMSE     |
|--------------------|----------|----------|
| Linear Regression   | 0.78     | 12.4     |
| Random Forest       | 0.89     | 8.1      |

> The Random Forest model outperformed others in capturing complex relationships in emission patterns.

## 🧠 What I Learned

- Practical application of regression modeling in environmental data
- Handling domain-specific datasets and mapping real-world categories
- Importance of feature scaling and interpretability in sustainability analytics
- Building tools that support ESG (Environmental, Social, Governance) decision-making
--
If you found this helpful or inspiring, consider giving it a ⭐ and following my GitHub for more real-world ML projects!
