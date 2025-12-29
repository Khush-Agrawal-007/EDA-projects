# Black Friday EDA & Feature Engineering â€” human summary

Author: Khush Agrawal

Why this project exists
- This notebook walks through exploratory analysis and feature engineering for a retail Black Friday sales dataset. The goal is to prepare data for models that predict purchase amount or recommend products, and to surface practical retail takeaways.

Human summary of findings (high-level):
- Data required careful handling of missing user/product attributes and categorical encodings.
- Feature engineering (e.g., aggregating past purchases, encoding user segments) materially improves model readiness.
- Important business takeaways: customer segmentation, identification of high-value product categories, and features that explain most of the purchase-value variance.

Files
- Notebook: `Main File/2- BlackFriday EDA And Feature Engineering.ipynb`

How to run
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install pandas numpy scikit-learn matplotlib seaborn jupyter nbconvert
jupyter nbconvert --to html "Main File/2- BlackFriday EDA And Feature Engineering.ipynb" --output BlackFriday_report.html
```

Next steps
- I will run the notebook, capture the feature list and model notes, and paste concrete performance metrics into this README.

Contact
- Khush Agrawal â€” add LinkedIn/GitHub/Codolio links.


