# Flight Delay Prediction — plain English summary

Author: Khush Agrawal

Purpose
- Build and evaluate a model to predict flight delays. This helps airlines and travel platforms improve customer experience by anticipating delays and proactively communicating with passengers.

What I did
- Cleaned time and schedule fields, engineered delay windows and categorical encodings, and trained baseline classifiers.

Key takeaways (will be finalized after running code):
- Weather and time-of-day are strong delay predictors in many airports.
- Simple tree-based models typically give reasonable baseline performance and are easy to explain to stakeholders.

Files
- Notebook: `Main File/Flight Prediction/FlightPrediction.ipynb`

How to run
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install pandas scikit-learn xgboost matplotlib seaborn jupyter nbconvert
jupyter nbconvert --to html "Main File/Flight Prediction/FlightPrediction.ipynb" --output FlightPrediction_report.html
```

Next steps
- I will run the notebook fully, save a model artifact, and paste final evaluation metrics into this README.

Contact
- Khush Agrawal — add personal links.
