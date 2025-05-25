# House_Price_Prediction

# 🏡 Predicting House Prices Using Linear Regression

This project uses the **California Housing dataset** from `sklearn.datasets` to build a simple linear regression model for predicting house prices based on various features.

## 📂 Project Overview

The notebook performs the following steps:

1. **Data Loading**: Loads the California housing dataset.
2. **Exploratory Data Analysis (EDA)**: Uses plots to understand feature relationships and distributions.
3. **Data Preprocessing**:
   - Feature scaling with `StandardScaler`
   - Train-test split
4. **Model Training**:
   - Uses `LinearRegression` from `sklearn.linear_model`
5. **Model Evaluation**:
   - Calculates MAE, RMSE, and R² score
   - Visualizes residuals and predictions

## 📊 Dataset Features

The dataset includes the following features:

- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average house occupancy
- `Latitude` & `Longitude`: Location coordinates

Target variable:
- `price`: Median house value for California districts (in $100,000s)



**3📈 Sample Output**
  - Model coefficients and intercept
      
  - Residual plots
      
  - Actual vs. Predicted plot
      
  - Metrics:
      
  - Mean Absolute Error (MAE)
      
  - Root Mean Squared Error (RMSE)
      
  -R² Score

**🧠 Future Work**
  - Add polynomial regression or tree-based models (e.g., RandomForestRegressor)
      
  - Include cross-validation
      
      - Hyperparameter tuning
## 🛠️ Requirements

Make sure the following libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
