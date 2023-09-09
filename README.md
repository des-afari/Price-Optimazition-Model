# Price Optimization with Random Forest

Price optimization is a critical aspect of any business strategy, as it directly impacts profitability and customer satisfaction. Random Forest is a powerful machine learning algorithm that can be leveraged for price optimization. 

### Step 1: Import Libraries, Load and Clean Data

### Step 2: Split Data into Training and Testing Sets

### Step 3: Create and Train the Random Forest Model

### Step 4: Make Predictions

### Step 5: Evaluate Model Performance

All steps shown in **main.ipynb**

# Optional
### Step 6: Feature Importance
### Get feature importances
`feature_importances = rf_model.feature_importances_`

### Create a DataFrame to show feature names and their importances
`feature_importance_df = pd.DataFrame({'Feature': X.columns, 'Importance': feature_importances})`

### Sort features by importance
`feature_importance_df = feature_importance_df.sort_values(by='Importance', ascending=False)`

### Display the top N important features (e.g., top 10)
`feature_importance_df.head(10)`

### Step 7: Hyperparameter Tuning
