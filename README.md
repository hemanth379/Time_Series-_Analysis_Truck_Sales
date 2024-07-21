# Time Series Analysis for Truck Sales

## Project Overview
This project focuses on forecasting truck sales using historical data from 2003 to 2014 to predict sales for the years 2015 and 2016. Utilizing various time series models, this analysis helps in understanding seasonal trends and forecasting future sales, thereby aiding strategic planning and decision-making.

## Project Details
- **Instructor:** Professor Zinovy Radovilsky
- **Course:** BAN 673 – 01 Time Series Analytics
- **Group Members:** Krutarth Sompura, Manan Upadhyay, Hemanth Varma Pericherla, Priyadarshini Madhusudanan, Vaishnavi Karingala
- **Date:** March 10, 2024

## Data Source
The dataset, derived from Kaggle, comprises monthly truck sales data from January 2003 to December 2014. This rich dataset facilitates a detailed exploration of temporal sales patterns, essential for the accurate forecasting of future trends.

## Repository Structure
- `data/`: CSV file containing the truck sales data used for the analysis.
- `scripts/`: R scripts used for applying and evaluating various time series models.
- `docs/`: Contains the full project report and additional documentation.
- `figures/`: Graphs and plots visualizing data trends and model performance.

## Models Evaluated
1. **Regression Model with Linear Trend and Seasonality**
2. **Holt-Winters Model**: Identified as the most effective model based on RMSE and MAPE metrics.
3. **Quadratic Trend and Seasonality Model**
4. **Auto ARIMA**

## Key Findings
- The Holt-Winters model outperformed other models in terms of accuracy with the lowest RMSE and MAPE values.
- Seasonal trends indicate peak sales mid-year with a decline towards the end.
- High autocorrelation across monthly sales data points to significant seasonality.

## Usage
To replicate the analysis or apply the models to different data:
1. Ensure R and necessary libraries are installed.
2. Run the scripts located in the `scripts/` directory.

## How to Contribute
Interested in contributing? Fork the repo and propose your changes via a pull request.

## References
- Kaggle Dataset: [Dummy Truck Sales for Time Series](https://www.kaggle.com/datasets/ddosad/dummy-truck-sales-for-time-series/data)

## Acknowledgments
Special thanks to our course instructor, Professor Zinovy Radovilsky, for guidance and insights throughout the project.
