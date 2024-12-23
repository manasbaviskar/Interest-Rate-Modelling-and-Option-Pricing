# Interest-Rate-Modelling-and-Option-Pricing
This project focuses on interest rate modeling and option pricing using advanced numerical techniques. By implementing Monte Carlo simulations and finite difference methods, the project provides a robust framework for pricing bonds and options under various interest rate models, including Vasicek, CIR, and G2++.

## Methodology
### 1. Monte Carlo Simulations
- Developed Monte Carlo frameworks to price bonds and options.
- Implemented the following models:
  - **Vasicek Model**: Captures mean-reverting behavior in interest rates.
  - **Cox-Ingersoll-Ross (CIR) Model**: Incorporates stochastic volatility with mean-reverting rates.
  - **G2++ Model**: Extends the Hull-White framework with two-factor dynamics for increased flexibility.

### 2. Finite Difference Methods
- Applied the **Implicit Finite Difference Method** for solving partial differential equations (PDEs) in the CIR model.
- Benchmarked the numerical results against analytical solutions to validate accuracy and robustness.

## Results
- **Monte Carlo Outputs**: Achieved accurate pricing of bonds and options with convergence to theoretical values for all models.
- **Finite Difference Analysis**: Demonstrated the reliability of the implicit method by achieving high fidelity to analytical solutions in the CIR model.
- **Comparison of Models**: Highlighted the strengths and limitations of each model under varying market conditions.

## Conclusion
This project offers a comprehensive toolkit for interest rate modeling and option pricing, showcasing the efficacy of numerical methods in capturing complex market behaviors. The frameworks and methodologies developed are extendable to other financial instruments and stochastic models.

## Future Work
- Expand the Monte Carlo framework to support multi-factor models and path-dependent options.
- Investigate alternative numerical schemes, such as Crank-Nicolson and explicit methods, for comparative analysis.
- Explore real-world calibration of models using historical market data.

## Acknowledgments
Gratitude to the academic and financial modeling communities for insights and resources that supported this project.
