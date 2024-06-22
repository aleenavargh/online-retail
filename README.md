# online-retail
# Online Retail Exploratory Data Analysis and Classification

## Overview

This project involves analyzing an online retail dataset to understand customer purchasing behavior and applying various classification models to predict certain outcomes. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and the application of machine learning models.

## Dataset

The dataset used in this project is an online retail dataset, which includes the following features:
- `Description`: Product description
- `Quantity`: Quantity of each product per transaction
- `InvoiceDate`: Date and time of the invoice
- `UnitPrice`: Price per unit of the product
- `CustomerID`: Unique identifier for each customer
- `Country`: Country where the customer resides

## Project Structure

The project is structured as follows:
├── data
│ ├── online_retail.csv # Raw data
├── notebooks
│ ├── data_preprocessing.ipynb # Data cleaning and preprocessing
│ ├── exploratory_data_analysis.ipynb # EDA
│ ├── model_training.ipynb # Model training and evaluation
├── src
│ ├── data_preprocessing.py # Data preprocessing functions
│ ├── eda.py # EDA functions
│ ├── model_training.py # Model training functions
├── README.md # Project overview and instructions
└── requirements.txt # Python packages and dependencies

## Setup

To set up the project on your local machine, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone (https://github.com/aleenavargh/online-retail.git)
    cd online-retail
    ```

2. **Create a virtual environment and activate it:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the notebooks:**

    Open Jupyter Notebook and run the notebooks in the `notebooks` directory.

## Data Preprocessing

The data preprocessing step involves the following tasks:
- Removing missing values
- Encoding categorical variables
- Scaling numerical features

## Exploratory Data Analysis (EDA)

In the EDA step, we analyze the distribution of various features, identify patterns, and visualize relationships between different variables. Key findings from the EDA are documented.

## Model Training and Evaluation

We apply several classification models to predict customer purchasing behavior. The models used include:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- AdaBoost

Hyperparameter tuning is performed using GridSearchCV to find the best parameters for each model. The performance of the models is evaluated using accuracy, precision, recall, and F1-score.

## Future Work

Future improvements to the project could include:
- Further feature engineering to create more predictive features
- Applying more advanced models like neural networks
- Conducting deeper analysis on customer segments

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

