# Quantitative Finance for Mathematicians: The Black-Scholes-Merton Framework 📈📐

[![LaTeX](https://img.shields.io/badge/LaTeX-47494E?style=for-the-badge&logo=latex&logoColor=white)]()
[![Finance](https://img.shields.io/badge/Quantitative_Finance-0052CC?style=for-the-badge)]()
[![Stochastic Calculus](https://img.shields.io/badge/Stochastic_Calculus-008000?style=for-the-badge)]()

## Overview
This repository contains a rigorous mathematical exposition of financial derivative pricing, specifically focusing on the valuation of European call options. 

Most finance textbooks assume you already understand the business, while most mathematics textbooks treat the financial intuition as trivial. **This project bridges that gap.** Developed specifically for a mathematical audience, it provides a step-by-step derivation of the Black-Scholes-Merton framework, translating fundamental economic concepts, such as market efficiency, arbitrage, and hedging, into the formal language of stochastic calculus.

📄 **[Read the full PDF Document here](BlackScholes_RiskNeutralMeasure.pdf)**

## Key Topics Covered
The document is structured to build intuition sequentially, culminating in the probabilistic resolution of the option pricing problem:

* **Financial Derivatives & Replicating Portfolios:** Formalizing the concepts of underlying assets, payoffs, and self-financing portfolios in continuous time.
* **Geometric Brownian Motion (GBM):** Modeling asset dynamics using Stochastic Differential Equations (SDEs) and understanding the unobservable nature of the real-world drift ($\mu$).
* **The Black-Scholes PDE:** Deriving the partial differential equation through dynamic hedging and the application of **Itô's Lemma**.
* **Risk-Neutral Valuation:** Applying **Girsanov's Theorem** to perform a change of probability measure (from physical $P$ to risk-neutral $Q$), effectively neutralizing market risk.
* **Analytical Solutions:** A complete, step-by-step integration in the appendix to compute the discounted expected payoff and arrive at the famous Black-Scholes formula.

## Real-World Limitations (Stylized Facts)
Beyond the theoretical beauty of the model, this project explicitly addresses the discrepancies between the Black-Scholes assumptions and real-world market dynamics, including:
- **Volatility Skew:** The failure of constant implied volatility ($\sigma$).
- **Fat Tails & Skewness:** Positive excess kurtosis and negative skewness in real-world equity returns versus the theoretical Log-Normal distribution.

## About Compilation
To compile the `.tex` file locally, ensure you have a standard LaTeX distribution installed (like TeX Live or MiKTeX) along with the `biber` backend for the bibliography. Use the compiler `pdfLaTeX`
