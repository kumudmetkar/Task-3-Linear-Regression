**Task 3: Linear Regression – House Price Prediction**

**This notebook is part of my internship**

**Objective**

To implement and understand both simple and multiple linear regression using the Housing dataset. The aim is to predict house prices based on features like area, number of bedrooms, and other house characteristics.

**Tools & Libraries**
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

**Dataset**

Housing.csv
https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction

**Workflow**

1. **Import & Preprocess**
- Loaded the dataset using Pandas
- Handled missing values
- Converted categorical variables using one-hot encoding (`get_dummies`)

2. **Split Data**
- Used `train_test_split()` to split into training (80%) and testing (20%)

3. **Model Fitting**
- Applied `LinearRegression()` from sklearn
- Trained the model on the training data

4. **Model Evaluation**
Used the following metrics:
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **R² Score (Coefficient of Determination)**

5. **Plot & Interpretation**
- Created a regression line plot for `area` vs `price`
- Interpreted model coefficients to understand impact of each feature


**Coefficient Interpretation**

- area: +₹235.97 per sq ft
- bedrooms: +₹76,778 per bedroom
- airconditioning_yes: +₹7.91 lakhs
- unfurnished: –₹4.13 lakhs (cheaper than furnished)

Full interpretation available in the notebook.

**Conclusion**

The linear regression model performs reasonably well for predicting house prices. Features like area, number of bathrooms, and amenities (like AC or basement) had significant impact on price.

**Skills learnt**

Regression modeling, evaluation metrics, model interpretation

