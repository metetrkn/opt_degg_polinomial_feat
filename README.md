# Sales Prediction using Linear and Polynomial Regression

    This repository contains a Python script that demonstrates the use of linear regression and polynomial regression for sales prediction based on advertising data. The dataset contains information on the amount of money spent on TV, radio, and newspaper advertisements, as well as the resulting sales.

## Dependencies

    Python 3.6 or later
    numpy
    pandas
    scikit-learn
    matplotlib
    pyforest
    joblib

    You can install the required dependencies using the following command:

    for linux, bash;

    $ pip install numpy pandas scikit-learn matplotlib pyforest joblib

## How to use

    Clone the repository.
    Run the script sales_prediction.py in your Python environment.

## The script will:

    Load the dataset and display the first few rows.
    Split the data into independent (X) and dependent (y) features.
    Perform linear regression and compute the mean absolute error (MAE) and root mean squared error (RMSE).
    Perform polynomial regression for degrees 1 through 5, comparing the test and training dataset errors.
    Choose the optimal degree for polynomial regression (based on the error vs. degrees plot).
    Train the final model using the optimal degree for polynomial regression.
    Save the trained model and polynomial converter as .joblib files.
    Load the saved model and converter, and use them to predict sales for a new advertising campaign.

## Example output

    The script will output the linear MAE, linear RMSE, and a plot of errors versus degrees for polynomial regression. The optimal degree will be used to train the final model, and a prediction will be made for a new advertising campaign.

    linear MAE: 1.2137457736144808
    linear RSME: 1.9307843822347201

    Errors vs. Degrees Plot

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
