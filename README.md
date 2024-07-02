This is an ad-hoc data analysis project focusing on the hospitality domain for Atliq Grands, a hotel chain operating in Delhi, Mumbai, Bangalore, and Hyderabad. Having been in the industry for around two years, AtliQ Grands offers various hotel types like AtliQ Seasons, Atliq Exotica, Atliq Bay, and AtliQ Palace, and room categories such as Standard, Elite, Premium, and Presidential. Guests can book through multiple channels including Atliq Grands' website and third-party sites like Make Your Trip, Log Trip, and Tripster. All booking data is stored in their bookings database, which we analyzed to provide actionable insights.

📊 Problem Statement:
Atliq Grands has been experiencing a decline in revenue and increased competition. To address these issues and boost their market share, Atliq management decided to leverage data analytics.

🛠️ Process:
To tackle this problem, I performed:
Data Exploration
Data Cleaning
Data Transformation
Insights Generation

🧹 Data Cleaning:
Handled null values using the fillna method.
Replaced negative values with positive ones using the replace method.
Filtered out invalid guest counts by applying conditions.

🔄 Data Transformation:
Calculated the occupancy rate to evaluate performance across different cities by dividing successful bookings by capacity.

💡 Insights Generation:
Average Occupancy Rate by Room Category
Average Occupancy Rate per City based on property ID by joining hotel and booking data
Occupancy Comparison: Weekdays vs. Weekends
Monthly Occupancy: Focused on June for different cities
Incorporating New Data: How to add August data
Revenue Realized per City
Monthly Revenue Trends
Revenue Realized per Hotel Type
Average Rating per City
Pie Chart: Revenue Realized per Booking Platform

🛠️ Solutions
Utilized merge and group by functions
Generated insightful plots

By analyzing this data, Atliq Grands can identify areas of improvement in revenue generation, occupancy rates, and revenue distribution across different metrics.
