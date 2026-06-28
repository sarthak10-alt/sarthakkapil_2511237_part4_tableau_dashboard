# sarthakkapil_2511237_part4_tableau_dashboard
# Retail Executive Dashboard Assignment

## 1. Business Problem Summary
The leadership team of a retail chain needs an executive dashboard to monitor sales performance, profitability, customer segments, category performance, shipping performance, discount impact and return patterns. The dashboard is designed to identify business opportunities and risks rather than simply displaying random charts.

## 2. Dataset Description
The dataset used is `data/dashboard_sales_data.xlsx`. It contains 4,200 order-level records with fields such as order date, ship date, customer segment, region, state, city, category, sub-category, product name, ship mode, sales, quantity, discount, profit, return flag, delivery days, customer rating and campaign channel.

## 3. Tableau Workbook Description
The Tableau packaged workbook is stored as `tableau/Executive_Dashboard.twbx`. It is designed around one executive dashboard with supporting views for trend, region, category, customer segment, shipping, discount and returns.

## 4. Calculated Fields Created
The following calculated fields were used:

- **Profit Margin** = Profit / Sales
- **Cost** = Sales - Profit
- **Average Order Value** = Sales / Number of Orders
- **Return Rate** = Returned Orders / Total Orders
- **Shipping Delay Bucket** = Delivery days grouped into business-friendly buckets
- **Profit/Loss Flag** = Profit greater than or equal to zero vs loss-making orders
- **Discount Bucket** = Discount percentage grouped into ranges

## 5. Dashboard Components
The dashboard includes:

1. KPI cards for Total Sales, Total Profit, Profit Margin, Return Rate, Average Delivery Days and Customer Rating
2. Sales trend over time
3. Regional performance view
4. Category profitability view
5. Customer segment view
6. Shipping performance view
7. Discount vs profit view
8. Return analysis view

## 6. Filters and Interactions Used
Suggested filters used in the dashboard:

- Region
- Category
- Customer Segment
- Order Date
- Ship Mode
- Campaign Channel

At least one dashboard/filter interaction is shown through the filter interaction screenshot.

## 7. Key Business Insights
The main insights are documented in `outputs/business_insights.md`. Key findings include:

- South is the strongest sales region.
- Technology is the strongest profit-driving category.
- Furniture has the highest category-level return risk.
- Standard Class has the longest average delivery delay.
- Organic is the strongest sales channel.
- Discounting should be monitored carefully because heavy discounts can reduce profit quality.

## 8. Dashboard Story Summary
The dashboard story is documented in `outputs/dashboard_story.md`. The story connects revenue, profit, return behavior, shipping delay and discounting into one leadership-level narrative.

## 9. Assumptions and Limitations
- Return Flag is interpreted as 1 = returned and 0 = not returned.
- Profit Margin is calculated as Profit divided by Sales.
- Cost is calculated as Sales minus Profit.
- The dashboard shows business associations and patterns, not automatic causation.
- Campaign cost and inventory stockout data are not available, so ROI and lost sales cannot be fully measured.

## 10. Screenshots Included
The required screenshots are stored in the `screenshots/` folder:

- `full_dashboard.png`
- `sales_trend_view.png`
- `regional_performance_view.png`
- `category_profitability_view.png`
- `filter_interaction_view.png`
