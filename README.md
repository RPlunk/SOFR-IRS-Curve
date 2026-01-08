# SOFR-IRS-Curve

Demonstrating a short end SOFR interest rate swaps curve and risk metrics in [RatesLib](https://rateslib.com/py/en/2.0.x/index.html)

Seeks to evaluate a portfolio of swaps, hedge the portfolio and evaluate performance over the course of a single day. Futures order book data via the databento API is utilized.

Please see this [post](https://rplunk.github.io/2026/01/06/pricing-curve-post.html) for further elucidation 

Other source repos include: [Code Repository for Pricing and Trading IRDs](https://github.com/attack68/book_irds3)

### Structure

**Curve 3_19**: Contains a notebook for a closing curve and portfolio as of March 19th, 2025

**Curve 3_20**: Contains a notebook evaluating PnL over the subsequent day 

**Data**: Contains example notebooks for order book and settlement price retrieval

### Installation

It is recommended to use a virtual environment

```bash
pip install -r requirements.txt
```

### Dependencies

All dependencies are listed in requirements.txt

Each third-party library is the property of its respective authors and is licensed under its own terms.

### Licensing

**Project license**

The original source code in this repository (excluding third-party components) is licensed under the terms of the MIT License, unless otherwise indicated in individual files.

This license applies only to code authored for this repository.
It does **not** override or replace the licenses of any third-party dependencies.

**Third-party licenses**

This project depends on third-party libraries that are distributed under their own licenses (e.g., MIT, BSD, Apache-2.0, Creative Commons, etc.).
By using this project, you are responsible for reviewing and complying with the licenses of those dependencies.
Please refer to:
The requirements.txt file for the list of dependencies.
The respective project pages or distributions for each dependency’s full license text.
