# Data Analysis for Credit Card Transactions

This project is a Data Analysis of hypothetical transactional data with the objective of creating a AI model to identify fraudulent transactions.

## Project Details

- **transaction_analysis.ipynb**: An overall analizes of the data looking for patterns.

- **transaction_model_v1.ipynb**: Model that uses the columns 'merchant_id', 'user_id', 'device_id' and 'transaction_amount'. ROC AUC Score: 0.9080157354178707.

- **transaction_model_v2.ipynb**: Model that breaks down the 'transaction_date' column in 'day_of_week' and 'hour_of_day' columns. The purpose is to increase the model accuracy. ROC AUC Score: 0.9118684794841379.

## Technologies

- Python 3.12.1
- Jupyter Notebook

## General instructions

1. Clone git repository

```bash
  git clone git@github.com:ANNEBORTOLI/cw-data-fraud--analysis.git
  cd cw-data-fraud--analysis
```

2. Create a virtual environment

```bash
 python -m venv env
```

3. Activate the virtual environment

```bash
 \env\scripts\activate
```

4. Install Dependencies

```bash
  pip install
```

5. Run Jupyter NoteBooks

## :technologist:Developer

- [Github](https://github.com/ANNEBORTOLI)
- [Linkedin](https://www.linkedin.com/in/anne-bortoli/)
- [Blog](https://annebortoli-blog.fly.dev/)
- [E-mail](annebortoli@gmail.com)
