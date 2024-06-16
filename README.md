## Bitcoin Price Prediction Project

### Overview
Bitcoin Price Prediction with ARIMA and N-BEATS
This project focuses on predicting Bitcoin prices using two distinct approaches: ARIMA and N-BEATS. The dataset is sourced from CoinDesk, and we leverage TensorFlow, statsmodels, and other libraries for time series analysis and modeling.

### Background
Time series forecasting is a critical business problem with significant financial impact. Classical statistical approaches often outperform machine learning and deep learning methods in this domain. The M4 competition highlighted this disparity, with most top-ranking methods being ensembles of classical techniques. However, a hybrid approach that combines deep learning with classical models, such as Holt-Winters, has shown promise, leading to further exploration of pure deep learning architectures for improved forecasting accuracy and interpretability.
### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bitcoin-price-prediction.git
    cd bitcoin-price-prediction
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Data
The dataset is downloaded from CoinDesk and contains Bitcoin prices from October 2013 to May 2021.

### ARIMA Model
The ARIMA model is used for time series forecasting. We search for the best parameters and fit the model on the training data.

### N-BEATS Model
N-BEATS is a neural network architecture for time series forecasting.


### Evaluation
We evaluate the models using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE).

### Results
The generic DL approach performs exceptionally well on heterogeneous univariate TS forecasting problems using no TS domain knowledge.
It is viable to additionally constrain a DL model to force it to decompose its forecast into distinct human interpretable outputs.
### Usage
1. To run the project, clone the repository and install the dependencies as described above.
2. Run the Jupyter notebook or Python script provided in the repository.
