# House Price Prediction 🏠💰

## TO DO:

- Clean the dataset for classification 🧹
- Perform analysis and statistical evaluation 📊
- Apply machine learning techniques 🤖

# Machine Learning Models Used:
- CatBoostRegressor
- LGBMRegressor (LightGBM)
- RandomForestRegressor
- GradientBoostingRegressor
- LinearRegression
- KNeighborsRegressor
- SVR (Support Vector Regressor)
- DecisionTreeRegressor
- XGBRegressor (XGBoost)

# Analyses Made:
- In our study, we used **SimpleImputer** and **KNNImputer** for filling in missing data. 🛠️📊
- To label and combine categorical variables, we utilized **LabelEncoder** and **OneHotEncoder**. 🏷️🔄
- Data scaling was performed using **RobustScaler**. 📏✨
- We evaluated model performance with **k-fold cross-validation** and the **RMSE (Root Mean Squared Error)** metric. 📉✅
- Hyperparameter optimization was achieved through **GridSearchCV**. 🔍🎯
- Feature importance was analyzed using the **feature_importance** function for graphical insights. 📊🔍
- Finally, predictions were made on the test data using the selected best model, and results were recorded. 🏆📈
- Throughout the process, we tested various machine learning models, selecting the best-performing one for a comprehensive analysis and modeling study. 🤖🔬



## ABOUT THE DATA:

**This dataset focuses on housing prices in Ames, Iowa, and is intended for predictive modeling of property values. It contains detailed information about various attributes 
of residential properties, including physical characteristics, quality and condition, and their specific locations within the city. The dataset is organized into several files:
train.csv for model training, test.csv for evaluation, and sample_submission.csv which includes a benchmark prediction based on a linear regression model. The dataset features 
columns that cover fundamental details such as lot area and bedroom count, as well as more specific attributes like basement quality and garage type. The goal is to predict the 
SalePrice, which represents the sale price of each property in dollars. The accompanying data description file offers comprehensive explanations of each column, aiding in the
understanding and preprocessing necessary for predictive analysis.** 📝🔍

