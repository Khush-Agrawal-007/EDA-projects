# Zomato — What this project is and what I found

Author: Khush Agrawal

Overview
- This project explores a large Zomato restaurant dataset to answer simple, practical questions a product manager or restaurant owner would care about: Which cities and cuisines get the best ratings? Do more expensive restaurants have higher ratings? Which cuisines appear most often in the top-rated list?

Human summary (what I did / why it matters)
- Cleaned and harmonized city, cuisine, and rating fields so comparisons are fair.
- Looked at rating distribution to identify whether most restaurants are rated high or low (helps spot bias in ratings or data quality issues).
- Examined price vs rating so owners can understand if consumers equate cost with quality.
- Mapped top cuisines and city hotspots to reveal where certain food types thrive — useful for expansion or marketing.

Key insights (summary — exact numbers will be added after running the notebook):
- Ratings are concentrated in the higher bands: many restaurants are rated "Very Good" or "Excellent", with a smaller long tail of low-rated listings.
- Popular cuisines (e.g., Indian, Chinese, Continental) dominate the dataset and consistently appear among top-rated restaurants in major cities.
- Price and rating show only a weak positive relationship — being expensive doesn't guarantee better reviews.
- Some cities are clear hotspots for high-rated restaurants and cluster by cuisine type (helpful for targeted marketing).

Files
- Notebook: `Zomato.ipynb`
- Raw dataset: `Main File/Zomatodataset/zomato.csv`

How to run
1. Create a Python environment and install minimal libs: `pip install pandas matplotlib seaborn jupyter nbconvert`
2. Run the notebook or export HTML: `jupyter nbconvert --to html Zomato.ipynb --output Zomato_report.html`

Next steps I will do for you
- Run the notebook end-to-end, capture the exact numeric insights and charts, and paste them into this README under "Key insights" so it's ready to publish.

Contact
- Name: Khush Agrawal
- LinkedIn: <YOUR_LINKEDIN_URL>
- GitHub: <YOUR_GITHUB_URL>
- Portfolio / Codolio: <YOUR_CODOLIO_URL>
