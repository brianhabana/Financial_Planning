# Financial Planning
This is a jupyter notebook accomplished two tasks:

Part 1: A financial planner for emergencies. The members of a firm are able to use this tool to visualize their current savings. The members can determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool  forecasts the performance of a member's retirement portfolio in 30 years and 10 years. To do this, the tool makes an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [MCForecastTools ](https://pypi.org/project/forecast-tools/) - forecast-tools has been developed to support forecasting education and applied forecasting research. It is MIT licensed and freely available to practitioners, students and researchers via PyPi. There is a long term plan to make forecast-tools available via conda-forge.

* [JSON](https://github.com/apis-json/api-json) - Ability to read JSON files from API calls


* [Alpaca](hhttps://alpaca.markets) - Alpaca SDK used to import historical ticker data

---

## Installation Guide

Before running the application first install the following dependencies.

```python
conda install -c anaconda requests
conda install -c jmcmurray json
pip install python-dotenv
pip install alpaca-trade-api

```

---

## Usage

This is for research purposes only


---

## Contributors

Brought to you by UC Berkeley Extension

---

## License

MIT
