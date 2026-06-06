


                            ####What is Do in this Porject.####



# Airbnb Data Cleaning and Analysis Project

This project focuses on cleaning, preprocessing, and analyzing a massive Airbnb dataset containing over 100,000 listings. The goal is to handle missing data, remove duplicates, fix data types, and prepare the dataset for meaningful visualization.

## 📊 Dataset Overview
* **Total Rows:** 101,410 listings (after duplicate removal)
* **Price Range:** \$50.00 to \$1,200.00
* **Average Price:** \$625.38
* **Key Locations:** New York City boroughs (Manhattan, Brooklyn, Queens, Bronx, Staten Island)

## 🧹 Data Cleaning Process
To ensure data quality, the following steps were performed in the notebook:
1. **Removing Unnecessary Columns:** Dropped columns with excessive missing data, such as `license` and `house_rules`.
2. **Handling Duplicates:** Identified and removed duplicate rows to prevent skewed analysis.
3. **Data Type Conversion:** Stripped currency symbols (`$`) and commas from the `price` and `service fee` columns to convert them into numeric formats for calculations.

## 🚀 How to Run the Project

### Prerequisites
Make sure you have Python installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn.