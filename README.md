# blockchain-fraud-detection-ai
AI-based system to detect suspicious blockchain transactions using behavioral and anomaly detection techniques
# Blockchain Transaction Fraud Detection Using AI

## Overview
This project implements an AI-based system to detect suspicious behavior in blockchain transactions. 
Instead of using fixed rules, the system analyzes how wallets behave over time and identifies unusual patterns that may indicate fraud.

## Key Ideas
- Blockchain transactions are transparent but irreversible
- Fraud appears as abnormal wallet behavior rather than single transactions
- AI helps detect unusual patterns without labeled fraud data

## What the System Does
- Analyzes transaction value, frequency, and speed
- Studies wallet behavior such as fund dispersion and balance draining
- Uses anomaly detection to assign a fraud risk score
- Provides simple explanations for why a transaction is flagged

## Techniques Used
- Unsupervised anomaly detection (Isolation Forest, LOF)
- Behavioral and temporal feature engineering
- Wallet interaction analysis
- Explainable risk scoring

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- NetworkX
- Matplotlib
- Google Colab

## Output
- Fraud risk score (0–100)
- Human-readable explanation for suspicious behavior

## Disclaimer
This project identifies potentially suspicious behavior and does not confirm fraud.
It is intended for academic and analytical purposes.
