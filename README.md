# Asset Pricing

This project reviewed and implemented various classical pricing models, including Capital Asset Pricing Model (CAPM), Factor Models, Options Pricing, etc.

* **Yaping Wang** email:  yaping.wang@barcelonagse.eu

## Getting Started

Clone this repository and run R Studio/Jupyter Notebook.
```
git clone https://github.com/yapingw/asset_pricing.git
```

## Table of Content
- **Portfolio Optimization**
    - Mean Variance Optimization: [Rmd](https://github.com/yapingw/asset_pricing/tree/master/src/Mean_Variance_Optimization)
    - CAPM and Factor Models: [Rmd](https://github.com/yapingw/asset_pricing/tree/master/src/CAPM_factor_models)
 - **Option Pricing**
    - Delta hedging and implied volatilities: [Jupyte Notebook](https://github.com/yapingw/asset_pricing/tree/master/src/DeltaHedging_ImpliedVolatilities.ipynb)
      - Simulating stock prices with Brownian Motion
      - Pricing call options with simulated data, using Black-Scholes solution
      - Computing delta hedging error under Black-Scholes model
      - Computing the implied volatility using Newton's method
    - Barrier and Asian Options: [Jupyte Notebook](https://github.com/yapingw/asset_pricing/tree/master/src/Barier_Asian_Options.ipynb)
      - Pricing Barrier options 
      - Pricing Asian options Monte Carlo 
- **Interest rates derivatives**
    - Vasicek model: [Jupyte Notebook](https://github.com/yapingw/asset_pricing/tree/master/src/vasicek.ipynb)
      - Pricing bonds with Vasicek model for interest rates
      - Obtaining different patterns for yields curve

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/yapingw/asset_pricing/blob/master/LICENSE) file for details


## Todos

 - Add more implementations on pricing models
 - Write better remarks