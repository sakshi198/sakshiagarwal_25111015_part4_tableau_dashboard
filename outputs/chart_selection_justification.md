# Chart Selection Justification

# 1. Sales Trend (Line Chart)

### Business Question

How are sales changing over time?

### Why this Chart Type?

A line chart is the most appropriate visualization for time-series data because it clearly shows trends, growth patterns, and seasonal fluctuations across different time periods.

### Fields Used

* **X-Axis:** Order Date (Month)
* **Y-Axis:** Sales
* **Filter:** Region, Category, Customer Segment, Ship Mode
* **Label:** Monthly Sales Values

### Design Principle Applied

The chart uses a simple continuous line with minimal clutter, making it easy for executives to identify increases and decreases in sales over time.

### Mistake Avoided

A pie chart or bar chart would not effectively communicate continuous changes over time. A line chart provides a much clearer view of trends.

---

# 2. Regional Performance (Horizontal Bar Chart)

### Business Question

Which regions generate the highest sales?

### Why this Chart Type?

A horizontal bar chart allows easy comparison of sales across multiple regions. It makes ranking regions straightforward and improves readability.

### Fields Used

* **Category:** Region
* **Measure:** Sales
* **Color:** Sales
* **Label:** Sales Value
* **Filter:** Region, Category, Customer Segment

### Design Principle Applied

Regions are sorted for easier comparison, and a single color palette is used to reduce unnecessary visual complexity.

### Mistake Avoided

Maps were not used because the objective was comparison rather than geographical analysis. Bar charts make ranking more accurate and easier to interpret.

---

# 3. Category Profitability (Horizontal Bar Chart)

### Business Question

Which product categories contribute the most profit?

### Why this Chart Type?

A horizontal bar chart effectively compares profit across product categories and highlights differences in profitability.

### Fields Used

* **Category:** Category
* **Measure:** Profit
* **Color:** Profit
* **Label:** Profit Value
* **Filter:** Category, Region

### Design Principle Applied

The chart emphasizes profit rather than sales, helping executives focus on business value instead of revenue alone.

### Mistake Avoided

Treemaps were avoided because they make precise comparisons more difficult than bar charts.

---

# 4. Discount vs Profit (Scatter Plot)

### Business Question

How does discount affect profitability?

### Why this Chart Type?

A scatter plot is the most appropriate visualization for identifying relationships between two continuous numerical variables.

### Fields Used

* **X-Axis:** Discount
* **Y-Axis:** Profit
* **Color:** Profit
* **Filter:** Region, Category, Customer Segment

### Design Principle Applied

Each point represents an individual observation, allowing executives to identify trends, outliers, and negative profit patterns associated with higher discounts.

### Mistake Avoided

Line charts were avoided because there is no continuous sequence between discounts and profit values. Scatter plots better represent correlation.

---

# 5. Return Analysis (Highlight Table)

### Business Question

Which areas have the highest return rates?

### Why this Chart Type?

A highlight table makes it easy to compare return patterns across categories and quickly identify areas requiring attention through color intensity.

### Fields Used

* **Rows:** Category
* **Columns:** Return Status (or Region/Segment depending on the dashboard)
* **Color:** Return Rate
* **Label:** Return Percentage
* **Filter:** Region, Category, Customer Segment

### Design Principle Applied

Color intensity draws immediate attention to areas with higher return rates while maintaining a clean and readable layout.

### Mistake Avoided

Pie charts were avoided because they are not effective for comparing multiple return values across categories. A highlight table supports quicker visual comparison.

---

# Overall Dashboard Design Principles

The dashboard follows key visualization best practices by using appropriate chart types for each business question, maintaining a clear visual hierarchy, minimizing unnecessary clutter, applying consistent color usage, using readable labels and titles, providing interactive filters, and presenting information in a business-friendly format. The dashboard focuses on supporting executive decision-making through clear KPIs and interactive visual analysis rather than decorative graphics.
