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
├── Dashboard/

│   └── ANALYTICS.pyix

├── data/

│   └── Car_dataset.csv           # Input car sales dataset

├── notebooks/

│   └── SmartSalesInsights.ipynb # Main exploratory and transformation notebook

└── LICENSE

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
|year          | Year of manufacture                           |
|make          | Car manufacturer (e.g., Toyota, Ford)         |
|model	      | Specific model of the car                     |
|transmission	| Type of transmission (Automatic, Manual)      |
|mileage	      | Odometer reading (total distance traveled)    |
|fuelType	   | Type of fuel (Petrol, Diesel, Electric, etc.) |
|tax           | Tax amount applicable to the vehicle          |
|engineSize    | Engine displacement size (in liters)          |
|price	      | Listed price of the vehicle                   |
|image	      | Image of the specific car                     |
|logo.png	   | Manufacturer's logo image                     |
|month	      | Month of sale or record                       |
|quantity	   | Number of vehicles (inventory or sales)       |
|pct	         | Percentage (context: market share, etc.)      |

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
   ## Plotted Scatter Plot of Car Age vs Selling Price
![image](https://github.com/user-attachments/assets/3451def3-f211-458f-ad72-4b51b2b63c55)

![image](https://github.com/user-attachments/assets/049740c6-ead9-4a56-b239-2dec82ffb90d)
   ##  Computed and Visualized the Correlation Matrix Using a Heatmap
![image](https://github.com/user-attachments/assets/a4458388-09be-44bc-8198-cdb8d2760799)
   ## Plotted the Distribution of Odometer Readings
![image](https://github.com/user-attachments/assets/5ca46311-36bd-4acb-9d66-256f79b29b79)
   ## Plotted Average Selling Price Trends by Year
![image](https://github.com/user-attachments/assets/f54c3cf4-2504-4240-aa31-8f9b0abad5fa)
   ## Visualized Vehicle Condition Distribution Using a Pie Chart
![image](https://github.com/user-attachments/assets/a6d05844-1896-4ca8-89bd-9ec4c5f782aa)

  

---

## 🔮 Future Enhancements

* Train regression models to predict `sellingprice`
* Develop interactive dashboards for exploration
* Integrate with market trend or external automotive data

---


## ✨ Aesthetics & Clarity
Design Choices:

Color Scheme: Sequential blues/reds for quantitative data, categorical for products
Typography: Open Sans font family for readability
Layout: Grid-based dashboard with consistent margins
Responsive Design: Adapts to desktop/tablet viewing
Best Practices Implemented: 
* ✔️ Axis labels with units
* ✔️ Legend positioning top-right
* ✔️ Contrast ratio >4.5:1 for accessibility
* ✔️ Mobile-optimized figure sizes

  ---
## 📊🖱 Interactive Features
This dashboard provides a comprehensive overview of car sales data, combining key performance indicators, brand analysis, and sales trends to deliver actionable insights:

* Brand Logos: Instantly identifies the brands under analysis, enhancing user engagement.

* Units Sold, Total Revenue, Variants: Present high-level metrics that summarize the scale and diversity of the dataset.

* Brand Market Value (Bar Chart): Visualizes which brands generate the most revenue, helping identify market leaders.

* Market Share (Pie Chart): Shows the competitive distribution of sales or revenue among brands, revealing market dominance and competition.

* Images: Offers a visual connection to the products, making the data more relatable.

* Top 5 Models for Revenue (Bar Chart): Highlights the most profitable models, guiding focus toward best-sellers.

* Sales Trend (Line Chart): Tracks sales performance over time, uncovering patterns and informing strategic decisions.

* Each visualization is designed to answer specific business questions:

* Which brands and models are most valuable?

* How is the market share distributed?

* What are the overall sales trends?

* Which products should be prioritized?

* These insights empower stakeholders to make data-driven decisions in sales, marketing, and inventory management.


## 📝 Author

**Prashant Kumar**

Smart Sales Insights – 2025

Contact: [dk9917970@gmail.com](mailto:dk9917970@gmail.com)
