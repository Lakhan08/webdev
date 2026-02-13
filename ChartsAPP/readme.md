# 📊 Sales Dashboard -- Streamlit App

This project is a Sales Dashboard built using Python, Streamlit, Pandas,
and Matplotlib.\
It allows users to upload a CSV file and visualize sales data with
filters and charts.

------------------------------------------------------------------------

## 🚀 Features

-   Upload CSV file
-   Sidebar filters (Region & Product)
-   View raw and filtered data
-   Bar chart → Region-wise Sales
-   Pie chart → Product-wise Sales Distribution
-   Responsive layout

------------------------------------------------------------------------

## 🛠️ Requirements

-   Python 3.8+
-   pip
-   Virtual Environment (recommended)

------------------------------------------------------------------------

# ⚙️ Installation & Setup Guide

## 1️⃣ Install Python

Download Python from: https://www.python.org/downloads/

Verify installation: python --version

------------------------------------------------------------------------

## 2️⃣ Create Virtual Environment

python -m venv 04venv

------------------------------------------------------------------------

## 3️⃣ Activate Virtual Environment

On Windows: 04venv`\Scripts`{=tex}`\activate`{=tex}

Or: source 04venv/Scripts/activate

If activated using cd: cd .. cd ..

------------------------------------------------------------------------

## 4️⃣ Install Dependencies

pip install -r appReq.txt

------------------------------------------------------------------------

## 5️⃣ Run the Streamlit App

streamlit run app.py

Open in browser: http://localhost:8501

------------------------------------------------------------------------

# 📂 Project Structure

project-folder/ │ ├── Chartsapp.py ├── appReq.txt ├── README.md └──
04venv/

------------------------------------------------------------------------

# 📄 Expected CSV Format

Region, Product, Sales

Example:

Region,Product,Sales North,Laptop,120000 South,Mobile,70000
East,Tablet,30000

------------------------------------------------------------------------

# 🧹 Deactivate Virtual Environment

deactivate

------------------------------------------------------------------------

# 🧑‍💻 Technologies Used

-   Python
-   Streamlit
-   Pandas
-   Matplotlib
