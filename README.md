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
<img width="707" height="567" alt="Practical_1_Bernoulli png" src="https://github.com/user-attachments/assets/29c64543-d471-43a9-be3a-fa6798b3949c" />

<img width="715" height="567" alt="Practical_1_Binomial png" src="https://github.com/user-attachments/assets/622e3cb7-3f30-43f9-bc3b-e3d42c387d03" />


### Practical 2: Poisson Distribution
<img width="720" height="570" alt="Practical_2_Poisson png" src="https://github.com/user-attachments/assets/95cd6f9e-f8b4-4970-a9a0-b1e0363161f9" />

### Practical 3: Log-Normal and Pareto Distribution
<img width="742" height="567" alt="Practical_3_LogNormal_Pareto png" src="https://github.com/user-attachments/assets/7362419d-febf-43ff-a449-612513b322e0" />


### Practical 4: Q-Q Plot
<img width="740" height="572" alt="Practical_4_QQ_Plot png" src="https://github.com/user-attachments/assets/75e7a096-84c2-446f-88b6-641e6a10a7e2" />


### Practical 5: Box-Cox Transformation
<img width="1240" height="490" alt="Practical_5_Box_Cox png" src="https://github.com/user-attachments/assets/4498c5ae-6550-49c1-82d4-f0b4a00396ee" />

### Practical 6: Z-Score
<img width="531" height="172" alt="Practical_6_Z_Score png" src="https://github.com/user-attachments/assets/26ae3d48-1bef-40d0-bb42-2cd3d27095a6" />

### Practical 7: PDF and CDF
<img width="1031" height="510" alt="Practical_7_PDF png" src="https://github.com/user-attachments/assets/5c6cafad-3dd4-489c-9573-0832ab7a24fe" />

<img width="1000" height="513" alt="Practical_7_CDF png" src="https://github.com/user-attachments/assets/1dba284c-1b90-47c3-97e8-b54af5abeaff" />

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
