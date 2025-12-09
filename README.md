# bshw-heston-szhw-dashboard

## Overview

Interactive Streamlit dashboard for analyzing advanced hybrid financial models that combine stochastic volatility with stochastic interest rates. The app provides real-time pricing, risk analysis, and visualization tools built around four core model families implemented in `models.py.`

--------------------------------------------------------------

## Features

### Model Coverage

- BSHW Model: Black–Scholes with Hull–White stochastic rates
- Heston–HW Model: Heston stochastic volatility with Hull–White rates
- SZHW Model: Schöbel–Zhu stochastic volatility with Hull–White rates
- Diversification Products: Stylized structured products with hybrid dynamics and correlation scenarios

### Technical Capabilities

- Real-time parameter controls with immediate visualization (via Streamlit UI)
- Monte Carlo path simulation with CIR-based variance dynamics
- Implied volatility–style sensitivity curves for SZHW
- Parameter sensitivity analysis across key volatility and correlation parameters
- Martingale checks for model validation (Heston–HW)
- Diversification payoff and relative price profiles under different correlations

## Installation

### Requirements

Install dependencies with:

````
pip install streamlit numpy matplotlib scipy pandas
````
