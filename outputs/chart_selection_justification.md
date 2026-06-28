# Chart Selection Justification

## Sales Trend View
1. **Question answered:** How are sales changing over time?
2. **Why this chart type:** A line chart is best because time-series performance is easier to read as a continuous trend.
3. **Fields used:** Order Date by month on the x-axis and Sales on the y-axis.
4. **Design principle applied:** Chronological order and clear axis labels.
5. **Mistake avoided:** Avoided a pie chart because it cannot show monthly movement.

## Regional Performance View
1. **Question answered:** Which region is performing best?
2. **Why this chart type:** A bar chart makes it easy to compare sales across regions.
3. **Fields used:** Region and Sales, with Profit Margin optionally available as label or tooltip.
4. **Design principle applied:** Sorted bars from highest to lowest performance.
5. **Mistake avoided:** Avoided overloading the view with too many measures.

## Category Profitability View
1. **Question answered:** Which categories drive profit or losses?
2. **Why this chart type:** A bar chart clearly compares profit contribution by category.
3. **Fields used:** Category and Profit.
4. **Design principle applied:** Profit is emphasized rather than only sales because leadership needs margin visibility.
5. **Mistake avoided:** Avoided judging categories only by revenue.

## Customer Segment View
1. **Question answered:** Which customer segment contributes most to sales and risk?
2. **Why this chart type:** A bar chart/highlight table helps compare segment-level sales, profit and return rate.
3. **Fields used:** Customer Segment, Sales, Profit and Return Rate.
4. **Design principle applied:** Segment comparison is kept simple and business-friendly.
5. **Mistake avoided:** Avoided too many segment breakdowns in one chart.

## Shipping Performance View
1. **Question answered:** Which shipping mode causes delay?
2. **Why this chart type:** A bar chart is appropriate for comparing average delivery days across ship modes.
3. **Fields used:** Ship Mode and Delivery Days.
4. **Design principle applied:** Average delivery days are shown as an operational risk metric.
5. **Mistake avoided:** Avoided using total sales for shipping analysis because the key question is delay.

## Discount vs Profit View
1. **Question answered:** How does discount relate to profit?
2. **Why this chart type:** A scatter plot shows the relationship between discount percentage and profit at order level.
3. **Fields used:** Discount, Profit and Sales size.
4. **Design principle applied:** Zero-profit line helps leadership quickly spot loss-making discounted orders.
5. **Mistake avoided:** Avoided implying causation; the chart shows association only.

## Return Analysis View
1. **Question answered:** Which category, segment or region has higher return risk?
2. **Why this chart type:** A bar chart or highlight table clearly ranks return rates.
3. **Fields used:** Return Flag, Category, Customer Segment and Region.
4. **Design principle applied:** Return Rate is used instead of only return count so groups with different order volumes can be compared fairly.
5. **Mistake avoided:** Avoided using raw returned order counts alone.
