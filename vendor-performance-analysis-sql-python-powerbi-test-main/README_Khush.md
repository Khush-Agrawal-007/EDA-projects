# Vendor Performance Analysis â€” Retail Inventory & Sales

**Author:** Khush Agrawal

**Contact:**
- LinkedIn: <YOUR_LINKEDIN_URL>
- GitHub: <YOUR_GITHUB_URL>
- Codolio / Portfolio: <YOUR_CODOLIO_URL>

Project summary
- Notebooks: `notebooks/exploratory_data_analysis.ipynb`, `notebooks/vendor_performance_analysis.ipynb`
- Scripts: `scripts/ingestion_db.py`, `scripts/get_vendor_summary.py`
- Objective: Evaluate vendor efficiency, inventory turnover, and profitability to guide purchasing and pricing decisions.

How to run
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install pandas numpy matplotlib seaborn sqlalchemy notebook nbconvert
python scripts/ingestion_db.py
python scripts/get_vendor_summary.py
jupyter nbconvert --to html notebooks/vendor_performance_analysis.ipynb --output VendorPerformance_report.html
```

Next steps
- I will run the ingestion scripts and notebooks, then summarize statistical test results and final recommendations.

