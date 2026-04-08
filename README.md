# Customer 360 Data Analysis
This project focuses on customer segmentation using the RFM model within a Customer 360 framework. The RFM model evaluates customer behavior across three key metrics—Recency, Frequency, and Monetary—scored on a scale from 1 (lowest) to 4 (highest).
* R (Recency): The last time the customer used the service
* F (Frequency): The frequency with which the customer uses the service
* M (Monetary): The revenue generated from the service
By leveraging these metrics, the analysis provides a comprehensive view of customer engagement and value, enabling more effective business decision-making.

## Main objectives:

1 - Understanding the fundamentals of RFM analysis and its role in customer segmentation.

2 - Identifying key customer segments based on Recency, Frequency, and Monetary value.

3 - Gaining insights into customer behavior to support data-driven decision-making.

4 - Applying RFM insights to improve marketing strategies and enhance customer engagement.

By using SQL queries, the analysis extracts meaningful insights from customer data to support strategic decisions and optimize business performance.

## Steps
1 - **Data preparation and integration**
Customer data was collected from two main tables: transaction data and customer registration data. These datasets were joined to ensure a complete view of customer behavior, while normalizing Frequency and Monetary values based on customer lifecycle.

2 - **RFM metric calculation**
Key metrics (Recency, Frequency, Monetary) were calculated using SQL techniques such as CTEs, window functions, and date functions to accurately measure customer activity and value.

3 - **RFM scoring and segmentation**
Customers were grouped into quartiles using the IQR method, assigning scores from 1 to 4 for each metric. These scores were then combined to form RFM segments and classified into meaningful customer groups (e.g., Loyalists, At Risk, Promising).

4 - **Customer segmentation mapping (BCG Matrix)**
RFM segments were mapped into four strategic groups—Star, Cash Cow, Question Mark, and Dog—to better understand customer value and prioritize business actions.

## Analysis outcome
1 - **Recency insight (engagement challenge)**
The business is currently facing challenges in attracting and retaining active customers. The number of recently active customers is relatively low, while revenue is concentrated in less recent segments. This indicates a dependency on inactive customers and highlights a potential risk of revenue decline if churn increases.

2 - **Frequency & Monetary insight (high impact opportunity)**
Although customer distribution across Frequency and Monetary groups is relatively balanced, higher segments generate significantly more revenue. A small shift of customers from group 3 to group 4 can lead to a disproportionately large increase in revenue, highlighting strong leverage in improving high-value behaviors.

3 - **Customer segmentation insight (growth potential)**
The Question Mark segment represents the largest share of customers (approximately 47–48%). These customers typically perform well in only one RFM dimension, indicating untapped potential. This segment presents the greatest opportunity for growth, as improving their engagement across all dimensions could significantly increase overall revenue.

Dashboard link: https://app.powerbi.com/groups/me/reports/9330ae91-7590-4c15-be52-6d8d546c04ca/935e9580cca98d251b90?experience=power-bi
[Description]
<img width="1157" height="648" alt="image" src="https://github.com/user-attachments/assets/5d7171e1-7fb0-46ea-8bce-8ebaea49e5a0" />
<img width="1036" height="603" alt="image" src="https://github.com/user-attachments/assets/d104c223-5517-45d4-8df5-93e635345d8f" />

