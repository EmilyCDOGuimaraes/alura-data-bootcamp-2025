# alura-data-bootcamp-2025

# 📊 Data Salaries Dashboard

This Streamlit dashboard analyzes global salaries in data-related roles, based on a dataset from the **Alura Python Bootcamp**.

## 🌍 About the dataset
The original dataset (`dados-imersao-final.csv`) is provided in **Portuguese** as part of the bootcamp materials.  
For this project, the dashboard **translates column names and key categorical values dynamically** at load time, so the app displays **all filters, charts, and tables in English** without modifying the original file.

This approach:
- Preserves the original dataset for reference and reproducibility.
- Allows the dashboard to be shared and understood by an international audience.
- Keeps translation logic version-controlled inside `app.py`.

## 🛠 Tech stack
- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) for the dashboard UI
- [Pandas](https://pandas.pydata.org/) for data manipulation
- [Plotly Express](https://plotly.com/python/plotly-express/) for interactive charts

## 🚀 Running locally
```bash
# Clone the repo

# Create virtual environment & activate
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py
