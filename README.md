# Business-Analysis-of-The-Carolina-Center
The case study is based on a real theatre named The Carolina, located at 309 W Morgan Street, in Durham NC 27701 USA.  The actual theater is owned by the city of Durham and is operated by a not-for-profit corporation. Built in 1926, it seats approximately 1,000 in its main hall. 

Customer Dataset contains purchase and demographic information about 5000 first-time customers for the "Last Chance Theater" annual ticket subscription, from March 2018 through December 2019. Customers buy tickets to a series of shows throughout the year, and "renewal" means that they renewed their subscription for the following year. 

📊 Dataset Variables

Customer_ID: Unique identifier assigned to each customer (primary key).

Number_of_Tickets: Number of tickets purchased by the customer (range: 1 to 8).

Price: Price per ticket. There are three ticket types: $180, $240, and $300.

Revenue: Total revenue generated from ticket sales, calculated as Price × Number_of_Tickets.

Age: Age of the customer.

Income: Estimated annual income (in thousands).

Own_home: Binary indicator of home ownership (1 = owns a home, 0 = does not).

Own_car: Binary indicator of car ownership (1 = owns at least one car, 0 = does not).

Zip: Categorical variable representing customer travel distance to the theater:
0 = less than 30 minutes
1 = 30–90 minutes
2 = more than 90 minutes

Gender: Binary gender indicator (1 = Male, 0 = Female).

Price_Category: Categorical variable representing ticket price level:
0 = $180 (cheapest)
1 = $240
2 = $300 (most expensive)

Renewal: Binary indicator for customer renewal in year 2 (1 = renewed, 0 = did not renew).

Age_range_1: Binary indicator (1 = Age < 25, 0 = Age ≥ 25).

Age_range_3: Binary indicator (1 = Age > 44, 0 = Other ages).

Age_range_2: Binary indicator (1 = Age between 25 and 44, inclusive; 0 = Other ages).

P: Categorical age group variable:
1 = Age < 25
2 = Age 25–44
3 = Age > 44

LTV: Estimated Lifetime Value. If the customer renews, it is 2 × Revenue; otherwise, it equals Revenue.

Campaign_ID: Identifier for digital marketing campaigns (values include 1–36, 501–548, or labels like 'Adwords' and 'Organic').

Dates: Date the marketing campaign started.
