# House Price Prediction

This project aims to predict house prices based on various property and neighborhood attributes using machine learning techniques. The analysis and modeling were performed in a Jupyter Notebook environment to develop a predictive model that estimates house prices based on input features.

## Dataset

- **Description:** This dataset includes a range of attributes related to neighborhood characteristics and housing features, which are essential in predicting house prices.
- **Features:**
  - `CRIM`: Crime rate per capita by town
  - `ZN`: Proportion of residential land zoned for lots over 25,000 sq. ft.
  - `INDUS`: Proportion of non-retail business acres per town
  - `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
  - `NOX`: Nitric oxide concentration (parts per 10 million)
  - `RM`: Average number of rooms per dwelling
  - `AGE`: Proportion of owner-occupied units built before 1940
  - `DIS`: Weighted distances to five Boston employment centers
  - `RAD`: Index of accessibility to radial highways
  - `TAX`: Full-value property tax rate per $10,000
  - `PTRATIO`: Pupil-teacher ratio by town
  - `B`: Weighted proportion of Black population by town
  - `LSTAT`: Percentage of lower-status population

The target variable is the house price, which the model will attempt to predict based on these features.

## Project Workflow

1. **Data Preprocessing**
   - Loaded the dataset and handled missing values and outliers.
   - Normalized continuous variables to optimize model performance.
   - Converted categorical variables (such as `CHAS`) where needed for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions and visualized relationships between features and house prices.
   - Generated correlation matrices to understand feature interactions and their impact on house prices.

3. **Feature Engineering**
   - Examined the importance of each feature in predicting house prices.
   - Created derived features when beneficial to improve the model’s predictive accuracy.

4. **Modeling**
   - Built multiple regression models, such as linear regression and decision tree regression, to predict house prices.
   - Split the data into training and testing sets to evaluate model performance.
   - Tuned hyperparameters to optimize accuracy and avoid overfitting.

5. **Model Evaluation**
   - Evaluated model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
   - Used cross-validation to validate the model and ensure its robustness.

## Results

- The model demonstrates strong predictive accuracy, with low error rates and reliable performance across the evaluation metrics.

## Getting Started

To replicate this analysis:

1. **Install Requirements:** Ensure Python and Jupyter Notebook are installed. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. **Run the Notebook:** Open the Jupyter Notebook and execute each cell to follow the data preprocessing, analysis, and modeling steps.

## Conclusion

This project provides a foundational approach to predicting house prices based on various housing and neighborhood attributes. The model offers valuable insights and can be extended with additional features or refined for increased accuracy, making it a practical tool for real estate analysis and investment planning.
