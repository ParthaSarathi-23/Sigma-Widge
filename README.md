# Sigma-Widge

# Stock Trading Decision Model

This repository contains a Python class named `Model` which represents a simple model for making trading decisions based on stock price movements. Below is an overview of its functionality:

## Initialization

The class initializes with default values for portfolio value, current state, optimal buy indices, and transition counts.

## Return Calculation

The `calculate_returns` method computes the returns based on the current and previous prices.

## Portfolio Value Update

The `update_portfolio_value` method updates the portfolio value based on the trading decision.

## Transition Counts and Probabilities

- The `update_transition_counts` method updates the transition counts between different states.
- The `calculate_transition_probabilities` method computes transition probabilities based on transition counts.

## Trading Decision

The `make_trading_decision` method makes trading decisions based on transition probabilities and the current state. It suggests buying the stock if the probability of price increase is higher; otherwise, it suggests not buying.

## Stock Trading Decision Procedure

This procedure outlines the steps involved in making trading decisions based on stock price movements:

1. **Calculate Returns**: Calculate the returns based on the given formula.
2. **Classify States**: Classify states based on predefined thresholds.
3. **Calculate Transition Probability Matrix**: Calculate the transition probability matrix in a streaming fashion.
4. **Make Trading Decision**: Make trading decisions based on calculated probabilities.
5. **Update Portfolio Value**: Update portfolio value according to trading decisions.
6. **Increase Transition Count**: Increase the transition count for the current state transition.

## How to Use

1. Clone the repository to your local machine.
2. Ensure you have Python installed along with the necessary dependencies listed in the `requirements.txt` file.
3. Utilize the `Model` class to make trading decisions based on stock price movements.




