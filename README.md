



#  AI & ML Internship – Task 3: Linear Regression

##  Objective
To implement and understand both **simple** and **multiple linear regression** using the **Housing Price Prediction** dataset and evaluate model performance using regression metrics.



##  Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (LinearRegression, train_test_split, metrics)



##  Dataset
- **Name**: Housing Price Prediction Dataset  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- **Description**: Includes features like area, number of bedrooms, bathrooms, presence of facilities (like basement, air conditioning), etc. to predict the house price.

---

##  Steps Followed

### 1. Import and Preprocess the Dataset
- Loaded the CSV file using `pandas`
- Replaced categorical values (`yes`, `no`, `furnished`, etc.) with numerical equivalents using `df.replace()`
- Used `df.infer_objects()` to avoid future downcasting warnings

### 2. Split Data into Train-Test Sets
- Used `train_test_split()` with a test size of 20%

### 3. Fit Linear Regression Model
- Trained `LinearRegression()` on the training dataset

### 4. Evaluate Model Performance
- Calculated:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score

```plaintext
 Evaluation Metrics:
MAE: 979679.69
MSE: 1771751116594.04
R² Score: 0.65
````

### 5. Model Coefficients

```plaintext
area: 235.85
bedrooms: 78574.49
bathrooms: 1097117.27
stories: 406223.16
mainroad: 366824.19
guestroom: 233146.77
basement: 393159.78
hotwaterheating: 687881.31
airconditioning: 785550.58
parking: 225756.51
prefarea: 629901.66
furnishingstatus: 210397.12
Intercept: -127711.17
```

### 6. Plot: Area vs Price Regression

* A scatter plot was generated showing actual vs predicted prices using `area` as the X-axis feature.
* A regression line overlays the plot showing the model’s predictions.

![Plot: Area vs Price](area_vs_price_regression.png) <!-- Add this plot to your repo if saved -->



##  Submission

*  GitHub Repository Link: \[Paste your GitHub link here]
*  Submitted via: Internship Task Submission Form


##  Author

**Kasara Pavan Sai Reddy**
B.Tech in Artificial Intelligence & Machine Learning
Presidency University, Bengaluru
[LinkedIn Profile](https://www.linkedin.com/in/kasara-pavan-sai-reddy-2a6761256)


