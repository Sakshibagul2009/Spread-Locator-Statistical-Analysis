# Spread Locator: A Statistical Distribution Analysis Model

## Project Overview

Spread Locator is a statistical analysis project that studies e-commerce transaction data using different probability distributions and statistical techniques.

The main objective is to understand customer transaction behaviour, analyze transaction amounts, identify data patterns and calculate probabilities using Python.

## Project Objectives

- Understand different statistical distributions.
- Analyze e-commerce transaction data.
- Fit Bernoulli, Binomial and Poisson distributions.
- Compare Log-Normal and Power Law distributions.
- Generate and interpret Q-Q plots.
- Apply Box-Cox transformation.
- Calculate Z-scores and probabilities.
- Plot Probability Density Function (PDF) and Cumulative Distribution Function (CDF).

## Dataset Description

The dataset contains 220 transaction records and 7 columns.

| Column Name | Description |
|---|---|
| transaction_id | Unique transaction ID |
| customer_id | Unique customer ID |
| transaction_amount | Transaction amount in rupees |
| transaction_date | Date of transaction |
| transaction_count | Number of transactions made by a customer in a week |
| region | Customer's geographical region |
| transaction_status | Success or Failure status |

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Statsmodels

## Project Structure

```text
Spread-Locator-Statistical-Analysis/
│
├── spread_locator_dataset.xlsx
├── Spread_Locator_Analysis.ipynb
├── Theory_Notes.pdf
├── README.md
│
└── Screenshots/
    ├── Bernoulli_Binomial.png
    ├── Poisson.png
    ├── LogNormal_Pareto.png
    ├── QQ_Plot.png
    ├── Box_Cox.png
    └── PDF_CDF.png
```

## Part 1: Theoretical Foundation

The following concepts are covered:

1. Statistical Distribution
2. Q-Q Plot
3. Discrete and Continuous Distributions
4. Bernoulli Distribution
5. Binomial Distribution
6. Log-Normal Distribution
7. Power Law Distribution
8. Box-Cox Transformation
9. Poisson Distribution
10. Z-score Probability
11. PDF and CDF

## Part 2: Data Analysis and Testing

The following practical tasks are performed:

1. Fit Bernoulli and Binomial distributions.
2. Fit Poisson distribution to daily transaction counts.
3. Model transaction amounts using Log-Normal and Power Law distributions.
4. Generate and interpret a Q-Q Plot.
5. Apply Box-Cox transformation.
6. Calculate Z-scores and probability of transactions exceeding ₹5,000.
7. Plot and interpret PDF and CDF.
8. Identify the best-fitting distribution.

## Installation and Requirements

Install the required Python libraries:

```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels openpyxl
```

## How to Run the Project

1. Download or clone this repository.
2. Keep the Excel dataset and Jupyter Notebook in the same folder.
3. Install the required libraries.
4. Open Jupyter Notebook.
5. Open `Spread_Locator_Analysis.ipynb`.
6. Run all cells in sequence.

## Key Findings

- Total transactions: 220
- Mean transaction amount: ₹3,365.19
- Median transaction amount: ₹3,077.72
- Standard deviation: ₹1,985.71
- Success rate: 44.55%
- Average daily transactions: 7.10
- Log-Normal AIC: 3821.03
- Pareto AIC: 4083.34
- Box-Cox lambda: -0.1808
- Z-score for ₹5,000: 0.8233

## Conclusion

The analysis shows that transaction amounts are strongly right-skewed.

Based on AIC comparison, the Log-Normal distribution provides a better fit than the fitted Pareto distribution for this dataset.

Box-Cox transformation significantly reduces the skewness of transaction amounts.

This project demonstrates how statistical distributions and probability techniques can help understand e-commerce transaction behaviour and support data-driven decision-making.

## Author

Sakshi bagul

Project: Spread Locator – A Statistical Distribution Analysis Model

Subject: Mathematics & Advanced Statistics
