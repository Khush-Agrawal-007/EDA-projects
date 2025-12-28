# Vendor Performance — plain-language overview

Author: Khush Agrawal

Project purpose
- This project helps retail teams understand which vendors drive sales and profit, which inventory sits unsold, and whether bulk purchasing is cost-effective — the kinds of insights purchasing managers use to negotiate and plan.

What I found (summary from the existing analysis)
- There are brands with low sales but high margins that could be promoted to increase revenue without heavy discounting.
- A small group of vendors account for a large share of purchases — diversifying can reduce supply risk.
- Bulk purchasing shows cost benefits in many cases, but it must be balanced against inventory turnover and storage costs.

Files
- Notebooks: `notebooks/exploratory_data_analysis.ipynb`, `notebooks/vendor_performance_analysis.ipynb`
- Scripts: `scripts/ingestion_db.py`, `scripts/get_vendor_summary.py`

How to run
1. Create environment and install deps: `pip install pandas numpy matplotlib seaborn sqlalchemy jupyter nbconvert`
2. Ingest data and create summaries: `python scripts/ingestion_db.py` then `python scripts/get_vendor_summary.py`
3. Export notebook: `jupyter nbconvert --to html notebooks/vendor_performance_analysis.ipynb --output VendorPerformance_report.html`

Next steps
- I will run the ingestion and analysis notebooks, validate the statistical tests, and publish the exact figures and charts into this README.

Contact
- Khush Agrawal — add LinkedIn/GitHub/Codolio links.
