I spent the past week building a fraud detection engine using pure SQL.

Dataset: 200,000 simulated transactions from an Indian payment aggregator (Razorpay-style).

Mission: Detect 12 different fraud patterns hidden in the data.

Some of the fraud patterns I detected:

Velocity fraud (30+ transactions by a user in a single day)
Card testing (30+ transactions under ₹10 in one day)
Round-amount clustering (money laundering)
Mule account detection
Structuring using ₹9,999 transactions to avoid KYC thresholds
Account takeover through dormant accounts and impossible travel
Monthly transaction spikes
High refund ratio
Merchant concentration
Failed transaction abuse
Odd-hour transaction concentration
And more...

Tools used:

MySQL
SQL (GROUP BY, HAVING, CASE WHEN, CTEs, Window Functions, LAG(), ROW_NUMBER(), EXISTS, TIMESTAMPDIFF())

No Python. No Machine Learning. No fintech APIs.

This project helped me understand how SQL can be used to identify suspicious financial activity and how fraud analysts investigate transaction data.

