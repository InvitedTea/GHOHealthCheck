# GHOHealthCheck

Inspired by [xmc2](https://github.com/xmc2)'s https://github.com/xmc2/lfgho_data/ 

Introducing the GHO Stablecoin Monitoring Tool: A cutting-edge platform for real-time tracking and analysis of stablecoin metrics. Stay ahead with our innovative tool! #GHOStablecoin #CryptoAnalytics


# GHO Stablecoin Dashboard

Full DApp local dashboard for GHO Stablecoin stats

## Quickstart

### Install packages using poetry

```shell
pip install poetry==1.4.1
poetry install


Put settings file (".env") into the parent directory.
Example defines all required parameters,
including the external web3 provider.

Other settings, such as contract addresses, are set in settings.

Run project locally

### Run project locally

```shell
streamlit run Dashboard.py
```

Dashboard will be available at http://localhost:8502 (browser opens automatically).

## Features
Features
Deployments, contract addresses for Controllers, AMMs, and other relevant contracts.
Total debt, total collateral, and price statistics for GHO.
Plots for GHO/USD and interest rates.
Tools for monitoring positions, health, and potential losses.


