# 💄 Beauty Products Supply Chain Analysis

A comprehensive data analytics project that explores a beauty products supply chain dataset to uncover business insights using **Python, Pandas, Matplotlib, Seaborn, and Scikit-learn**. The project combines exploratory data analysis (EDA), statistical correlation analysis, data visualization, and machine learning to evaluate supplier performance, customer preferences, logistics efficiency, and the factors influencing manufacturing costs and lead times.

---

## 📌 Project Overview

Supply chain optimization is critical for improving operational efficiency and customer satisfaction. This project analyzes a beauty products supply chain dataset to identify trends, evaluate supplier performance, understand customer purchasing behavior, and determine the key drivers affecting manufacturing costs and lead times.

The analysis includes descriptive statistics, correlation analysis, interactive visualizations, and a Decision Tree Regressor for feature importance analysis.

---

## 📂 Project Structure

```
├── Beauty_Products_Supply_Chain_Analysis.ipynb
├── supply_chain_data.csv
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains information related to:

- Product Type
- Supplier Information
- Manufacturing Costs
- Shipping Costs
- Order Quantities
- Transportation Modes
- Routes
- Customer Demographics
- Revenue
- Lead Time
- Defect Rates
- Product Cost

---

## 🔍 Project Workflow

### 1. Data Preparation

- Loaded the dataset using Pandas
- Performed exploratory data analysis
- Checked data types and descriptive statistics
- Verified missing values
- Encoded categorical variables using One-Hot Encoding

---

### 2. Correlation Analysis

Two statistical methods were used:

#### Pearson Correlation
- Identified linear relationships between variables.
- Filtered significant correlation coefficients.

#### Spearman Correlation
- Identified monotonic relationships.
- Compared feature relationships independent of linearity.

---

### 3. Exploratory Data Analysis

The project includes multiple visualizations to understand different aspects of the supply chain.

#### 📍 Product Quantities by Location
- Bar chart showing sales quantities across different locations.

#### 👥 Customer Demographics vs Product Types
- Pie charts showing purchasing preferences among customer segments.

#### 🏭 Supplier Defect Rates
- Comparison of average defect rates across suppliers.

#### 🚚 Transportation Analysis
- Stacked bar charts showing order quantities across routes and transportation modes.

#### ⏳ Supplier Lead Time Analysis
- Average manufacturing lead time by supplier and product type.

#### 💰 Manufacturing Cost Distribution
- Box plots comparing manufacturing costs across product categories.

#### 💲 Product Cost Analysis
- Box plots showing product cost variation among product types.

#### 📦 Shipping Cost vs Order Quantity
- Scatter plots illustrating shipping cost trends for different carriers.

#### 📈 Revenue by Customer Demographics
- Pie chart showing revenue contribution from different customer groups.

---

## 🤖 Machine Learning

A **Decision Tree Regressor** was implemented to determine the most influential features affecting:

- Product Cost
- Manufacturing Lead Time

Feature importance scores were extracted to identify the top contributing variables for each prediction target.

---

## 📈 Key Insights

- Female customers predominantly purchase skincare and cosmetic products.
- Male customers show a higher preference for haircare products.
- Supplier 5 exhibits the highest average defect rate.
- Supplier 1 maintains the lowest defect rate.
- Transportation mode influences order distribution across supply routes.
- Manufacturing lead time varies significantly across suppliers and product categories.
- Decision Tree feature importance highlights the key variables affecting manufacturing costs and lead times.

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/Beauty-Products-Supply-Chain-Analysis.git
cd Beauty-Products-Supply-Chain-Analysis
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

```bash
jupyter notebook Beauty_Products_Supply_Chain_Analysis.ipynb
```

---

## 📷 Visualizations Included

- Bar Charts
- Pie Charts
- Scatter Plots
- Box Plots
- Stacked Bar Charts
- Correlation Heatmaps (if applicable)
- Feature Importance Plots

---

## 🎯 Business Value

This analysis helps businesses:

- Monitor supplier performance
- Identify quality issues
- Understand customer preferences
- Optimize logistics operations
- Reduce manufacturing lead time
- Improve cost efficiency
- Support data-driven supply chain decisions

---

## 📚 Future Improvements

- Predict demand using time-series forecasting
- Build an interactive Power BI/Tableau dashboard
- Implement supplier risk scoring
- Forecast inventory requirements
- Compare multiple machine learning models for improved prediction accuracy

---

## 👨‍💻 Author

**Anmol Nayak**

- B.Tech Civil Engineering, NIT Rourkela
- Minor in Computer Science
- Interested in Data Analytics, Machine Learning, and Supply Chain Analytics

---
