# Chocolate-Business-Performance-Dashboard
## Page 8: Executive Sales Performance Dashboard(Final Dashboard)

### Objective

Developed an interactive executive dashboard to monitor overall business performance through key performance indicators, sales trends, shipment distribution, product performance, geographical revenue and salesperson analysis.

### Visualizations Implemented

**1. KPI Cards**
- Total Amount
- Total Boxes
- Shipment Count
- Total Profit
- Profit Percentage

**2. Date Range Slicer**
- Implemented a Between-type date slicer using the Calendar table.
- Enabled dynamic filtering across dashboard visuals.

**3. Current Year vs Previous Year Sales**
- Implemented a line chart to compare monthly revenue.
- Used Start of Month as the X-axis.
- Compared Total Amount with Total Amount (Last Year).

**4. Shipment Distribution Histogram**
- Created numerical bins using the Boxes column.
- Analysed shipment frequency across different box intervals.
- Visualized shipment distribution using a column chart.

**5. Top 5 Products Treemap**
- Implemented a Treemap to display the five highest revenue-generating products.
- Applied Top N filtering based on Total Amount.

**6. Current Year vs Previous Year Box Sales**
- Compared monthly box sales with previous-year values.
- Used a line chart to identify changes in sales volume.

**7. Top 6 Salesperson Performance**
- Created a table displaying salesperson pictures, names, revenue, boxes sold and profitability.
- Applied Top N filtering to identify leading salespeople.

**8. Product Profitability Analysis**
- Created a product-level performance table.
- Displayed Total Amount and Profit Percentage.
- Applied conditional formatting and data bars to highlight profitability.

### Operations Performed

1. Created KPI cards using existing DAX measures.
2. Configured a date range slicer for interactive date filtering.
3. Implemented current-year and previous-year revenue comparisons.
4. Created numerical bins for shipment distribution analysis.
5. Applied Top N filters to identify leading products.
6. Compared monthly box sales against previous-year performance.
7. Created a salesperson performance table with profile images.
8. Applied conditional formatting to product profitability.
9. Configured visual-level formatting and dashboard layout.
10. Integrated multiple visuals into a consolidated executive dashboard.

### Technical Concepts Covered

- KPI Development
- DAX Measures
- Time Intelligence
- Year-over-Year Analysis
- Date Slicers
- Top N Filtering
- Data Binning
- Histogram Analysis
- Treemap Visualization
- Conditional Formatting
- Data Bars
- Image Integration
- Interactive Dashboards
- Sales and Profitability Analysis

### Business Value

The executive dashboard provides a consolidated view of sales and profitability, helps identify high-performing products and salespeople, analyses shipment distribution and enables management to compare monthly performance against previous-year results.
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

### Page 5: Salesperson Profitability & Monthly Profit Analysis

**Objective:**

Analyse salesperson-wise profitability and evaluate monthly profit trends across multiple years.

**Visualizations:**

1. **Table – Salesperson Profitability**
   - Salesperson
   - Total Profit
   - Profit Percentage
   - Displays individual salesperson profitability and overall totals.

2. **Horizontal Bar Chart – Salesperson Profit Comparison**
   - Category: Salesperson
   - Values: Total Profit and Profit Percentage
   - Compares profitability across individual salespeople.

3. **Column Chart – Monthly Total Profit Trend**
   - X-axis: Year and Month Number.
   - Y-axis: Total Profit.
   - Displays monthly profit fluctuations across different years.

**Operations Performed:**

1. Created a table visual to display salesperson-wise profit information.
2. Added Total Profit and Profit Percentage measures.
3. Created a horizontal bar chart for salesperson profitability comparison.
4. Added Salesperson as the category and profitability measures as values.
5. Created a column chart to analyse monthly profit trends.
6. Used Year and Month Number fields from the Calendar table.
7. Added Total Profit to analyse changes in profitability over time.

**Concepts Covered:**

