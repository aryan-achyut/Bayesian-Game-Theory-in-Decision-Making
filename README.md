# Bayesian Game Theory in Decision-Making: A Statistical Analysis of Predictive Accuracy under Uncertainty

## Overview

This project explores the application of **Bayesian Game Theory** to optimize decision-making in adversarial environments. By leveraging Bayesian strategies, the model aims to find the optimal balance between exploration and exploitation in a competitive scenario. The project demonstrates how to fine-tune hyperparameters such as learning rate, decay factor, and exploration factor to improve the performance of decision-making models under uncertainty.

Key Contributions:
- Utilization of **Bayesian Game Theory** for decision optimization.
- Hyperparameter tuning for the best performance in adversarial games.
- Evaluation of model performance using **AUC (Area Under Curve)** and **accuracy** metrics.

## Project Highlights

- **Best Hyperparameters**: 
  - Learning Rate = 0.1
  - Decay Factor = 0.8
  - Exploration Factor = 0.5
- **Model AUC**: 0.8186 (Significant model performance improvement!)
- **Model Accuracy**: 84%
- **Model Payoff**: 155
- **Adversary Payoff**: 50

## Objective

The goal of this project is to apply **Bayesian Game Theory** to a decision-making scenario where the model interacts with an adversary. The **exploration-exploitation dilemma** is at the core of this project, and hyperparameter tuning helps in optimizing decision-making processes to achieve maximum reward for the model while minimizing the adversary's payoff.

## Hyperparameter Tuning

The following hyperparameters were tuned to find the best performance:
1. **Learning Rate**: Controls the rate at which the model learns from the data.
2. **Decay Factor**: Helps in controlling the rate of decay of the learning rate over time.
3. **Exploration Factor**: Balances between exploration of new strategies and exploitation of known strategies.

## Results

- The model achieved the **highest AUC (0.8186)** when using the hyperparameters:
  - Learning Rate: 0.1
  - Decay Factor: 0.8
  - Exploration Factor: 0.5
- The adversary payoff was 50, while the model's payoff was 155, demonstrating a robust performance in decision-making.

## Files and Structure

- `model.py`: Contains the implementation of the decision-making model and Bayesian updating process.
- `adversary.py`: Defines the adversary’s decision-making logic in the game.
- `hyperparameter_tuning.py`: Script for tuning the learning rate, decay factor, and exploration factor.
- `results/`: Contains the AUC and accuracy results for each set of hyperparameters tested.
- `README.md`: This file, providing an overview of the project and results.

