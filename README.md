# Sales and Product Prediction Models

## Overview

This project involves the development of multiple predictive models aimed at forecasting future sales and product prices using historical data. The models are built using various machine learning techniques, with the goal of enhancing decision-making processes related to inventory management, marketing strategies, and financial planning. The datasets used in this project span various domains, including retail, automotive sales, e-commerce, real estate, and technology.

## Project Structure

The project is structured around six datasets, each representing a unique domain. For each dataset, a specific predictive model is developed, trained, and evaluated. The Python scripts for these models are hosted in a GitHub repository, and the output of the models is demonstrated in a YouTube video. 

### Datasets

1. **BigMart Sales Data**:
   - Description: Historical sales data from a retail company.
   - Objective: Predict future sales to optimize inventory and marketing efforts.

2. **Car Sales Data**:
   - Description: Data on car sales over a period.
   - Objective: Forecast future car sales for better resource allocation and budgeting.

3. **E-commerce Product Dataset 1 & 2**:
   - Description: Two datasets containing product details and sales data from an e-commerce platform.
   - Objective: Predict product prices and sales to assist in pricing strategy and stock management.

4. **Housing Data**:
   - Description: Real estate data including house prices and features.
   - Objective: Predict future housing prices for investment and sales strategy.

5. **Laptop Sales Data**:
   - Description: Data on laptop sales and features.
   - Objective: Forecast future laptop prices to inform pricing and marketing strategies.

### Methodology

For each dataset, the following steps were taken:

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing or standardizing features as required.

2. **Model Training**:
   - Linear Regression and Random Forest models were trained on the preprocessed data.
   - The models were evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).

3. **Prediction and Evaluation**:
   - Future sales or prices were predicted using the trained models.
   - The performance of each model was assessed and compared.

### Results

The results of the predictive models are saved in separate Python scripts. The key metrics and predictions are displayed within the scripts. The output demonstrates the effectiveness of each model in predicting future trends based on the historical data provided.

## Installation and Setup

To run the code and reproduce the results, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nandini-asadi/sales-prediction-model.git
   cd aales-prediction-model
   ```

2. **Install Required Packages**:
   Ensure that you have Python 3.x installed. Then, install the required packages:
   ```bash
   pip install pandas scikit-learn
   ```

3. **Run the Scripts**:
   Run the Python scripts corresponding to each dataset:
   ```bash
   python bigmart_sales_prediction.py
   python car_sales_prediction.py
   python ecommerce_product_prediction1.py
   python ecommerce_product_prediction2.py
   python housing_prediction.py
   python laptop_sales_prediction.py
   ```

## Usage

Each script in the repository is designed to load the corresponding dataset, preprocess the data, train the models, and output predictions. The scripts are modular and can be easily adapted for other similar datasets.

## Contributions

Contributions to this project are welcome. Feel free to fork the repository, make your improvements, and submit a pull request. Please ensure that your code adheres to the project's coding standards.

## Contact

For any inquiries or support, please contact:
- **Your Name**
- [LinkedIn](https://www.linkedin.com/in/nandini-asadi-8a4873241/)
- [GitHub](https://github.com/nandini-asadi)