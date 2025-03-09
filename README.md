# US Tariffs: Financial Impact on US Companies

This project analyzes the financial impact of US tariffs on US companies using time series and regression models. It focuses on two specific companies, Beam Inc. (BEAM) and Steel Dynamics Inc. (STLD), and uses historical stock data from `yfinance` to build predictive models and assess potential financial implications.

## Project Overview

The project involves the following steps:

1. **Data Collection and Preparation:** Historical stock data for BEAM and STLD is downloaded using `yfinance`.
2. **Feature Engineering:** Features such as daily returns, volatility, and lagged returns are calculated from the stock data.
3. **Model Selection and Training:** Four models are explored:
   * **Linear Regression:** A baseline regression model.
   * **Random Forest:** A more complex regression model.
   * **ARIMA:** A time series model to capture trends and seasonality.
   * **Prophet:** A robust forecasting model for handling data irregularities.
4. **Visualization:** Both static and interactive plots are created to visualize model predictions and compare them to actual stock prices.
5. **Observations:** The model predictions and visualizations are analyzed to gain insights into the potential financial impact of the tariffs on the selected companies.
6. **Conclusion:** The project's findings are summarized, limitations are discussed, and potential future work is suggested.

## Key Findings

* The models generally indicate a potential negative impact of US tariffs on the stock prices of BEAM and STLD.
* Increased volatility in stock prices is also observed during the post-tariff period.
* Counterfactual analysis suggests potential losses for the companies if tariffs had been imposed earlier.
* Industry-specific effects and the companies' exposure to international trade play a role in the impact of tariffs.

## Repository Contents

* `notebook.ipynb`: Jupyter Notebook containing the complete analysis, code, and visualizations.
* `data/`: Directory to store the downloaded stock data (if applicable).
* `requirements.txt`: File listing the project's dependencies.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/us-tariffs-stock-impact.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Open and run the `notebook.ipynb` file in a Jupyter Notebook environment.

## Contributing

Contributions to this project are welcome. Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

* `yfinance` library for providing access to financial data.
* `statsmodels` and `prophet` libraries for time series modeling.
* `scikit-learn` library for regression modeling.
* `matplotlib` and `plotly` libraries for visualization.
