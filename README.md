# DATA CLEANSING

1. Outlier
Interquartile range based on fare_amount
Before: (68211, 20)
After: (63872, 20)

2. Duplicate
Based on lpep_pickup_datetime and lpep_dropoff_datetime
Before: (63872, 20)
After: (63726, 20)

3. Missing Value
Delete ehail_fee coloumn
Delete null contained rows
Before: (63726, 20)
After: (60093, 19)

# DATA CORRELATION

1. Top five positive correlation
2. Top five negative correlation
3. Visualize by heatmap
4. Visualize by masked triangle

# TABLEAU DATA EXPORT

1. To make the same heatmap

# ANALYSIS

1. Correlation of total_amount vs payment_type
Sum total_amount based on payment_type
Visualize by bar chart

2. Correlation of tip_amount vs payment_type
Sum tip_amount based on payment_type
Visualize by bar chart
