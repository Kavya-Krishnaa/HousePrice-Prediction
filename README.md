 🏠 House Price Prediction using Linear Regression

 📌 Task Objective

This project involves implementing Linear Regression to predict house prices based on various housing features using a dataset from Kaggle. This task was completed as part of Task 3 of the AI/ML Internship.

 📁 Dataset Used

- Dataset: `Housing.csv` (from Kaggle)
- Total Records: 545
- Features include: area, bedrooms, bathrooms, furnishing status, etc.
- Target variable: `price`

 🔧 Tools & Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (LinearRegression, metrics, train_test_split)

 📊 Steps Performed

 1. Data Preprocessing
- Converted categorical columns (`yes/no`) to numeric (1/0)
- One-hot encoded `furnishingstatus` to avoid dummy variable trap
- Checked for missing values (none found)

 2. Train/Test Split
- Split into 80% training and 20% testing using `train_test_split`

 3. Model Training
- Trained `LinearRegression()` model using scikit-learn

 4. Model Evaluation
- Calculated:
  - Mean Absolute Error (MAE): ₹9.7 lakhs
  - Root Mean Squared Error (RMSE): ₹13.2 lakhs
  - **R² Score**: `0.65` (model explains 65% of the variance)

 5. Visualization
- Scatter plot of Actual vs Predicted prices
- Most points lie close to the ideal line, showing fair prediction quality

 📈 Sample Output

Mean Absolute Error (MAE): 970043.40
Mean Squared Error (MSE): 1.75e+12
Root Mean Squared Error (RMSE): 1324506.96
R² Score: 0.6529
