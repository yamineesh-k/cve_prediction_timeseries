# Predicting Monthly Software Vulnerability (CVE) Disclosure Trends for 2024

This repository contains a Python-based machine learning project that aims to predict the monthly count of CVEs (Common Vulnerabilities and Exposures) for the year 2024. The model utilizes a SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous Regressors) approach to analyze historical trends and generate forecasts.

Key Features:

NVD Data Integration: Leverages the widely-used NVD (National Vulnerability Database) data feed v1.1 as the model's primary data source.

Data Visualization: Generates visualizations to explore seasonality and trends. Specifically includes ACF, Polar, Decomposition Plots.

Time Series Forecasting: Employs SARIMAX, a powerful time series modeling technique, to capture seasonal patterns and trends in CVE disclosure data.


Project Structure:

data/: Contains the NVD data files used for training and evaluation.

notebooks/: Includes Jupyter Notebooks with detailed code walkthroughs and results.

images/: Includes the Data Visualizations generated from the project.

README.md (this file): Provides an overview of the project and its contents.

Dependencies:

pandas
numpy
statsmodels
sklearn
matplotlib
seaborn
plotly
Installation:

Clone this repository: git clone https://github.com/yamineesh-k/cve_prediction_timeseries.git

Install dependencies: pip install -r requirements.txt

Getting Started:

Navigate to the notebooks/ directory.
Open the main notebook (cve_prediction_timeseries.ipynb) in Jupyter Notebook or a similar environment.
Follow the instructions within the notebook to execute the code and explore model results.

Contributions and Suggestions:

Welcome contributions and suggestions! 
Please reach out to me on Linkedin at https://www.linkedin.com/in/yamineesh