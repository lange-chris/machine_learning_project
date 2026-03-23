## 🌍 Project Overview

This project focuses on leveraging Machine Learning to predict tourist expenditure in Tanzania. By analyzing historical travel data, we aim to provide the Tanzania Tourism Board with actionable insights to identify high-value segments and optimize strategic marketing spend.

## 🎯 Project Objective

Develop a predictive model to estimate tourist expenditure to identify high-value segments and maximize the return on marketing investment (ROI).


## 🛠️ Methodology & Tech Stack

Data Processing: Log-transformation (log1p) to handle extreme expenditure "Whales" (outliers up to 99M TZS).

Modeling: Ridge Regression with Hyperparameter Tuning (Grid Search for optimal Alpha), RandomForest, XGBoost with Hyperparameter-Tuning

Evaluation: Focus on MAE for financial planning and robust quality assessment.

Libraries: scikit-learn, pandas, numpy, seaborn, matplotlib.

## 📁 Repository Structure

models/: Exploratory Data Analysis and Model Experiments.

reports/: Final Slides.

data/: (Not tracked) Processed datasets used for training.

## 🚀 Strategic Recommendations

Prioritize Western Markets: Focus marketing budgets on the US and Northern Europe for premium Wildlife packages.

Activity-Based Targeting: Move KPIs from "Nights Stayed" to "Wildlife Activity Participation."

Group Incentives: Create tailored offers for larger travel groups, as they exhibit higher total contribution stability.

#### Team: Chris (Ridge Regression), Esther (Random Forest), Isis (XGBoost)
