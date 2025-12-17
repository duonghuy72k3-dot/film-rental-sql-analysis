##### **1. Project Title**



Film Rental Business Analysis using MySQL

\*\*Tools:\*\* My SQL Workbench 8.0 CE

\*\*Dataset:\*\* Sakila Sample Database







##### **2. Project Overview**



This project uses the Sakila sample database to analyze the business performance of a film rental company.

The analysis focuses on revenue generation, customer behavior, rental patterns, and film popularity. 

Key tables such as payment, rental, film, inventory, customer, and category are used to answer practical business-related questions.

The project demonstrates how SQL can be applied to transform raw transactional data into meaningful business insights.







##### **3. Dataset**



Source: Sakila Sample Database (MySQL official sample database)

Description: The Sakila database simulates a DVD rental store, containing information about films, customers, rentals, payments, stores, and staff.

Main tables used:

* Payment
* Rental
* Customer
* Film
* Inventory
* Category
* Actor
* Address
* City
* Country







##### **4.Business Questions**



1.Total Revenue of the Company

* Calculate the total revenue generated from film rentals.

2.Monthly Revenue Trend

* Analyze revenue over time to identify business cycles.

3.Top Revenue Contributing Countries

* Analyze geographic distribution of revenue.

4.Customer Segmentation by Payment Amount

* Classify customers into High / Medium / Low value groups.

5\. Revenue Ranking by Film Category

* Identify top performing film genres.

6.Top Actors by Revenue Contribution

* Identify actors driving the most revenue.

7\. Number of Rentals by Rating

* Understand customer preferences by film rating.

8\. Top 10 Most Rented Films

* Identify popular films.

9\. Percentage of Late Returns

* Measure customer behavior related to late returns.

10\. Top 3 Highest Revenue Films in Top 10 Revenue Countries

* Deep-dive analysis using CTE and ranking functions.







##### **5. SQL Techniques Used**



* JOIN
* GROUP BY \& HAVING
* CASE WHEN
* Common Table Expressions (CTE)
* Window Functions (RANK() OVER PARTITION BY)
* Date functions (DATE\_ADD, DATE\_FORMAT)
* Subqueries







##### **6. Project structure**

/queries

01\_Total\_Revenue.sql

02\_Revenue\_by\_Month.sql

03\_Countries\_with\_High\_Payment.sql

04\_Customers\_Classification\_by\_Payment\_Level.sql

05\_Ranking\_Revenue\_by\_Category.sql

06\_Top\_10\_Actors\_Generating\_the\_Highest\_Revenue.sql

07\_Number\_of\_Rentals\_by\_Rating.sql

08\_Top\_10\_Most\_Rented\_Films.sql

09\_Percentage\_of\_Late\_Returns\_Rentals.sql

10\_Top\_3\_Highest\_Revenue\_Films\_in\_Top\_10\_Revenue\_Countries.sql







##### **7. Results / Insights**

1. Revenue Performance

* Total revenue represents the overall business performance of the company during the analyzed period. When combined with cost data, it can be used to evaluate profitability and operational efficiency. Comparing revenue across different periods helps identify growth trends or potential performance issues.

2\. Monthly Revenue Trend

* Monthly revenue trends reveal how business performance changes over time. This analysis helps identify peak-demand months, enabling more effective marketing strategies and better resource allocation during high-revenue periods.

3\. High Paying Countries

* Countries contributing the highest revenue are considered key markets for the business. Focusing on maintaining and expanding these markets can help ensure stable and long-term revenue growth.

4\. Customer Payment Classification

* Classifying customers based on their payment levels helps identify high-value and loyal customers. This enables the business to design targeted loyalty programs and personalized incentives to strengthen customer retention.

5\. Revenue by Film Category

* Revenue analysis by film category provides insights into customer preferences. This information supports strategic decisions on inventory investment, focusing on film genres that attract the highest demand.

6\. Top Revenue-Generating Actors

* Actors generating high revenue indicate strong audience appeal. The store can prioritize acquiring films featuring these actors to maximize revenue potential.

7\. Rentals by Rating

* Rental counts by film rating reflect customer preferences and indirectly indicate the dominant customer age segments. This insight helps align the film inventory with the target audience.

8\. Most Rented Films

* The most rented films highlight current customer interests and trends. This insight helps the store maintain appropriate inventory levels for high-demand films.

9\. Late Return Rate

* The late return rate indicates customer compliance with rental policies. Based on this analysis, the store can adjust penalty rules or reminder systems to reduce late returns.

10\. Top Films by Country

* Analyzing top-performing films by country reveals differences in customer preferences across markets. This insight supports the development of localized content strategies tailored to each region.







##### **8. How to Run the project**



1. Import the Sakila database into MySQL

2\. Open MySQL Workbench

3\. Execute the SQL files in the /queries folder







##### **9. Author**



* Name: Dương Quang Huy
* Email: duonghuy72k3@gmail.com
* Github: duonghuy72k3-dot
* Major: Finance -  Accounting
* Skills: SQL, Data Analysis