- Table Visualizations
- Horizontal Bar Charts
- Column Charts
- DAX Measures
- Profitability Analysis
- Salesperson Performance Analysis
- Date Hierarchy
- Monthly Trend Analysis
- Data Aggregation
- Comparative Analysis
- Time-Based Business Analysis

**Business Insights:**

The analysis helps identify high-profit salespeople, compare individual profitability and understand monthly profit fluctuations. These insights can support salesperson performance evaluation and business profitability planning.

### Page 6: Team Performance & Product Sales Analysis

**Objective:**

Evaluate team-wise sales performance by comparing current-period sales with previous-year sales and identify the highest and lowest revenue-generating products.

**Visualizations:**

1. **Table – Team-wise YoY Sales Comparison**
   - Team
   - Total Amount
   - Total Amount (Last Year)
   - Total Amount (12 Month Variance)
   - Compares current and previous-year sales performance across teams.

2. **Horizontal Bar Chart – Product-wise Sales Analysis**
   - Category: Product
   - Values: Total Amount
   - Displays product revenue in descending order.

**Operations Performed:**

1. Created a table visual for team-wise sales analysis.
2. Added Total Amount, Total Amount (Last Year) and Total Amount (12 Month Variance) measures.
3. Compared current-period and previous-year sales performance.
4. Created a horizontal bar chart to analyse product-wise revenue.
5. Added Product to the category axis and Total Amount to Values.
6. Sorted the products in descending order based on sales revenue.
7. Enabled totals in the team comparison table.

**Concepts Covered:**

- Table Visualizations
- Horizontal Bar Charts
- DAX Measures
- Time Intelligence
- Year-over-Year Comparison
- Variance Analysis
- Previous-Year Sales Analysis
- Date Context
- Data Aggregation
- Descending Sorting
- Team Performance Analysis
- Product Revenue Analysis

**Business Insights:**

The analysis helps identify teams experiencing sales growth or decline compared with the previous year. It also highlights products contributing the most revenue, supporting business decisions related to sales strategies and product performance.

### Page 7: Monthly Sales Trends & Geographical Revenue Analysis

**Objective:**

Analyse monthly sales performance across multiple years, compare current-period revenue with previous-year revenue, calculate sales variances and evaluate geographical revenue contributions.

**Visualizations:**

1. **Table – Monthly Year-over-Year Sales Analysis**
   - Year
   - Month Name
   - Total Amount
   - Total Amount (Last Year)
   - Total Amount (12 Month Variance)
   - Displays monthly sales performance and previous-year comparisons.

2. **Donut Chart – Geographical Revenue Distribution**
   - Legend: Geo
   - Values: Total Amount
   - Displays revenue contribution and percentage distribution across six countries.

3. **Line Chart – Current Year vs Previous Year Sales**
   - X-axis: Year and Month Name
   - Y-axis: Total Amount and Total Amount (Last Year)
   - Compares monthly sales trends across different years.

**Operations Performed:**

1. Created a table visual for monthly sales analysis.
2. Added Year and Month Name from the Calendar table.
3. Added Total Amount, Total Amount (Last Year) and Total Amount (12 Month Variance).
4. Created a donut chart to analyse geographical revenue contribution.
5. Added Geo as the category and Total Amount as the value.
6. Configured data labels to display revenue and percentage contribution.
7. Created a line chart to compare current and previous-year sales.
8. Added Year and Month Name to the X-axis.
9. Added current-year and previous-year sales measures to the chart.
10. Configured line styles to distinguish the two sales trends.

**Concepts Covered:**

- Table Visualizations
- Donut Charts
- Line Charts
- DAX Time Intelligence
- SAMEPERIODLASTYEAR()
- CALCULATE()
- Year-over-Year Analysis
- Monthly Sales Variance
- Geographical Revenue Analysis
- Percentage Contribution
- Date Hierarchy
- Trend Analysis
- Comparative Business Analysis

**Business Insights:**

The analysis identifies monthly sales growth and decline, compares current and previous-year performance and highlights geographical revenue contributions. India contributes the largest share of total revenue, while Canada contributes the smallest share among the six regions.
