# Aave V2 Wallet Credit Scoring System

## Overview

This system provides credit scores (0-1000) for Aave V2 wallets based on their transaction behavior patterns. The scores help identify:

- Responsible long-term users (700-1000)
- Moderate risk wallets (300-699)
- High-risk/bot-like behavior (0-299)

## Key Features

- **Behavioral Clustering**: Identifies distinct user archetypes
- **Risk Prediction**: Estimates default probability using Gradient Boosting
- **Network Analysis**: Examines protocol interactions
- **Anomaly Detection**: Flags suspicious wallets
- **Stress Testing**: Simulates market downturns
- **Explainable AI**: SHAP values show score factors

