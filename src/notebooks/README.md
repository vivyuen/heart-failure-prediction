# 📓 Notebooks

Directory contains the Jupyter notebooks for analyzing the heart failure prediction dataset.

### 1. Data Cleaning (`01_data_cleaning_heart_failure.ipynb`)
- Initial data loading and inspection
- Data cleaning steps:
  - Removed records with invalid Cholesterol (0)
  - Removed records with invalid RestingBP (0)
  - Reduced dataset from 918 to 746 records

### 2. Data Visualization (`02_data_visualization.ipynb`)
- Uses cleaned data from notebook 1
- Created visualizations:
  - Age distribution by heart disease status
  - Correlation heatmap of key features
  - Gender distribution analysis
- Saved visualizations to `data/figures/`