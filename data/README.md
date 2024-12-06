# Data Directory

This directory contains all datasets used in the heart failure prediction project.

## Directory Structure

- `processed/`: Contains cleaned and preprocessed datasets
  - `cleaned_heart_data.csv`: Final preprocessed dataset with removed zero values and encoded categorical variables
  
- `raw/`: Contains original, unmodified data
  - `heart.csv`: Original heart failure prediction dataset from Kaggle

## Data Description

The heart failure dataset contains 11 clinical features:
- Demographics: Age, Sex
- Baseline/Pre-Stress Test: ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG
- Stress Test: MaxHR, ExerciseAngina, Oldpeak, ST_Slope
- Target: HeartDisease (binary classification)

## Data Cleaning Notes
- No missing values or null values in original dataset
- 130 records with zero values in Cholesterol and RestingBP were removed
- Categorical variables were encoded using one-hot encoding