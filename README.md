# Smart Sales Insights: Predict, Analyze, Grow

A comprehensive, modular data analysis pipeline for a car sales dataset that performs cleaning, feature engineering, visualization, and exploratory insights for sales performance.

---

## 🚀 Quick Start

1. **Run the notebook:**

   ```bash
   jupyter notebook notebooks/SmartSalesInsights.ipynb
   ```

---

## 📁 Project Structure


Smart-Sales-Insights/

├── data/

│   └── car_sales.csv           # Input car sales dataset

├── notebooks/

│   └── SmartSalesInsights.ipynb # Main exploratory and transformation notebook

└── README.md                   # This file



---

## 🔄 Processing Pipeline

The notebook executes the following steps:

1. **Data Loading** - Load car sales dataset from CSV
2. **Initial Inspection** - Basic dataset info and null value check
3. **Data Cleaning** - Missing value imputation and column formatting
4. **Duplicate & Integrity Check** - VIN duplicates and invalid data
5. **Feature Engineering** - Derived columns like price difference
6. **Encoding & Transformation** - Label encoding, normalization
7. **Outlier Detection** - Identify and handle extreme values
8. **Visualization** - Generate meaningful exploratory plots
9. **Summary Statistics** - Descriptive stats by brand, model, year

---

## 📊 Dataset Description

| Feature      | Description                                   |
| ------------ | --------------------------------------------- |
| year         | Year of manufacture                           |
| make         | Car manufacturer (e.g., Toyota, Ford)         |
| model        | Specific model of the car                     |
| trim         | Trim level or version (e.g., Sport, SE)       |
| body         | Body type (e.g., SUV, Sedan)                  |
| transmission | Type of transmission (Automatic, Manual)      |
| vin          | Vehicle Identification Number (unique ID)     |
| state        | U.S. state where the car was sold             |
| condition    | Condition score of the vehicle (numeric)      |
| odometer     | Mileage at the time of sale                   |
| color        | Exterior color                                |
| interior     | Interior type or color                        |
| seller       | Dealership or seller name                     |
| mmr          | Manheim Market Report price (estimated value) |
| sellingprice | Actual sale price of the vehicle              |
| saledate     | Date of the sale                              |

---

## ✅ Project Objectives

* **Data Cleaning**: Handle missing values, remove duplicates
* **Feature Engineering**: Create new features like `price_diff = sellingprice - mmr`
* **Data Validation**: Fix formats, standardize fields like `saledate`, `vin`, etc.
* **Descriptive Statistics**: Summarize price, mileage, condition by make/year
* **Trend Analysis**: Identify seasonal or temporal sales trends
* **Outlier Management**: Detect and cap or remove extreme values
* **Visualization**: Create plots for insights:

  * Price distribution
  * Odometer vs. Selling Price
  * Time series trends
  * Correlation heatmaps

---

## 🧰 Tools & Technologies

* **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
* **Environment**: Jupyter Notebook
* **Preprocessing**: Label encoding, scaling, outlier handling

---

## 📈 Output & Insights

* Cleaned, analysis-ready dataset
* Top-selling makes, models, and best-performing conditions
* Exploratory visuals and pattern recognition
* Foundation laid for building predictive models
![image](https://github.com/user-attachments/assets/3451def3-f211-458f-ad72-4b51b2b63c55)
![image](https://github.com/user-attachments/assets/049740c6-ead9-4a56-b239-2dec82ffb90d)
![image](https://github.com/user-attachments/assets/a4458388-09be-44bc-8198-cdb8d2760799)
![image](https://github.com/user-attachments/assets/5ca46311-36bd-4acb-9d66-256f79b29b79)
![image](https://github.com/user-attachments/assets/f54c3cf4-2504-4240-aa31-8f9b0abad5fa)
![image](https://github.com/user-attachments/assets/a6d05844-1896-4ca8-89bd-9ec4c5f782aa)

  

---

## 🔮 Future Enhancements

* Train regression models to predict `sellingprice`
* Develop interactive dashboards for exploration
* Integrate with market trend or external automotive data

---

## 📝 Author

**Prashant Kumar**

Smart Sales Insights – 2025

Contact: [dk9917970@gmail.com](mailto:dk9917970@gmail.com)
