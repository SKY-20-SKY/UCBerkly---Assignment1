Analysis Summary: Coupon Acceptance Drivers

Segment 1: Initial Data Overview

The initial data exploration showed that the 'car' column contained the highest percentage of missing values and was dropped from the analysis. An examination of coupon counts showed a bar chart 
illustrating the distribution of coupons, followed by a visualization of the 'temperature' distribution.

Further analysis will focus on identifying the specific criteria that can be utilized to target the most receptive customers.

Segment 2: Bar Coupon Deep Dive

In this segment, I investigated the Bar coupon and derived the following observations:
While the overall acceptance rate for Bar coupons is approximately 41%, the acceptance rate for the most frequent visitors (>3 times a month) is significantly higher, at approximately 77%.

Key Targeting Criteria (Acceptance Probability)
Age: Customers who are over 25.
Frequency: Those who frequent the bar (more than once).
Context: Those driving with non-child passengers (e.g., Alone, Friend, or Partner).

Segment 3: CarryAway Coupon Investigation

The 'CarryAway' coupon was selected for independent investigation. The data was filtered to create a DataFrame dedicated to CarryAway coupon observations.
The overall acceptance rate for CarryAway coupons is high, at approximately 74%. After calculating the mean, examination of the correlation matrix did not yield a strong conclusion among numerical fields.
Further analysis revealed that the acceptance of CarryAway coupons is strongly correlated with the interaction of multiple different attributes.
Strong Correlation: The combination of 'widowed' customers with attributes related to weather and CarryAway frequency showed a strong acceptance (0.90).

Key Targeting Criteria (CarryAway)
The highest probability of acceptance based on the above analysis is:
Frequency: Those who visit CarryAway services more than 3 times.
Demographic: Customers whose marital status is widowed.
Weather: When the weather is Sunny/Rainy.

Please note that I did not perform a comprehensive analysis for Segments 1 and 2, but focused on directly answering the questions. However, independent investigation allowed me to dive into more details, as you can see in the workbook
