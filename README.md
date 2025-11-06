# ab-test-analysis
A/B test analysis for payment system experiment
# A/B Test Analysis: Payment System Experiment

## 📊 Project Overview
Comprehensive A/B test analysis comparing a new payment system against the current one. The analysis evaluates impact on:
- Conversion rates to paying users
- ARPU (Average Revenue Per User)
- ARPPU (Average Revenue Per Paying User)

## 🎯 Business Question
Does the new payment system significantly improve key revenue metrics compared to the current system?

## 🔍 Methodology
- Statistical hypothesis testing
- Permutation tests for robust mean comparison
- Bootstrap confidence intervals
- Z-test for proportion comparison
- Brunner-Munzel test for median comparison

## 📈 Key Findings
- ✅ **ARPPU**: Significant increase among paying users
- ❌ **ARPU**: No significant overall revenue impact
- ❌ **Conversion**: No significant change in conversion rates

## 🛠 Technical Stack
- Python 3.8+
- Pandas, NumPy (data processing)
- Pingouin, Scipy (statistical tests)
- Matplotlib, Seaborn (visualization)
- Statsmodels (proportion tests)

## 🚀 Quick Start
```bash
# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook ab_test_analysis.ipynb
