# Commodity Price Forecasting

This project is an implementation of the analysis and modeling pipeline for the competitive data science project conducted as part of the **Datavidia 2025** competition, specifically titled **"Commodity Price Prediction, Penyisihan Datavidia 9"**

Forecasting temperature rise using machine learning regression and statistical forecasting models. This project aims to predict future commodity price changes by analyzing climate-related variables and external economic indicators. The data used includes global commodity prices, historical food prices, Google Trends data, and currency exchange rates.

## Business Understanding

With increasing volatility in global food markets, accurately forecasting commodity prices is crucial for policymakers, businesses, and researchers. This project addresses the need to develop predictive models that estimate future food commodity prices using historical trends, market conditions, and economic indicators. Accurate forecasts can support data-driven decision-making, enhance food security, and reduce the risks associated with price fluctuations.

## Data Overview

The dataset comprises multiple collections compiled from reliable sources to support the analysis of food price trends, global market behavior, and currency fluctuations. The Food Price folder serves as the core dataset, containing historical price data for various commodities across 34 Indonesian provinces.

The Global Commodity Price data provides supplementary data on commodities across sectors such as energy, metals, and food.
The Google Trend data offers insights into public interest and consumer behavior by tracking keyword search patterns related to commodities and economic sectors.
The Currency data contains historical exchange rate movements collected from central banks and foreign exchange markets.

Further information and metadata can be found at: [[Kaggle Competition](https://www.kaggle.com/competitions/warmup-datavidia/data)].

In addition to the provided data, external open-source datasets were also used, including monthly inflation data and monthly import-export statistics of Indonesia, to enrich the model with macroeconomic context and improve prediction accuracy.

## Evaluation Metrics
Mean Absolute Percentage Error (MAPE)

![image](https://github.com/user-attachments/assets/b07a6580-c153-4c70-95db-18227529e9c8)

## Installation
### Local
1. Install dependencies (recommended using virtualenv or conda):
```
pip install -r requirements.txt
```
2. Run Forecasting.ipynb

### Jupyter Notebook
1. Launch Forecasting.ipynb
