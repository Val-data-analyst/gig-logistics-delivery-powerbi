# GIG Logistics Delivery - PH & Lagos - Power BI
GIG Logistics PH & Lagos - 30 deliveries Cost ₦115K Profit ₦34.6K On-Time 73.33% (22/30) Avg 2.13 days | Power BI DAX | SQL to Power BI | Amaka top rider

![GIG Dashboard](GIG_Logistics_Dashboard_Clear.png)

## Metrics
- 30 deliveries, ₦115K Cost, ₦34.6K Profit, 73.33% On-Time (22/30), 2.13 Avg Days
- Top Rider: Amaka ₦12.5K, Top Destination: Lagos

## DAX
PROFIT_MARGIN = DIVIDE(PROFIT, COST, 0)
OnTime% = DIVIDE(FILTER(STATUS="On-Time"), COUNTROWS, 0)
