# Carbon Emission Futures Price Prediction

## Overview

This project examines the prediction of **carbon emission futures prices** using traditional time-series modelling and machine learning techniques. The objective is to compare the predictive performance of the **ARIMA model** with several machine learning models capable of capturing complex and potentially nonlinear patterns in the data.

## Models Used

The study compares the following approaches:

* **ARIMA (AutoRegressive Integrated Moving Average)**
* **Random Forest Regressor**
* **Gradient Boosting Regressor**
* **K-Nearest Neighbours (KNN)**
* **Decision Tree Regressor**

## Data & Variables

The analysis incorporates economic and environmental variables relevant to carbon emission futures prices, including:

* GDP
* Per-capita carbon emissions
* Carbon emission futures prices

Variables originally available at non-monthly frequencies, such as GDP and per-capita carbon emissions, were **interpolated to a monthly frequency** to align them with the modelling framework.

## Methodology

The project follows a comparative modelling approach:

1. Prepare and preprocess the relevant economic and environmental variables.
2. Convert selected variables to a monthly frequency through interpolation.
3. Develop an **ARIMA** model as a traditional time-series benchmark.
4. Train multiple machine learning regression models.
5. Evaluate and compare model performance using metrics including **R²** and **Mean Squared Error (MSE)**.
6. Identify the model with the strongest predictive performance.

## Results

Among the models evaluated, the **Random Forest Regressor** achieved the best predictive performance. It outperformed the other machine learning models as well as the traditional ARIMA model, achieving a **higher R² score and lower MSE**.

This suggests that machine learning models, particularly Random Forest, can capture complex patterns in carbon emission futures prices that may not be adequately captured by traditional linear time-series approaches.

## Key Takeaways

* Machine learning provides a useful alternative to traditional time-series modelling for carbon futures price prediction.
* **Random Forest Regressor** produced the strongest predictive performance among the models examined.
* Economic and environmental variables such as **GDP and per-capita carbon emissions** can be incorporated into the prediction framework.
* Comparing traditional econometric models with machine learning models provides a broader perspective on forecasting performance.

## Reference

The project is based on the research presented in:

**A Study on the Carbon Emission Futures Price Prediction**

[Read the research paper on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0959652624037582)

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Statsmodels
* Matplotlib / Seaborn

## Disclaimer

This repository is intended for **academic and research purposes** and should not be interpreted as financial advice or a recommendation to trade carbon emission futures.
