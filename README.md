# **Global Cost of Living Analysis: Uncovering Trends and Insights from 2024 Mid-Year Data**

---

### **1. Introduction**
In an increasingly globalized world, understanding the cost of living across different regions is crucial for individuals and businesses alike. This report explores global cost of living data from Numbeo’s 2024 mid-year index. By comparing several key metrics such as rent, groceries, restaurants, and local purchasing power to New York City (the baseline), we aim to uncover significant trends and provide insights into which countries offer affordable living, where expenses are highest, and how these factors impact local purchasing power.

**Dataset Source**:  
The data used in this project was sourced from [Numbeo](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp), an extensive and reliable source for cost of living data globally. This data was downloaded from [Kaggle](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024).

---

### **2. Objectives**
The goals of this analysis include:
1. **Identify global trends** in cost of living, rent, groceries, and restaurant expenses.
2. **Compare regions and countries** to uncover significant differences in cost of living.
3. **Analyze the relationship** between local purchasing power and the cost of living.
4. **Provide actionable insights** for individuals (expats, travelers) and businesses (salary adjustments for international employees).

---

### **3. Data Overview**
The dataset includes the following key indices:
- **Cost of Living Index (Excl. Rent)**: Measures relative prices of consumer goods such as groceries, transportation, and utilities compared to New York City.
- **Rent Index**: Estimates the relative cost of renting apartments in various cities.
- **Cost of Living Plus Rent Index**: Combines consumer goods and rent expenses for a more comprehensive comparison.
- **Groceries Index**: Relative cost of groceries in different cities.
- **Restaurants Index**: Compares the prices of meals in restaurants.
- **Local Purchasing Power**: Reflects the purchasing power of residents based on average net salaries compared to New York City.

Each index is relative to New York City, with an index of 100 representing parity with NYC.

---

### **4. Methodology**
The data was analyzed in **Python** using popular libraries such as **Pandas**, **Matplotlib**, and **Seaborn** for data manipulation and visualization. Key metrics were evaluated using summary statistics, correlation analysis, and data visualizations.

1. **Data Cleaning**: Checked for missing values, ensured consistency, and transformed raw data into usable formats.
2. **Data Visualization**: Visualizations were created to highlight global cost of living differences, such as heat maps for geographic distribution, bar charts for category comparison, and scatter plots for correlations.
3. **Statistical Analysis**: Conducted correlation and trend analysis to uncover relationships between cost of living indices and local purchasing power.

---

### **5. Analysis and Findings**

#### **5.1. Global Cost of Living Trends**
We analyzed global cost of living data relative to New York City and visualized the **Cost of Living Index (Excl. Rent)** across regions. Notable findings include:
- **Top 5 Most Expensive Countries**: Switzerland, Norway, Iceland, Denmark, and Luxembourg ranked highest in cost of living, all exceeding New York City.
- **Most Affordable Countries**: India, Pakistan, and Egypt had some of the lowest cost of living indices, with costs 60-80% lower than New York City.

![Global Heatmap of Cost of Living Index](#)  
*Figure 1: Global Heatmap of Cost of Living Index (Excl. Rent)*

#### **5.2. Rent Index and Cost of Living Plus Rent**
Rental prices show significant variation across regions:
- **High Rent Countries**: Hong Kong, Singapore, and Switzerland were at the top with rental prices significantly higher than New York City.
- **Affordable Rent Countries**: Countries like India, Tunisia, and Bolivia have rent prices that are less than 20% of NYC’s rent costs.

![Bar Chart of Rent Index by Region](#)  
*Figure 2: Rent Index Distribution by Region*

#### **5.3. Groceries and Restaurants**
The **Groceries Index** and **Restaurants Index** provided insight into daily expenses:
- **Europe**: Countries like Switzerland and Norway show a high cost of groceries and eating out, contributing to their high overall cost of living.
- **Southeast Asia**: Despite higher restaurant costs in cities like Singapore, groceries remain more affordable relative to Western countries.
  
![Comparison of Groceries and Restaurants Index](#)  
*Figure 3: Groceries vs. Restaurants Index Comparison*

#### **5.4. Local Purchasing Power and Cost of Living**
A key finding of this analysis is the inverse relationship between **Local Purchasing Power** and the **Cost of Living Plus Rent Index** in several countries:
- **Higher Purchasing Power**: Countries such as the United States, Australia, and Switzerland allow residents to maintain higher purchasing power despite high living costs.
- **Lower Purchasing Power**: Countries like Indonesia and Pakistan have low purchasing power, with residents struggling to afford everyday goods despite low living costs.

![Scatter Plot: Purchasing Power vs. Cost of Living](#)  
*Figure 4: Local Purchasing Power vs. Cost of Living*

---

### **6. Insights and Recommendations**

#### **6.1. For Expats and Travelers**
- **Affordable Living**: Countries in South Asia and parts of Latin America offer a significantly lower cost of living, making them ideal for budget-conscious travelers and expats.
- **High Costs in Europe**: Switzerland and Norway may offer high standards of living, but expats should prepare for high costs, particularly for rent and everyday goods.

#### **6.2. For Businesses**
- **Salary Adjustments**: Companies operating globally need to adjust salaries based on local cost of living and purchasing power. High-rent countries like Hong Kong will require higher salaries to maintain the same standard of living as in New York City.
- **Relocation Recommendations**: For employees relocating, destinations like Southeast Asia offer lower costs while maintaining a reasonable quality of life.

#### **6.3. For Governments**
- **Wage Policy Adjustments**: Governments in countries with low local purchasing power but rising living costs should consider adjusting minimum wage policies to help residents cope with increasing expenses.

---

### **7. Conclusion**
This project demonstrates how analyzing cost of living data can reveal valuable insights for individuals, businesses, and governments alike. The global variations in rent, groceries, and local purchasing power highlight the complex nature of affordability across different regions. Moving forward, this analysis can be extended by including historical data to uncover cost of living trends over time or integrating additional variables such as economic growth and inflation rates.

---

### **8. Tools Used**
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn
- **Visualization Platform**: Tableau or Power BI (optional for dashboard creation)

---

### **9. Future Work**
- **Historical Data Analysis**: Analyze trends over time to forecast future changes in cost of living and rent prices.
- **Deeper Correlation Analysis**: Incorporate more variables (e.g., inflation rates, employment rates) to understand what drives living costs.
- **Interactive Dashboard**: Build an interactive dashboard for users to explore the data in real-time.

---

#### **10. References**

- [Kaggle](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024)
- [Numbeo: Cost of Living Index](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp)
- [Methodology](https://www.numbeo.com/common/motivation_and_methodology.jsp)
