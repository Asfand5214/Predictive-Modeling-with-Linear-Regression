## Predictive Modeling with Linear Regression

### Overview

This Jupyter Notebook demonstrates the process of building and evaluating a predictive model using Linear Regression. The model is applied to a dataset with randomly generated features and target variables. Key steps include data preprocessing, model training, evaluation, and interpretation of results.

### Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- pandas
- scikit-learn

### Usage

1. Ensure you have Python and Jupyter Notebook installed on your system.
2. Install the required libraries by running `pip install numpy pandas scikit-learn`.
3. Download the `Predictive-Modeling-with-Linear-Regression.ipynb` notebook file.
4. Launch Jupyter Notebook and open the notebook file.
5. Execute each cell sequentially to run the code and observe the results.
6. Follow the instructions and comments provided within the notebook for guidance.

### Notebook Contents

1. **Data Generation**: Random data with two features (`X`) and a target variable (`y`) is generated. The target variable `y` is created based on a linear relationship with noise.

2. **Data Preprocessing**: The data is split into training and testing sets. No significant preprocessing is required as the data is randomly generated.

3. **Model Training**: A linear regression model is initialized and trained on the training data.

4. **Prediction**: The trained model is used to make predictions on both the training and testing sets.

5. **Model Evaluation**: The performance of the model is evaluated using two metrics:
    - **Root Mean Squared Error (RMSE)**: This measures the average deviation of predicted values from the actual values.
    - **R-squared (R²) Score**: This measures the proportion of the variance in the dependent variable that is predictable from the independent variables.
