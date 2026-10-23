# Loan default: exploratory data analysis

An exploratory analysis of a loan dataset, looking at which borrower attributes relate to default (credit risk). It's the groundwork you'd do before building a credit model: understanding the data, cleaning it and deciding which variables are worth keeping.

The notebook and its comments are in Portuguese.

## What's in it

- **Data understanding:** a description of every field and the dataset made consistent.
- **Missing values:** which columns are mostly empty and how to treat them, for example turning missing education into its own "not informed" category instead of dropping rows.
- **Categorical variables:** state, education, marital status, gender and others, with notes on imbalance and on which variables could be dropped to simplify a model or avoid regional bias.
- **Continuous variables:** income, age, fines, interest and loan amounts, with boxplots, skewness and outliers, and a discussion of why removing outliers would throw away useful information.

## Files

- `loan_case.ipynb`: the analysis
- `loan_case.html`: the same notebook rendered, readable without Jupyter
- `dados.xls`, `descricao_dados.xlsx`: the data and its field descriptions

**Stack:** Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter
