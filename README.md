## L2T13 - Supervised Learning - Linear Regression
## Insurance and Diabetes Regression Analysis

### Overview

This task involves performing regression analysis on two datasets: insurance.csv and diabetes.csv. The goal is to analyze how certain variables affect insurance costs and predict a person's progression in the condition of diabetes using various attributes.

### Instructions
### Setup and Installation

1. **Clone the Repository**
   - Clone this repository to your local machine using:
     ```
     git clone https://github.com/vswapna3202/L2T13.git
     ```

2. **Navigate to the Task's Folder**
   - Navigate to the folder containing the task:
     ```
     cd L2T13 or cd <your-task-folder>
     ```

3. **Install Dependencies**
   - Ensure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/).
   - Install Jupyter Notebook to run the provided notebooks. You can install it using pip:
     ```
     pip install notebook
     ```
   - Install required libraries such as `scikit-learn` for machine learning and `pandas` for data manipulation. You can install them using pip:
     ```
     pip install scikit-learn pandas
     ```
#### Insurance Regression Analysis

1. **Creating the Notebook**
   - Create a Jupyter notebook named `insurance_regression.ipynb`.

2. **Importing Data**
   - Import the dataset `insurance.csv` into your notebook. You can find the dataset [here](<insurance.csv>).

3. **Analyzing Age vs. Insurance Costs**
   - Use the relevant columns to determine how age affects insurance costs:
     - Plot a scatter plot with age on the x-axis and charges on the y-axis.
     - Fit a linear regression model to the data using `linear_model.LinearRegression()` from `sklearn`.
     - Make predictions on the data.
     - Plot another scatter plot with the best-fit line.

#### Diabetes Regression Analysis

1. **Creating the Notebook**
   - Create a Jupyter notebook named `diabetes_regression.ipynb`.

2. **Importing Data**
   - Read the dataset `diabetes.csv` into your Jupyter notebook. You can find the dataset [here](<diabetes.csv>).

3. **Data Preprocessing**
   - Differentiate between the independent variables and the dependent variable and assign them to variables x and y.
   - Generate training and test sets comprising 80% and 20% of the data, respectively.
   - Use `MinMaxScaler` and `StandardScaler` from `sklearn.preprocessing`. Fit these scalers on the train set and use them to transform the train and test sets.

4. **Model Training and Evaluation**
   - Generate a multiple linear regression model using the training set. Use all of the independent variables.
   - Print out the intercept and coefficients of the trained model.
   - Generate predictions for the test set.
   - Compute R-squared for your model on the test set using `r2_score` from `sklearn.metrics`.
