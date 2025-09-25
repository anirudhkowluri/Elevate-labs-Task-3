In this project I loaded housing dataset, preprocessesed it, trained a linear regression model, evaluated its performance, and saved predictions along with residuals to a new CSV file.
- Loaded housing data from CSV
- Preprocess data by one-hot encoding categorical variables
- Split data into training and testing sets
- Features like more bathrooms, air conditioning, hot water heating, preferred area, stories, basement, and main road access have strong positive associations with price.
- Furnishing status (semi/unfurnished) shows negative coefficients relative to the base category, suggesting furnished may command a premium.
- The area-price plot shows a clear positive trend, as expected.
- Fit a linear regression model on the training data
- Evaluate model performance using MAE, MSE, and R²
- The model explains a solid portion of variance (R² shown above). Error levels are consistent with the price scale.
- Here are the key results and artifacts.
- Evaluation metrics (MAE, MSE, R²)
- MAE: 970043.4039201636
- MSE:1754318687330.6638
- R²:0.6529242642153184
- Plot price vs area with regression line for test set
- Interpret and display model coefficients
- Predict prices for the full dataset and save results to a new CSV
  
