# Models Directory

This directory contains all trained models and their artifacts.

## Directory Structure

### Logistic Regression
- `LR_best_model_all.pkl`: Model trained on all features
- `LR_best_model_baseline.pkl`: Model trained on baseline features only

### Neural Networks
- `best_baseline_model.keras`: Neural network using only baseline features
- `best_complete_model.keras`: Neural network using all features

### XGBoost
- `xgboost_model.pkl`: Best performing XGBoost model

## Model Performance Summary

| Model | Baseline Features | All Features |
|-------|------------------|--------------|
| Logistic Regression | 76% (77% recall) | 85% (83% recall) |
| XGBoost | 81% (77% recall) | 92% (89% recall) |
| Neural Network | 77% (90% recall) | 91% (92% recall) |