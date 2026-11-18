# E-commerce Customer Behavior Analysis

**Exploratory Data Analysis and Customer Insights using Python**

An MSc Data Analytics project exploring customer demographics, shopping behavior, spending patterns, platform preferences and satisfaction through statistical analysis and data visualization.

## Dataset

The original analysis used 100 customer records and 14 attributes, including age, gender, monthly income, spending score, website visits, cart additions, purchases, average purchase value, session duration, ratings, total spending, platform and product category. Dataset provenance has not been confirmed. The supplied original CSV is included in `data/`. Confirm permission to publish it before making the repository public.

## Analytical workflow

- Dataset inspection and missing-value checks
- Descriptive statistics and univariate analysis
- Outlier detection using box plots
- Bivariate and multivariate analysis, cross-tabulation and correlation
- Twenty descriptive and comparative business questions
- Visualizations using Pandas, Matplotlib and Seaborn

## Key findings

| Metric | Result in the original analysis |
|---|---|
| Customers | 100 |
| Average age | 36.14 years |
| Total spending | INR 1,152,472 |
| Most used platform | Amazon (28 customers) |
| Most purchased category | Electronics (59 purchases) |
| Five-star ratings | 22 customers |
| More than three purchases | 27 customers |
| Correlation: visits and purchases | -0.11 |
| Correlation: average purchase value and total spending | 0.66 |

## Business implications

- Investigate barriers between browsing and purchasing rather than assuming more visits lead to more sales.
- Review feedback among higher-spending customers with lower ratings.
- Explore category demand and customer preferences before planning campaigns.

## Run locally

Use Python and install the dependencies:

```bash
python -m pip install -r requirements.txt
```

The supplied CSV is already inside `data/`. From the repository root, launch:

```bash
jupyter notebook Ecommerce_Customer_Analysis.ipynb
```

Run cells in order. Existing outputs are retained from the original analysis; key numerical findings were independently checked against the supplied CSV. All 35 code cells were also executed successfully in order in a non-interactive Python environment.

## Limitations

This is exploratory analysis of a small sample, not a representative market study. Correlation does not establish causation. No predictive model is trained. Dataset origin and redistribution permissions must be verified. Findings should not be generalized to the wider e-commerce market.
