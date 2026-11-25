# Spread Locator: A Statistical Distribution Analysis Model

## 📌 Project Overview
Spread Locator is a statistical analysis project based on e-commerce transaction data. It uses different statistical distributions and techniques to understand transaction amounts, transaction patterns, and data behaviour.

## 🎯 Objectives
- Analyse e-commerce transaction data.
- Study Bernoulli and Binomial distributions.
- Apply the Poisson distribution to daily transaction counts.
- Fit Log-Normal and Pareto distributions.
- Analyse data using Q-Q plots.
- Apply the Box-Cox transformation.
- Calculate Z-scores and probabilities.
- Understand Probability Density Function (PDF) and Cumulative Distribution Function (CDF).

## 📂 Dataset Information
The dataset contains 220 e-commerce transaction records with the following columns:

- transaction_id
- customer_id
- transaction_amount
- transaction_date
- transaction_count
- region
- transaction_status

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

## 📊 Practical Analysis

1. Bernoulli and Binomial Distribution
2. Poisson Distribution
3. Log-Normal and Pareto Distribution
4. Q-Q Plot and Normality Test
5. Box-Cox Transformation
6. Z-Score and Probability Calculation
7. PDF and CDF Analysis

## 📈 Key Findings

- Total records: 220
- Average transaction amount: ₹3,365.19
- Median transaction amount: ₹3,077.72
- Standard deviation: ₹1,985.71
- Minimum transaction amount: ₹804.42
- Maximum transaction amount: ₹20,462.84
- Success transactions: 98
- Failed transactions: 122

The transaction amount data is positively skewed. The Box-Cox transformation reduces the skewness and makes the distribution more symmetric.

The Log-Normal model fits the transaction amount data better than the Pareto model among the two models tested, based on AIC.

## 🖼️ Screenshots and Visualizations

### Practical 1: Bernoulli and Binomial Distribution
![Bernoulli Distribution](Screenshots/Practical_1_Bernoulli.png)

![Binomial Distribution](Screenshots/Practical_1_Binomial.png)

### Practical 2: Poisson Distribution
![Poisson Distribution](Screenshots/Practical_2_Poisson.png)

### Practical 3: Log-Normal and Pareto Distribution
![Lognormal and Pareto](Screenshots/Practical_3_LogNormal_Pareto.png)

### Practical 4: Q-Q Plot
![Q-Q Plot](Screenshots/Practical_4_QQ_Plot.png)

### Practical 5: Box-Cox Transformation
![Box-Cox Transformation](Screenshots/Practical_5_Box_Cox.png)

### Practical 7: PDF and CDF
![PDF](Screenshots/Practical_7_PDF.png)

![CDF](Screenshots/Practical_7_CDF.png)

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open Jupyter Notebook.
3. Load the dataset file.
4. Install the required Python libraries.
5. Run the notebook cells one by one.
6. Observe the graphs and statistical results.

## 📝 Conclusion

This project demonstrates how statistical distributions and techniques can be used to analyse e-commerce transaction data. Different distributions help understand transaction patterns, while Q-Q plots, Box-Cox transformation, Z-scores, PDF, and CDF provide additional insights into the data.

## 👩‍💻 Project Type
Statistics Practical Project

**Project Title:** Spread Locator: A Statistical Distribution Analysis Model
