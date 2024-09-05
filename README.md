# Options Implied Volatility

## Introduction

This repository contains a Jupyter Notebook for calculating the implied volatility (IV) of options. Implied volatility is an essential metric in options trading, representing the market's expectations of the future volatility of the underlying asset. The notebook uses numerical methods to extract implied volatility from options prices, providing a practical tool for traders and analysts.

## Features

- **Implied Volatility Calculation**: Computes the implied volatility of options using the Newton-Raphson method.
- **Jupyter Notebook**: Interactive and easy-to-follow notebook format, allowing you to modify and experiment with the code.
- **Customizable Inputs**: Allows input customization, such as stock symbol, strike price, expiration date, and market price.
- **Visualization**: Includes visualizations to help understand the results and the behavior of implied volatility.

## Requirements

To install the necessary Python packages, run:

```bash
pip install -r requirements.txt
```

Alternatively, you can manually install the main dependencies:

```bash
pip install numpy pandas matplotlib scipy
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/MathQuantLab/options-implied-volatility.git
cd options-implied-volatility
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Implied_Volatility_Calculator.ipynb
```

3. Modify the inputs in the notebook (stock symbol, strike price, expiration date, etc.) and run the cells to compute the implied volatility.

## Cloud Deployment

Although the project is currently based on a local Jupyter Notebook, it can be easily adapted for cloud environments such as Google Colab, AWS, or Azure for real-time calculation and monitoring.

## Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the GPL-3.0 License.
