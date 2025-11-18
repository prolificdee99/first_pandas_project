# Sales Data Analysis with Pandas

## 📋 Description

This project is a capstone exercise using Pandas to analyze sales data for an online store. It explores revenue, product performance, sales trends over time, and city-level insights. The goal is to practice real-world data analysis workflows with Pandas.

## 📊 Dataset

The dataset contains fictional sales records with the following columns:

- **OrderID**: Unique identifier for each order
- **Customer**: Customer name
- **Product**: Product name
- **Category**: Product category
- **Quantity**: Number of units sold
- **Price**: Unit price
- **OrderDate**: Date of order
- **City**: Customer's city
- **Revenue**: Calculated as Quantity × Price

## 🎯 Analysis Tasks

The analysis covers the following key areas:

1. **Revenue Analysis**
   - Revenue per order
   - Revenue by product category
   - Revenue by city

2. **Product Performance**
   - Top-selling products by quantity
   - Top products by revenue

3. **Temporal Analysis**
   - Sales trends over time
   - Daily revenue patterns

4. **Geographical Analysis**
   - Revenue distribution across cities
   - Regional performance insights

## 📈 Visualizations

The project includes the following charts and visualizations:

- **Line Chart**: Revenue trend over time
- **Bar Chart**: Revenue distribution by city
- **Pie Chart**: Revenue share by category (optional)
- **Summary Statistics**: Key metrics and insights

## 💡 Key Insights

### Major Findings:
- **Electronics** generated the highest revenue among all categories
- **Books** were the top-selling product by quantity
- **Paris** emerged as the top-performing city by revenue
- **January 7th** recorded the peak revenue day

### Business Implications:
- Electronics category shows highest profitability
- Books category demonstrates high volume sales potential
- Paris market shows strongest purchasing power
- Early January indicates seasonal sales peak

## 🚀 How to Run

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Google Colab

### Installation & Execution

**1.** **Open the notebook:**
   ```bash
   # For Google Colab: Upload the notebook and run
   # For local Jupyter: 
   jupyter notebook sales_analysis.ipynb

**2. Install dependencies:**
pip install pandas matplotlib
Run the analysis:
Open the notebook in your preferred environment
Run all cells sequentially to reproduce the analysis
Results and visualizations will be displayed inline

##Quick Start in Google Colab:
# Clone the repository
!git clone https://github.com/prolificdee99/first_pandas_project.git

# Navigate to project directory
%cd first_pandas_project
# Install requirements
!pip install pandas matplotlib
# Run the analysis notebook
from IPython.display import display
import pandas as pd
import matplotlib.pyplot as plt

##🔮 Future Work
Planned Enhancements:
Dataset Expansion
Add more records for comprehensive analysis
Include additional columns (customer demographics, product ratings)
Advanced Analysis
Monthly and weekly trend analysis
Seasonal pattern detection
Customer segmentation analysis
Predictive modeling for sales forecasting
Visualization Improvements
Integrate Seaborn for advanced visualizations
Create interactive dashboards with Plotly
Generate automated reports
Feature Additions
Automated data cleaning pipeline
Export functionality for reports
Comparative analysis across time periods

🤝 Contributing
Contributions and suggestions are welcome! Feel free to:
Report issues or bugs
Suggest new analysis features
Improve existing visualizations
Add new datasets for comparison
📄 License
This project is open source and available under the MIT License.
Author: Prolific Dee
GitHub: @prolificdee99
Project Link: https://github.com/prolificdee99/first_pandas_project
