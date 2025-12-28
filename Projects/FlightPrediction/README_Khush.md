# Flight Delay Prediction — Notebook

**Author:** Khush Agrawal

**Contact:**
- LinkedIn: <YOUR_LINKEDIN_URL>
- GitHub: <YOUR_GITHUB_URL>
- Codolio / Portfolio: <YOUR_CODOLIO_URL>

Project summary
- Notebook: `Main File/Flight Prediction/FlightPrediction.ipynb`
- Objective: Build a model to predict flight delays using available features; evaluate metrics and provide deployment notes.

How to run
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install pandas scikit-learn xgboost matplotlib seaborn notebook nbconvert
jupyter nbconvert --to html "Main File/Flight Prediction/FlightPrediction.ipynb" --output FlightPrediction_report.html
```

Next steps
- I will run end-to-end training cells, save the trained model artifact, and summarize model performance (precision/recall/AUC).
