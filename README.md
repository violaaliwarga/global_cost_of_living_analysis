# **Global Cost of Living Analysis: Uncovering Trends and Insights from 2024 Mid-Year Data**


### **1. Introduction**
In an increasingly globalized world, understanding the cost of living across different regions is crucial for individuals and businesses alike. This report explores global cost of living data from Numbeo’s 2024 mid-year index. By comparing several key metrics such as rent, groceries, restaurants, and local purchasing power to New York City (the baseline), we aim to uncover significant trends and provide insights into which countries offer affordable living, where expenses are highest, and how these factors impact local purchasing power.

**Dataset Source**:  
The data used in this project was sourced from [Numbeo](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp), an extensive and reliable source for cost of living data globally. This data was downloaded from [Kaggle](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024).


### **2. Objectives**
The goals of this analysis include:
1. **Identify global trends** in cost of living, rent, groceries, and restaurant expenses.
2. **Compare regions and countries** to uncover significant differences in cost of living.
3. **Analyze the relationship** between local purchasing power and the cost of living.
4. **Provide actionable insights** for individuals (expats, travelers) and businesses (salary adjustments for international employees).


### **3. Data Overview**
The dataset includes the following key indices:
- **Cost of Living Index (Excl. Rent)**: Measures relative prices of consumer goods such as groceries, transportation, and utilities compared to New York City.
- **Rent Index**: Estimates the relative cost of renting apartments in various cities.
- **Cost of Living Plus Rent Index**: Combines consumer goods and rent expenses for a more comprehensive comparison.
- **Groceries Index**: Relative cost of groceries in different cities.
- **Restaurants Index**: Compares the prices of meals in restaurants.
- **Local Purchasing Power**: Reflects the purchasing power of residents based on average net salaries compared to New York City.

Each index is relative to New York City, with an index of 100 representing parity with NYC.


### **4. Methodology**
The data was analyzed in **Python** using popular libraries such as **Pandas**, **Matplotlib**, and **Seaborn** for data manipulation and visualization. Key metrics were evaluated using summary statistics, correlation analysis, and data visualizations.

1. **Data Cleaning**: Checked for missing values & duplicates and also ensured consistency.
2. **Data Visualization**: Visualizations were created to highlight global cost of living differences, such as heat maps for geographic distribution, bar charts for category comparison, and scatter plots for correlations.
3. **Statistical Analysis**: Conducted correlation and trend analysis to uncover relationships between cost of living indices and local purchasing power.


### **5. Analysis and Findings**

#### **5.1. Global Cost of Living Trends**
We analyzed global cost of living data relative to New York City and visualized the **Cost of Living Index (Excl. Rent)** across regions. Notable findings include:
- **Top 5 Most Expensive Countries**: Switzerland with index of 101.1, slightly exceeding New York City.
- **Most Affordable Countries**: Pakistan and Libya had some of the lowest cost of living indices, with costs 80% lower than New York City.

<img src="https://github.com/user-attachments/assets/3e94a0ff-560b-42fa-8a84-886bf5c687fa" width="1000">
<br>

#### **5.2. Rent Index and Cost of Living Plus Rent**
Rental prices show significant variation across regions:
- **High Rent Countries**: Singapore with index of 67.2 is the highest rent country, along with Hong Kong and Switzerland.
- **Affordable Rent Countries**: Countries like Bangladesh and Pakistan have rent prices that are less than 97% of NYC’s rent costs.

<img src="https://github.com/user-attachments/assets/ee46cf44-10d5-4dd8-b8f4-b56529e8a149" width="500">
<br>

#### **5.3. Groceries and Restaurants**
The **Groceries Index** and **Restaurants Index** provided insight into daily expenses:
- **Groceries**: Switzerland shows a high cost of groceries and eating out, contributing to its high overall cost of living. It even exceeded NYC by nearly 10%. Whereas Pakistan is the most affordable with index of 17.5.
- **Restaurants**: Switzerland still holds the top rank, but restaurant costs is 4% lower than NYC. With Bangladesh holds the most affordable with more than 80% cheaper than restaurants in NYC.

<img src="https://github.com/user-attachments/assets/b6f213ad-dee0-4751-899c-1e7b2f5398a9" width="500">
<br>

#### **5.4. Local Purchasing Power and Cost of Living**
A key finding of this analysis is the inverse relationship between **Local Purchasing Power** and the **Cost of Living Plus Rent Index** in several countries:
- **Higher Purchasing Power**: Countries such as the Luxembourg, Kuwait, and Qatar allow residents to maintain higher purchasing power especially with low-medium living costs.
- **Lower Purchasing Power**: Countries like Cuba and Syria have low purchasing power, with residents struggling to afford everyday goods despite low living costs.

<img src="[https://github.com/user-attachments/assets/78ebce97-4feb-4e94-ab13-427ed95adb7f](https://github.com/user-attachments/assets/bed2f198-175a-40eb-90ba-5e133d55293a)" width="500">
<br>

---

### **6. Insights and Recommendations**

### **6.1. For Expats and Travelers**
- **Affordable Living**: Countries in South Asia (e.g., India, Bangladesh) and parts of Latin America (e.g., Paraguay, Bolivia) offer a significantly lower cost of living, making them ideal for budget-conscious travelers and expats. For example, India has one of the lowest costs of living indices at 21.2, making it highly affordable.
- **High Costs in Europe**: Switzerland and Norway are indeed high-cost destinations. Switzerland, with a cost of living index of 101.1 and high rent, is notably expensive. Norway also has a high cost of living (76) with substantial rent costs, so expats should prepare for high expenses if considering these countries.

### **6.2. For Businesses**
- **Salary Adjustments**: Companies operating globally need to adjust salaries based on local cost of living and purchasing power. For example, high-rent countries like Hong Kong (Rent Index: 59.4) and Switzerland require higher salaries to maintain the same standard of living compared to less expensive locations.
- **Relocation Recommendations**: For employees relocating, destinations in Southeast Asia (e.g., Thailand, Malaysia) and parts of Latin America (e.g., Colombia, Guatemala) offer lower costs while maintaining a reasonable quality of life. For instance, Thailand has a cost of living index of 34.1, which is significantly lower than that of Switzerland.

### **6.3. For Governments**
- **Wage Policy Adjustments**: Governments in countries with low local purchasing power but rising living costs should consider adjusting minimum wage policies. For example, countries like Pakistan (Purchasing Power Index: 29.1) and Egypt (Purchasing Power Index: 20) might need to address minimum wage issues to help residents manage increasing expenses.


### **7. Conclusion**
This project demonstrates how analyzing cost of living data can reveal valuable insights for individuals, businesses, and governments alike. The global variations in rent, groceries, and local purchasing power highlight the complex nature of affordability across different regions. Moving forward, this analysis can be extended by including historical data to uncover cost of living trends over time or integrating additional variables such as economic growth and inflation rates.


### **8. Tools Used**
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Plotly Express


### **9. Future Work**
- **Historical Data Analysis**: Analyze trends over time to forecast future changes in cost of living and rent prices.
- **Deeper Correlation Analysis**: Incorporate more variables (e.g., inflation rates, employment rates) to understand what drives living costs.
- **Interactive Dashboard**: Build an interactive dashboard for users to explore the data in real-time.


#### **10. References**

- [Kaggle](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024)
- [Numbeo: Cost of Living Index](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp)
- [Methodology](https://www.numbeo.com/common/motivation_and_methodology.jsp)
