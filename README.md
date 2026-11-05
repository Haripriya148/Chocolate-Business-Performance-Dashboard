# Chocolate-Business-Performance-Dashboard
### Page 1: Product-wise Sales Analysis

**Objective:** Analyse product-wise sales performance and identify the highest- and lowest-revenue-generating products across geographical regions.

**Visualizations:**
- Clustered Column Chart: Displays the sum of sales amount for each product.
- Geo Slicer: Enables interactive filtering of product sales by country.

**Operations Performed:**
1. Created a clustered column chart using Product and Amount fields.
2. Applied SUM aggregation to calculate total sales for each product.
3. Sorted products in descending order based on total sales.
4. Created a geographical slicer using the Geo field.
5. Applied geographical filtering to analyse country-specific product performance.

**Concepts Covered:**
- Data aggregation using SUM.
- Categorical data analysis.
- Clustered column charts.
- Sorting and ranking through visual sorting.
- Interactive slicers.
- Filter context and data relationships.

**Business Insights:**
The analysis helps identify high-performing and low-performing products within selected geographical regions, supporting product-level sales analysis and business decision-making.

### Page 2: Geographical Sales & Product Profitability Analysis

**Objective:**

Analyse geographical sales, cost and profit performance while identifying high-performing and low-performing products based on profitability.

**Visualizations:**

1. **Clustered Column Chart – Geographical Analysis**
   - X-axis: Geo
   - Values: Sum of Amount, Sum of Cost and Total Profit.
   - Compares revenue, cost and profit across geographical regions.

2. **Product Profitability Table**
   - Product
   - Total Profit
   - Profit Percentage
   - Uses conditional formatting with data bars to highlight positive and negative profitability.

**Operations Performed:**

1. Created a clustered column chart to compare sales, cost and profit across countries.
2. Added Geo as the geographical category.
3. Added Amount, Cost and Total Profit as numerical measures.
4. Created a table visual for product-level profitability analysis.
5. Added Product, Total Profit and Profit Percentage fields.
6. Applied conditional formatting using data bars.
7. Used different colours to distinguish positive and negative profitability.

**Concepts Covered:**

- Clustered Column Charts
- Data Aggregation using SUM
- Multiple Measures
- Geographical Analysis
- Table Visualizations
- Conditional Formatting
- Data Bars
- Profitability Analysis
- Positive and Negative Values

**Business Insights:**

The analysis helps compare geographical business performance, identify profitable products and highlight products with negative profitability that may require further investigation.

### Page 3: Shipment Trend & Team Performance Analysis

**Objective:**

Analyse monthly shipment trends across multiple years and evaluate the contribution of individual teams to the overall shipment volume.

**Visualizations:**

1. **Line Chart – Monthly Shipment Trends**
   - X-axis: Year and Month Number.
   - Y-axis: Shipment Count.
   - Displays monthly shipment fluctuations across 2023, 2024 and 2025.
   - Helps identify changes in shipment activity over time.

2. **Donut Chart – Team-wise Shipment Distribution**
   - Legend: Team.
   - Values: Shipment Count.
   - Displays the shipment contribution of each team.
   - Shows shipment distribution through counts and percentages.

**Operations Performed:**

1. Created a line chart to visualize monthly shipment trends.
2. Used Year and Month Number fields from the Calendar table to organize the timeline.
3. Added the Shipment Count measure to analyse monthly shipment volumes.
4. Created a donut chart to analyse team-wise shipment distribution.
5. Added Team as the category and Shipment Count as the numerical value.
6. Configured data labels to display shipment counts and percentage contributions.

**Concepts Covered:**

- Line Chart Visualization
- Donut Chart Visualization
- Time-Series Analysis
- Date Hierarchy
- Monthly Trend Analysis
- Data Aggregation
- Percentage Contribution
- Data Labels
- Categorical Data Analysis
- Data Modelling and Relationships

**Business Insights:**

The analysis identifies team-wise shipment contributions and highlights monthly variations in shipment activity. Delish contributes the highest shipment share, while Yummies contributes the lowest share among the four teams. These insights can support operational planning and workload distribution.

### Page 4: Salesperson Performance & Geographical Analysis

**Objective:**

Evaluate salesperson performance using sales revenue, total boxes and amount per box while comparing performance across geographical regions.

**Visualizations:**

1. **Table – Salesperson Performance**
   - Salesperson
   - Total Amount
   - Total Boxes
   - Amount Per Box
   - Displays individual salesperson performance and overall totals.

2. **Matrix – Geographical Salesperson Analysis**
   - Rows: Salesperson
   - Columns: Geographical Region
   - Values: Amount Per Box
   - Uses conditional formatting to create a heatmap-style comparison.

3. **Date Range Slicer**
   - Field: cal_date
   - Allows users to filter the report using a selected date range.

**Operations Performed:**

1. Created a table visual to display salesperson performance.
2. Added Total Amount, Total Boxes and Amount Per Box.
3. Enabled grand totals for overall performance.
4. Created a Matrix visual for geographical comparisons.
5. Added Salesperson to Rows and Geo to Columns.
6. Added Amount Per Box to Values.
7. Applied conditional formatting using background colours.
8. Created a date range slicer using the Calendar table.
9. Configured date filtering to analyse performance over selected periods.

**Concepts Covered:**

- Table Visualizations
- Matrix Visualizations
- Pivot-style Analysis
- Conditional Formatting
- Heatmap Visualization
- Date Range Slicers
- Data Aggregation
- Grand Totals
- Geographical Analysis
- Salesperson Performance Analysis
- Cross-dimensional Analysis

**Business Insights:**

The analysis helps evaluate individual salesperson contributions, compare sales efficiency across geographical regions and investigate performance during selected periods. The matrix provides a quick visual comparison of salesperson performance across countries.
