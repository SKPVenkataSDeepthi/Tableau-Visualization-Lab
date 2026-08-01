# Tableau IBM Project Notes
## Creating Charts and Dashboards using Tableau

## Objective
Learn how to build interactive visualizations and dashboards using Tableau by analyzing customer sales and marketing data.

---

# Dataset Overview

The dataset contains information related to:

- Revenue
- Quantity Sold
- Product Line
- Coupon Response
- Customer Lifetime Value
- Loyalty Status
- City
- Country
- Latitude
- Longitude

---

# Visualization 1 — Map

### Purpose
Visualize revenue generated and quantity sold across different countries.

### Steps
- Drag Latitude → Rows
- Drag Longitude → Columns
- Change Latitude & Longitude from Measure to Dimension
- Drag Quantity Sold onto the map
- Drag Revenue to Detail
- Color the map using Quantity Sold
- Change Background Layer → Streets

### Insights
- Geographic distribution of sales
- High-performing regions
- Sales density by country

---

# Visualization 2 — Column Chart

### Purpose
Compare product sales for different coupon responses.

### Fields Used

Columns
- Coupon Response

Rows
- SUM(Quantity Sold)

Color
- Product Line

### Insights

- Product performance by marketing response
- Coupon effectiveness
- Product category comparison

---

# Visualization 3 — Circle Chart

### Purpose

Compare product lines across coupon responses using bubble sizes.

### Fields

Columns
- Product Line

Rows
- Quantity Sold

Color
- Coupon Response

Chart
- Circle Chart

### Insights

- Product demand
- Marketing response distribution
- Product popularity

---

# Visualization 4 — Dual Axis Chart

### Purpose

Compare:

- Quantity Sold
- Customer Lifetime Value

for each city.

### Fields

Columns
- City

Rows
- SUM(Quantity Sold)
- SUM(Customer Lifetime Value)

Chart Types

Quantity Sold
- Bar

Customer Lifetime Value
- Line

Additional Steps

- Convert to Dual Axis
- Apply Top 10 filter
- Sort Descending

### Insights

- Best performing cities
- High lifetime value customers
- Sales concentration

---

# Visualization 5 — Bubble Chart

### Purpose

Compare product demand among customer loyalty groups.

### Fields

Rows
- Loyalty Status

Columns
- Product Line

Size
- Quantity Sold

Chart
- Packed Bubble

### Insights

- Customer segmentation
- Product preferences
- Loyalty-based demand

---

# Dashboard

Dashboard combines:

- Revenue Map
- Coupon Response Chart
- Marketing Response Circle Chart
- Customer Lifetime Dual Axis Chart
- Loyalty Bubble Chart

Purpose:

Provide a complete sales and customer analytics dashboard.

---

# Tableau Skills Practiced

✔ Maps

✔ Column Charts

✔ Circle Charts

✔ Bubble Charts

✔ Dual Axis Charts

✔ Filters

✔ Sorting

✔ Color Encoding

✔ Dashboard Design

✔ Data Storytelling

---

# Key Learning Outcomes

- Creating geographic visualizations
- Using dimensions and measures
- Applying filters
- Building dual-axis charts
- Creating dashboards
- Visual storytelling with Tableau
