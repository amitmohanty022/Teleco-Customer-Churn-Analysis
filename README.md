# Telco Customer Churn Analysis

Exploratory data analysis of about 7,000 telecom customers, to find out **who leaves (churns) and why**. Built with Pandas, Matplotlib and Seaborn. A PDF summary of the findings is included (`Teleco Customer Churn Analysys.pdf`).

## Key findings
- **26.54%** of customers have churned.
- Churn is the same for male and female customers, so gender is not a factor.
- New customers (1–2 months) churn the most. Long-term customers stay.
- **Month-to-month** contracts churn far more than 1- or 2-year contracts.
- Customers with PhoneService, DSL internet and OnlineSecurity churn less.
- Customers paying by **electronic check** churn more than those using card or automatic bank transfer.

## How to run (step by step)

You need **Python 3.10 or newer** ([download](https://www.python.org/downloads/)). No API key is needed, and the dataset (`Customer Churn.csv`) is included.

**1. Download the project**

```bash
git clone https://github.com/amitmohanty022/Teleco-Customer-Churn-Analysis.git
cd Teleco-Customer-Churn-Analysis
```

**2. Create a virtual environment and activate it**

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

**3. Install the requirements**

```bash
pip install -r requirements.txt
```

**4. Start Jupyter and run the notebook**

```bash
jupyter notebook Teleco_Customer_Churn_Analysis.ipynb
```

Choose **Run → Run All Cells**. All charts are produced in the notebook.

### Running in Google Colab instead
Open https://colab.research.google.com → **File → Upload notebook**, upload `Customer Churn.csv` with the 📁 **Files** panel, then **Runtime → Run all**.

## Files

| File | Purpose |
|---|---|
| `Teleco_Customer_Churn_Analysis.ipynb` | The analysis notebook |
| `Customer Churn.csv` | Dataset (7,043 customers) |
| `Teleco Customer Churn Analysys.pdf` | Summary report |
