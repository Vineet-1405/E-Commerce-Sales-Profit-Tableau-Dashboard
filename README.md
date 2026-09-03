# E-Commerce-Sales-Profit-Tableau-Dashboard
Interactive Tableau dashboard for analyzing e-commerce sales, profit, orders, categories, regions, and product performance.
About the Project

This project is an interactive Tableau dashboard created to understand
the sales and profit performance of an e-commerce business.

The dashboard brings important business information into one place, so
it is easier to see overall performance, monthly trends, category
performance, regional performance, and product-level results.

I created this dashboard as part of my data analytics/Tableau project.

Objectives

The main objectives of this project are:

Understand total sales and total profit.

Track the number of orders.

Calculate and monitor profit margin.

Compare sales and profit across categories.

Study monthly sales and profit trends.

Compare performance across different regions.

Identify top-performing products.

Identify products that are making losses.

Understand profit margin across categories and regions.

Dashboard Highlights

The dashboard includes the following KPIs:

Total Sales

Total Profit

Total Orders

Profit Margin

It also contains these visualizations:

Monthly Sales & Profit Trend

Sales by Category

Profit by Category

Regional Performance

Top 10 Products by Profit

Bottom 10 Products by Profit

Profit Margin by Category & Region

Interactivity

The dashboard includes filters that allow users to explore the data
based on:

Order Year

Region

Category

Segment

Users can select different values and the charts update accordingly.
This makes it easier to compare different parts of the business without
creating separate reports.

Calculated Fields

Some calculated fields were used in Tableau to make the analysis more
useful.

Profit Margin

IF SUM([Sales]) = 0 THEN
    0
ELSE
    SUM([Profit]) / SUM([Sales])
END

Order Count

COUNTD([Order ID])

Order Month

DATETRUNC('month', [Order Date])

Order Year

YEAR([Order Date])

Tools Used

Tableau

CSV Dataset

Tableau Calculated Fields

Data Visualization

Exploratory Data Analysis (EDA)

Project Files

Task 2
│
├── task2_corrected_dashboard.twb
├── Ecommerce_Sales_Dashboard_Practice.csv
└── README.md

How to Open the Project

Download or clone this repository.

Keep the .twb file and CSV dataset in the same folder.

Open task2_corrected_dashboard.twb using Tableau Desktop.

If Tableau asks for the data source, select
Ecommerce_Sales_Dashboard_Practice.csv.

Open the dashboard and use the filters to explore the data.

What I Learned

Through this project, I practiced working with Tableau from data
preparation to dashboard design. I learned how to create calculated
fields, build different types of charts, create KPI cards, apply
filters, and arrange multiple worksheets into an interactive dashboard.

I also focused on making the dashboard simple to understand instead of
putting too many charts on one screen.

Conclusion

This dashboard gives a simple overview of e-commerce sales and
profitability. It can help a business quickly identify strong
categories, profitable regions, top products, and products that need
attention.

The project also helped me understand how raw business data can be
converted into useful visual information for decision-making.
