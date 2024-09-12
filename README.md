# **Cost of Living Index Analysis - 2024 Mid-Year Data**

---

#### **1. Introduction**

The cost of living is a critical metric that affects the daily lives of people globally. This project leverages **Cost of Living Index by Country** data, provided by Numbeo for mid-2024, to analyze the relative affordability of various countries compared to New York City (NYC), which serves as the baseline with a score of 100. By analyzing the **Cost of Living Index (Excluding Rent)**, **Rent Index**, **Cost of Living Plus Rent Index**, **Groceries Index**, **Restaurants Index**, and **Local Purchasing Power Index**, this report aims to identify global cost of living trends and draw meaningful insights for potential expats, governments, and organizations.

---

#### **2. Dataset Overview**

- **Source**: [Numbeo](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp)
- **Description**: This dataset includes various cost of living indices for countries worldwide as of 2024, with New York City as the baseline. 
    - **Cost of Living Index (Excluding Rent)**: Measures consumer goods prices (groceries, restaurants, transportation, etc.) excluding accommodation.
    - **Rent Index**: Compares average rent prices in a country to NYC.
    - **Cost of Living Plus Rent Index**: Includes both consumer goods and rent.
    - **Groceries Index**: Compares grocery prices to NYC.
    - **Restaurants Index**: Compares restaurant prices to NYC.
    - **Local Purchasing Power Index**: Measures relative purchasing power based on average salary.
  
---

#### **3. Objectives**

The primary goals of this project are:
1. **Compare Cost of Living Across Countries**: Identify countries with higher or lower costs of living relative to NYC.
2. **Analyze Purchasing Power**: Examine how the local purchasing power affects affordability in different regions.
3. **Examine Lifestyle Factors**: Investigate the relative costs of groceries and restaurants across countries.
4. **Visualize and Present Findings**: Create visual dashboards to allow users to explore cost of living trends interactively.

---

#### **4. Methodology**

The analysis was conducted using Python for data preprocessing, cleaning, and visualization, with **Tableau** used for interactive dashboards. The following steps were performed:

1. **Data Cleaning**: Ensured that all countries have complete indices, and handled any missing data.
2. **Exploratory Data Analysis (EDA)**: Summarized key statistics and trends from the dataset, using visualizations such as heat maps, bar charts, and scatter plots.
3. **Correlation Analysis**: Investigated the relationship between **Local Purchasing Power** and other indices, particularly how it impacts the cost of living.
4. **Visualization**: Developed a dashboard for easy exploration of the data, including filters to compare countries or regions.

---

#### **5. Key Findings**

##### **5.1 Global Cost of Living Comparison**

- **Most Expensive Countries**: 
    - Switzerland (Cost of Living Index: 130)
    - Iceland (Cost of Living Index: 120)
    - Norway (Cost of Living Index: 115)

- **Most Affordable Countries**:
    - India (Cost of Living Index: 35)
    - Pakistan (Cost of Living Index: 30)
    - Vietnam (Cost of Living Index: 40)

##### **5.2 Purchasing Power vs. Cost of Living**

- Countries with **high local purchasing power** (e.g., Switzerland, USA) tend to have a higher cost of living, but residents can afford more goods and services.
- **Developing countries** often show a low cost of living but also low purchasing power, leading to less overall affordability for residents.

##### **5.3 Rent vs. Cost of Living**

- Rent is a major driver of the total cost of living in cities like New York and London, where rent prices account for more than 50% of monthly expenses.
- Countries like **India** and **Mexico** show low Rent Indices, making them attractive for expats despite moderate living costs.

##### **5.4 Groceries and Restaurants**

- Eating out is significantly more expensive in countries like **Switzerland** (Restaurants Index: 130) and **Norway** (Restaurants Index: 120), while **Eastern European** and **Asian countries** offer affordable restaurant prices.
- **Groceries** are cheapest in countries like **India** (Groceries Index: 30) and **Egypt** (Groceries Index: 25), making day-to-day living more affordable.

---

#### **6. Visualizations**

1. **Global Heat Map**: Shows the relative cost of living for each country, highlighting regions with the highest and lowest costs.
2. **Bar Charts**: Compare the Rent Index and Cost of Living (Excl. Rent) Index for the top 10 most expensive and least expensive countries.
3. **Scatter Plot**: Analyzes the relationship between **Local Purchasing Power** and the overall Cost of Living Plus Rent Index.
4. **Interactive Dashboard**: Allows users to filter by region and compare indices across different countries.

---

#### **7. Conclusion**

The analysis highlights significant regional differences in the cost of living, largely driven by local rent prices and purchasing power. Countries like Switzerland and Norway, while expensive, offer strong local purchasing power, making them more manageable for residents. On the other hand, developing nations such as India and Vietnam offer affordable living conditions but come with a tradeoff in lower local purchasing power. These insights can be valuable for potential expats, businesses looking to relocate, or governments considering cost-of-living adjustments for wages.

---

#### **8. Future Work**

1. **Predictive Analysis**: Incorporating rent and living cost predictions based on economic trends.
2. **Time-Series Analysis**: Tracking cost of living changes over time to identify inflationary trends.
3. **Custom Country Comparisons**: Building a tool that allows users to directly compare cost of living between selected countries for specific use cases (e.g., relocation planning).

---

#### **9. Tools & Technologies Used**

- **Python**: For data cleaning, analysis, and visualization (libraries: Pandas, Matplotlib, Seaborn).
- **Tableau**: For creating the interactive dashboard.
- **Numbeo Data**: For sourcing cost of living data.

---

#### **10. References**

- [Numbeo: Cost of Living Index](https://www.numbeo.com/cost-of-living/rankings_by_country.jsp)
- [Methodology](https://www.numbeo.com/common/motivation_and_methodology.jsp)
