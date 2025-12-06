**Food Delivery Performance**

**📌 Overview**

The Food Delivery Performance Dashboard is a Power BI report designed to analyze and visualize key metrics related to food delivery operations.
It helps users track delivery efficiency, order trends, customer experience indicators, and partner (restaurant & delivery agent) performance.
This dashboard supports data-driven decision-making by enabling businesses to identify delivery delays, understand demand patterns, optimize operational workflows, and improve overall service quality

**⚙️ Working**

The Power BI report (Food Delivery performance.pbix) processes raw delivery data, transforms it into a structured data model, and visualizes performance insights using multiple interactive dashboards.

**1. Data Import**

The .pbix file pulls data from:
CSV/Excel datasets
SQL database sources (if configured)
Any additional delivery/restaurant/agent data provided
Data is cleaned, merged, and standardized inside Power BI using Power Query.

**2. Data Modeling**

The model includes:
Fact tables → Orders, Deliveries, Revenue
Dimension tables → Date, Restaurant, Delivery Agent, Location, Order Status
Relationships are created to enable cross-filtering across visuals.

**3. DAX Calculations**

The report uses several DAX measures, such as:
Total Orders
Total Revenue
Average Delivery Time
On-Time Delivery % (SLA Adherence)
Average Rating / Customer Feedback
Cancellation Rate
These measures power KPI cards and trend charts.

**4. Interactive Visual Dashboards**

The report includes multiple views, such as:
Executive Overview → KPI summary
Order Trends → Daily/Monthly demand patterns
Delivery Performance → Delay reasons, SLA tracking
Geographic View → Region-wise order and delivery behavior
Partner Analytics → Restaurant & delivery agent performance
