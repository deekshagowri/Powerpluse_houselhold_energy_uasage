# PowerPulse: Household Energy Usage Forecast

PowerPulse is a machine learning project that predicts household electricity consumption using historical power usage data. The project implements various regression models to forecast energy consumption patterns, helping both consumers and energy providers make informed decisions about power usage.

## Project Overview

This project analyzes household power consumption data to create predictive models for energy usage. It includes comprehensive data preprocessing, feature engineering, and the implementation of multiple regression models including Linear Regression, Random Forest, and Gradient Boosting.

## Features

- Data preprocessing and cleaning of household power consumption data
- Feature engineering including temporal features and rolling averages
- Implementation of multiple regression models
- Detailed visualization of energy consumption patterns
- Model performance evaluation using RMSE, MAE, and R-squared metrics
- Feature importance analysis

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/PowerPulse.git

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dataset

The project uses the Individual Household Electric Power Consumption dataset, which includes measurements of:
- Global active power
- Global reactive power
- Voltage
- Global intensity
- Sub-metering (1, 2, and 3)

## Model Performance

The project implements three regression models:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

Models are evaluated using RMSE, MAE, and R-squared metrics to ensure accurate predictions.

## Usage

```python
# Run the main analysis script
python power_pulse_project.py
```

## Project Structure

- `power_pulse_project.py`: Main script containing all analysis and modeling code
- `README.md`: Project documentation
- `/visualizations`: Directory containing generated plots and visualizations
- `/models`: Directory containing trained models

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Scikit-learn for machine learning models
- Matplotlib and Seaborn for visualization
- NumPy for numerical computations

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss proposed changes.
