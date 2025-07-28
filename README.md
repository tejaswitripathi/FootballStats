# Predictive Playbook: Machine Learning Insights into College Football Win Rates 🏈📊  
*A machine learning project exploring what drives success in college football, with a focus on predicting team win rates.*

## 🧠 Project Overview  
This project analyzes a college football dataset to predict **`winRate`**, the proportion of games won by a team. Using machine learning models such as **Random Forest**, **Gradient Descent Linear Regression**, and **AdaBoost with Shallow Regression Trees**, we identify which team performance metrics most strongly predict victory.

## 🎯 Objectives  
- Predict `winRate` using key performance indicators  
- Identify the most influential features (e.g., total points, defensive rankings)  
- Compare multiple ML models for performance  
- Validate findings using residuals and scatter plots

## 📈 Key Features Identified  
From feature importance analysis using **Random Forest Regressor**, the most predictive variables were:
- `TotalPoints`  
- `ScoringDefRank`  
- `AvgPointsPerGameAllowed`  
- `PointsPerGame`

These variables were used in subsequent model training and analysis.

## 🔍 Machine Learning Techniques Used

### 🌲 Random Forest Regressor  
- Used for feature selection via importance scores  
- Ensemble method that builds many decision trees and averages their outputs  
- Helped isolate only the most relevant predictors for training

### 📉 Gradient Descent for Linear Regression  
- Used to minimize cost function and optimize model parameters  
- Iterative updates improve predictive accuracy  
- Scatter plots of predictions vs actuals used to visualize performance

### 🚀 AdaBoost with Shallow Regression Trees  
- Boosting technique applied to improve prediction and reduce model variance  
- Performed well in capturing **non-linear feature interactions**

## 🧪 Model Evaluation  
- Residual plots and scatter plots were used to compare models  
- Linear regression captured general trends  
- AdaBoost provided improved accuracy in more complex regions of the feature space

## 💡 Insights and Takeaways  
- The selected features are **strong indicators of team success**  
- AdaBoost demonstrated **superior performance** when feature interactions were present  
- Gradient Descent allowed for fine-tuning of regression coefficients  
- Predictive modeling in sports analytics can offer **real-world strategic applications** for analysts, coaches, and institutions

## 🧰 Tools & Libraries  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- `scikit-learn` for Random Forest and AdaBoost  
- Custom implementation of gradient descent for linear regression  
- Jupyter for analysis and visualization

## 🔮 Next Steps  
- Run models on out-of-sample / future season data for generalization  
- Investigate how performance changes across different leagues or divisions  
- Explore additional metrics like turnover margin, yards per play, or coaching history

## 📌 Team  
- Vikas Rama  
- Rohan Saha  
- Tejaswi Tripathi  
- Wonjoon Yang
