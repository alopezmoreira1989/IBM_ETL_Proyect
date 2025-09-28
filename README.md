**ETL Pipeline – IBM Data Engineering Foundations**

This project was developed as part of the IBM Data Engineering Foundations course. It demonstrates a complete ETL (Extract, Transform, Load) process in Python using World Bank GDP data.

**📌 Project Overview**

Extract: Load raw GDP data from a CSV file.

Transform:

Rename and normalize columns

Handle missing values

Convert currencies and standardize values

Aggregate GDP data by country

Load: Save the processed dataset into a SQLite database for structured storage and analysis.

**🛠️ Technologies Used**

Python 3

Jupyter Notebook

Pandas

NumPy

SQLite3

**📂 Project Structure**
├── ETL.ipynb      # Jupyter Notebook containing the ETL pipeline
├── data.csv       # Raw GDP dataset (source)
├── etl.db         # SQLite database with cleaned data (output)
└── README.md      # Project documentation

**🚀 How to Run**

Clone the repository:

git clone https://github.com/alopezmoreira1989/IBM_ETL_Proyect.git
cd IBM_ETL_Proyect


Install dependencies:

pip install pandas numpy


Open the notebook:

jupyter notebook ETL.ipynb


Run all cells to execute the ETL pipeline.

**📖 Learning Outcomes**

Built an end-to-end ETL pipeline with Python

Gained hands-on experience in data wrangling and cleaning

Learned how to store structured data in a relational database

Practiced data engineering best practices with real-world data

**👨‍💻 Author**

Created by Alejandro López Moreira during the IBM Data Engineering Foundations course.
