MN Laptop Price Analysis Project
📑 Project Overview
This project focuses on analyzing a dataset of laptops to understand key factors influencing their prices. It involves cleaning messy data, performing feature extraction, handling missing values and outliers, and preparing the data for further analysis or modeling.

🧰 Tools & Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📊 Key Steps Performed
Data Loading
Loaded laptop data from a CSV file into a Pandas DataFrame.

Data Cleaning

Removed or replaced missing values using statistical techniques like mean, mode, backfill, and forward fill.

Dropped unnecessary columns and handled inconsistent formats in features like Ram and Weight.

Feature Engineering

Extracted CPU brand, series, and clock speed from the Cpu column.

Converted memory units (GB, kg) into numerical formats for analysis.

Outlier Detection and Handling

Used box plots and interquartile range (IQR) method to identify and handle outliers in features such as Inches and Price.

Data Visualization

Created insightful plots using Seaborn and Matplotlib to explore distributions and relationships in the data.

📌 Project Goals
Clean and transform raw data into a reliable format.

Gain insights from price trends based on laptop specifications.

Prepare data for future machine learning modeling.

📁 Dataset Columns (Sample)
Company

TypeName

Inches

Cpu

Ram

Memory

Gpu

OpSys

Weight

Price

📈 Next Steps (Optional)
Apply regression models to predict laptop prices.

Build an interactive dashboard using Power BI or Excel.
