# Credit-Card-Fraud-EDA-Visualization-

This project involves analyzing a dataset of financial transactions to detect fraudulent activities. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to uncover patterns related to fraudulent transactions.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project aims to analyze and visualize fraudulent transactions to uncover patterns and insights. The analysis covers various aspects such as:

- Merchant fraud rates
- Fraud rates by city and state
- Time of day and month with high fraud rates
- Fraudulent transaction patterns based on job descriptions and age groups

## Data

The dataset used in this project is a CSV file (`fraud_data.csv`) containing transaction details with the following columns:

- `trans_date_trans_time`: Date and time of the transaction
- `merchant`: Merchant name
- `category`: Transaction category
- `amt`: Amount of the transaction
- `city`: City of the transaction
- `state`: State of the transaction
- `lat`: Latitude of the transaction location
- `long`: Longitude of the transaction location
- `city_pop`: Population of the city
- `job`: Job description of the customer
- `dob`: Date of birth of the customer
- `trans_num`: Transaction number
- `merch_lat`: Latitude of the merchant's location
- `merch_long`: Longitude of the merchant's location
- `is_fraud`: Fraudulent transaction indicator (1 for fraud, 0 for non-fraud)

## Installation

To run this project, you'll need Python and the following libraries:

```sh
pip install pandas numpy seaborn matplotlib folium
```

## Usage

1. Clone this repository:
    ```sh
    git clone https://github.com/your-username/fraud-detection-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd fraud-detection-analysis
    ```
3. Place the `fraud_data.csv` file in the project directory.
4. Run the analysis script:
    ```sh
    python analysis.py
    ```

## Visualizations

### 1. Merchant Fraud Rates

![Merchant Fraud Rates](images/merchant_fraud_rates.png)

### 2. City Fraud Counts and Rates

![City Fraud Counts](images/city_fraud_counts.png)
![City Fraud Rates](images/city_fraud_rates.png)

### 3. Fraudulent Transactions by Hour and Month

![Fraudulent Transactions by Hour](images/fraudulent_transactions_hour.png)
![Fraudulent Transactions by Month](images/fraudulent_transactions_month.png)

### 4. Fraud by Job and Age Group

![Fraud by Job](images/fraud_by_job.png)
![Fraud by Age Group](images/fraud_by_age_group.png)

### 5. Fraud Map Visualization

A geographical map visualizing the locations of transactions:

```python
m.save('map_from_dataframe_123.html')
```

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your improvements or fixes.

