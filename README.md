**Customer Purchase Analysis**
**Project Overview**

This project performs statistical analysis on customer purchase data. The analysis focuses mainly on the PurchaseAmount column and examines customer spending patterns, differences between groups, relationships between categorical variables, and the distribution of purchase amounts.

The analysis is performed using Python, mainly with Pandas, NumPy, Matplotlib, Seaborn, and SciPy.

**Dataset**

The dataset contains the following columns:

CustomerID – Unique identifier for each customer
Gender – Customer gender
Region – Customer region
PurchaseAmount – Amount spent by the customer
ProductCategory – Category of the purchased product
Churn – Whether the customer has churned (Yes/No)
CampaignGroup – Email campaign group (A/B)

The PurchaseAmount column contains some missing values. These missing values are removed when performing statistical tests and analysis that require actual purchase

**Libraries Used**
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import (
    ttest_ind,
    chi2_contingency,
    f_oneway,
    shapiro,
    probplot
)

**Conclusion**

This analysis provides insights into customer spending behavior using descriptive statistics, hypothesis testing, probability distributions, and confidence intervals.

The analysis includes:

Measures of central tendency
Outlier detection
Skewness and kurtosis
Independent t-test
Chi-square test
One-way ANOVA
Campaign comparison
Normality analysis
Central Limit Theorem
95% confidence interval
