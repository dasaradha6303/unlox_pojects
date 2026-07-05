I spent a weekend building a Python tool that analyzes
6 months of my UPI transactions.

Some findings about my own spending were… uncomfortable:

36.9% of my spend went to E-commerce
20.4% of my food-delivery orders happen after 9 PM
I spend roughly ₹66,000+ on Quick Commerce in 6 months
My personality archetype: THE SHOPAHOLIC + THE YOLO SPENDER

What surprised me most wasn’t where the money went —
it was how predictable my patterns actually are.

Built using only Python fundamentals, NumPy, and Pandas.

No fintech APIs. No ML. No matplotlib.
Just clean analytics on messy bank-export data — the kind of work transaction-analytics teams at Cred / Slice / Jupiter deal with every day.

This project included:

Category-wise spend breakdown
Monthly spending trends
Time-of-day behavior analysis
Z-score based anomaly detection
Behavioral archetype classification

Turns out, your bank statement knows your lifestyle better than you do.





==============================================
📊 SpendDNA REPORT - RAHUL SHARMA
6 months • 1328 transactions • Jan - Jun 2024
==============================================

📌 EXECUTIVE SUMMARY

Total Debits     : Rs. 1,729,708
Total Credits    : Rs.   509,774
Net Change       : Rs. -1,219,934 (Overspending)
Savings Rate     : -239.3% (BURNING SAVINGS 🔥)

==============================================

📊 TOP CATEGORIES (% of debit total)

E-commerce        ██████████████████████  36.9%  Rs. 638,210
Investments       ████████████            14.3%  Rs. 248,160
Food Delivery     ██████████              10.6%  Rs. 183,637
Utilities         ████████                 8.8%  Rs. 152,245
Restaurants       █████                    5.7%  Rs. 97,912
Fuel              █████                    5.6%  Rs. 96,567
Quick Commerce    ███                      3.9%  Rs. 66,619
Groceries         ███                      3.4%  Rs. 59,407
Transport         ██                       2.7%  Rs. 46,062
Cash Withdrawal   ██                       2.6%  Rs. 45,500
Cafe              █                        1.8%  Rs. 31,445
Subscriptions     █                        1.1%  Rs. 18,471
Entertainment     █                        0.5%  Rs. 8,293

==============================================

🏆 TOP VENDORS

Amazon            Rs. 348,447   (87 orders)
Zerodha           Rs. 248,160   (23 orders)
Flipkart          Rs. 191,926   (48 orders)
House Rent        Rs. 108,000   (6 orders)
Swiggy            Rs. 106,758   (248 orders)
Zomato            Rs. 76,879    (134 orders)
Myntra            Rs. 69,529    (20 orders)
IOCL Petrol Pump  Rs. 63,599    (18 orders)
Cash Withdrawal   Rs. 45,500    (17 orders)
Generic Restaurant Rs. 44,978   (29 orders)

==============================================

⏰ TIME-OF-DAY PATTERNS

🍔 Food Delivery peak : 78 orders (20.4%)
☕ Cafe peak          : 38 orders (38.4%)
🚚 Quick Commerce     : Evenly distributed

==============================================

📈 MONTHLY TREND (Food Delivery)

Jan  Rs. 24,329  ##########
Feb  Rs. 30,781 ############
Mar  Rs. 29,483 ############
Apr  Rs. 33,303 #############
May  Rs. 30,016 ############
Jun  Rs. 35,725 ###############

==============================================

🚨 TOP ANOMALIES (3+ stddev)

22 Jun - Zomato              Rs. 7,935   (z=17.1)
26 Feb - Generic Restaurant  Rs. 8,383   (z=4.0)
26 Jun - Amazon              Rs. 22,008  (z=3.9)
07 Feb - Amazon              Rs. 21,986  (z=3.9)
31 Mar - Meghana Foods       Rs. 7,931   (z=3.8)
04 Mar - Truffles            Rs. 7,441   (z=3.5)
05 Mar - Amazon              Rs. 19,917  (z=3.4)
02 Mar - Amazon              Rs. 18,273  (z=3.1)

==============================================

🧠 SPENDING ARCHETYPES

-> THE FOODIE (18.1% on food)
-> THE SHOPAHOLIC (36.9% on e-commerce)
-> THE LATE-NIGHT SNACKER (20.4% on food after 9 PM)
-> THE YOLO SPENDER (-239.3% savings)

==============================================
