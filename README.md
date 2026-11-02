# MSCS 634 — IPL Cricket Analytics: Deliverable 1

## Project overview
Data Collection, Cleaning, and Exploration of Indian Premier League (IPL) cricket matches and ball-by-ball deliveries. **Deliverable 1 only** (no predictive modeling yet).

## Dataset
- **Source:** [IPL Ball By Ball 2008 to 2025 on Kaggle](https://www.kaggle.com/datasets/dgsports/ipl-ball-by-ball-2008-to-2022)
- **Description / data dictionary:** [IPL-Hackathon DATA.md](https://github.com/SahilGogna/IPL-Hackathon/blob/main/DATA.md)
- **Original data attribution noted by guide:** Cricsheet
- **Files:** `matches.csv` (match-level), `deliveries.csv` (ball-by-ball)
- **Actual rows and columns:** TODO — enter after running the notebook.
- **Years covered:** TODO — verify from your downloaded files (Kaggle listing says 2008–2025).
- **Downloaded on:** TODO
- **Data source license/terms:** TODO — verify before redistributing any CSV.

## How to reproduce
1. Download the Kaggle dataset linked above.
2. Extract it and place the two CSV files at `data/raw/matches.csv` and `data/raw/deliveries.csv`. Rename only if needed; document original names.
3. Install dependencies: `python3 -m pip install -r requirements.txt`.
4. Launch Jupyter: `python3 -m jupyter lab` (or `python3 -m notebook`).
5. Open `MSCS_634_ProjectDeliverable_1.ipynb` and choose **Run All**.
6. Review results and add measured findings in the notebook/README.

## Main tasks
- Loaded and inspected both datasets (shape, dtypes, descriptive statistics, missing values).
- Checked for duplicate records, invalid numeric values and IDs.
- Standardized selected historical franchise-name aliases for aggregate charts.
- Recognized structural missingness (non-wicket deliveries have no dismissed player).
- Explored season trends, match wins, toss-vs-match outcomes, batting leaders, innings phases, and innings score distributions/outliers.

## Key findings
**TODO:** Replace with 4–6 findings and specific values from your notebook (do not invent results).

## Cleaning decisions
**TODO:** Note counts before/after cleaning, fields normalized, anomalies found, and rationale for retaining/removing rows. Document possible team identity mismatches and unusual match results.

## Challenges and resolutions
**TODO:** Describe any inconsistent field names, missingness, installation/SSL issues, suspicious records, and how you handled them.

## Future project phases
Regression, classification, clustering, and pattern mining may be developed in later deliverables. No models were built for Deliverable 1.

## Visualizations
Screenshots are saved to the `screenshots/` directory when the notebook is executed.

