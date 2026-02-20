# Chi-Squared Test and Pearson Correlation - Group 3

## Course Information
- **Course**: PROG8245 Data Integration Workshop
- **Topic**: Chi-Squared Contingency Test and Pearson Correlation
- **Date**: February 2026

## Team Members
- **Ali** (Group 3)

## Project Description

This Jupyter notebook demonstrates two important statistical concepts used in data science and feature engineering:

### 1. Chi-Squared Contingency Test
- Used to determine if there is a significant association between two categorical variables
- Creates contingency tables from categorical data
- Compares observed vs expected frequencies
- Statistical test for independence between categorical variables

### 2. Pearson Correlation
- Measures the linear relationship between numerical variables
- Range: -1 (negative) to +1 (positive)
- Used to identify and remove redundant features
- High correlation (|r| > 0.7) suggests redundancy

## Datasets Used
- **Titanic Dataset**: For Chi-Squared test examples (Gender vs Survival, Passenger Class vs Survival)
- **Insurance Dataset**: For Pearson correlation examples
- **Auto Dataset**: For feature redundancy removal examples

## How to Run the Notebook

1. **Clone the repository or download the files**
2. **Ensure data files are in place**: The data files should be in `./reference/DataIntegrationWorkshop/data/`
3. **Install requirements**: Run `pip install -r requirements.txt`
4. **Open and run the notebook**: Open `Ali_ChiSquared_Pearson.ipynb` in Jupyter Notebook or JupyterLab

## Requirements

See `requirements.txt` for a list of required Python packages.

## Key Results

### Chi-Squared Test Results
- **Gender vs Survival**: Significant association found (p < 0.001)
  - Women were more likely to survive than men
- **Passenger Class vs Survival**: Significant association found (p < 0.001)
  - Higher class passengers were more likely to survive

### Pearson Correlation Results
- **Insurance Dataset**: No highly correlated features found (threshold > 0.7)
- **Auto Dataset**: Multiple highly correlated features identified
  - Features like `displacement`, `horsepower`, and `weight` show high correlation
  - These redundant features can be removed to simplify models

## Summary

This notebook provides comprehensive examples of:
- Hypothesis testing for categorical variables
- Feature selection and dimensionality reduction
- Data preprocessing techniques
- Visualization of statistical results

## References
- SciPy Documentation: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2_contingency.html
- Pandas Documentation: https://pandas.pydata.org/docs/
- Seaborn Documentation: https://seaborn.pydata.org/

---

**Notebook created by: Ali (Group 3)**
**PROG8245 Data Integration Workshop**
