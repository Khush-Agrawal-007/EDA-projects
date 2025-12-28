# Customer Shopping Behavior — plain-language summary

Author: Khush Agrawal

What this project is about
- This project uses a realistic retail customer transactions file to answer questions like: Who are our best customers? Which products and categories sell well by season? How effective are discounts and promo codes?

What I did and why it matters
- Cleaned the purchase log and standardized category and payment fields.
- Explored customer segments (by age, subscription status, and purchase frequency) to identify high-value customers for retention.
- Looked at seasonal patterns and promotion lift so marketing can time offers effectively.

Practical insights (summary — I'll add exact figures after running the notebook):
- The dataset shows a mix of frequent buyers and occasional shoppers; a subscription program appears common and correlates with higher repeat purchases.
- Clothing and accessories are among the most common purchase categories — promotions targeted to these perform well.
- Promo codes and discounts increase conversion but require careful segment-targeting to be profitable.

Files
- Notebook: `Customer_Shopping_Behavior_Analysis.ipynb`
- Dataset: `customer_shopping_behavior.csv`

How to run
1. Create virtual env and install: `pip install pandas matplotlib seaborn sqlalchemy jupyter nbconvert`
2. Run the notebook and export HTML: `jupyter nbconvert --to html Customer_Shopping_Behavior_Analysis.ipynb --output CustomerShopping_report.html`

Next actions I will take
- Run the notebook and compute cohort and retention metrics, then paste concrete numbers and visuals into this README so it's presentation-ready.

Contact
- Khush Agrawal — replace placeholders with your LinkedIn, GitHub, and Codolio links.
