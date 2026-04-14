# SOFE4620 - Credit Card Fraud Detection
Machine Learning and Data Mining — Winter 2026

## Group 11
- Hasaan Rashidi
- Sanzir Anarbaev
- Noah Getachew
- Muhammad Idrees

## Project Overview
This project develops and compares multiple machine learning models for detecting fraudulent credit card transactions using a highly imbalanced real-world dataset. The workflow includes exploratory data analysis, feature engineering, model development, evaluation, and final model comparison.This project aims to develop machine learning models to detect fraudulent credit card transactions using a real-world imbalanced dataset from Kaggle.

## Repository Structure
- `data/raw/` -> location for the original dataset file (`creditcard.csv`)
- `data/processed/` -> processed or engineered datasets such as `creditcard_engineered.csv`
- `notebooks/` -> Jupyter notebooks for EDA, feature engineering, modeling, evaluation, and final comparison
- `notebooks/archive/` -> older or replaced notebook versions kept for reference
- `src/` -> Python scripts and helper functions

## Notes
- Place the original dataset file `creditcard.csv` inside `data/raw/`.
- The engineered dataset can be generated through `GroupPhase_FeatureEngineering.ipynb` and saved to `data/processed/`.
- Archived notebooks are stored in `notebooks/archive/` to keep the main workflow cleaner.
- Evaluation focuses on precision, recall, and F1-score due to class imbalance.