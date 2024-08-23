## Analyzing the Impact of Inflation on Commodity Prices: A Visual Exploration of Gold, WTI, and Brent

This project involves analyzing the relationship between inflation rates and the prices of Gold, WTI (West Texas Intermediate) crude oil, and Brent crude oil over time using Python. Here's a summary:

### **Data Sources:**
- **Inflation Rates:** A CSV file containing dates and corresponding inflation percentages.
- **Gold, WTI, Brent Prices:** A CSV file containing dates and the respective prices of Gold, WTI, and Brent.

### **Process Overview:**
1. **Data Loading & Preparation:**
   - The inflation rates and commodity prices data are loaded from CSV files.
   - Dates are converted into a proper datetime format for easier manipulation and plotting.

2. **Visualization:**
   - Three subplots are created to display the prices of Gold, WTI, and Brent over time.
   - For each subplot:
     - The price data (Gold, WTI, Brent) is plotted as a line graph.
     - The inflation percentage is overlaid as a scatter plot with corresponding dates.
   - Twin axes are used to show both the commodity prices and the inflation rates on the same subplot, allowing for comparison.

3. **Plot Formatting:**
   - The date axis is formatted to display the date in a readable format.
   - Legends are added for better understanding of the plots.

4. **Output:**
   - The resulting visualization shows how Gold, WTI, and Brent prices have changed over time alongside the inflation rate, helping to identify any possible correlations or patterns between these economic indicators.

### **Goal:**
The project aims to provide insights into how inflation impacts the prices of key commodities like Gold, WTI, and Brent crude oil. By visualizing these relationships, the analysis can highlight trends or anomalies that might be relevant for financial or economic decision-making.

### **Tools and Technologies Used:**

1. **Programming Language:**
   - Python

2. **Libraries:**
   - **Pandas:** For data manipulation and analysis.
   - **Matplotlib:** For creating visualizations and plots.
   - **NumPy:** For numerical operations and data manipulation.
   - **Scikit-learn:** For scaling and evaluating data (though not explicitly used in the code provided).

3. **Data Sources:**
   - CSV files containing inflation rates and commodity prices.

4. **Visualization Tools:**
   - **Matplotlib:** Used to create line plots and scatter plots to visualize the relationship between inflation rates and commodity prices.
