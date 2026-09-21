# Kevin Abdallah

**M.Sc. Mathematics · Data analyst · Fraud operations at RBC · Laval, QC**

I build analytics end to end — raw data through cleaning, modelling and validation to something
deployed that a non-technical person can actually use. I care more about whether a model is
*defensible* than whether it scores well: leak-free splits, stated uncertainty, and predictions
committed to before the outcome is known.

Currently a Fraud Officer at RBC, completing an Applied AI & Data Science program at McGill,
and working toward financial-crime analytics.

---

## Projects

### [Retail Retention & Customer Lifetime Value](https://github.com/idkibebs/retail-retention)
`Python` · `scikit-learn` · `Streamlit` · [**live dashboard →**](https://retail-retention-kevin.streamlit.app)

1.07M transactions → 779,425 auditable line items, every exclusion counted and explained.
A **time-aware, leak-free** repeat-purchase model at **ROC-AUC 0.81**, RFM segmentation
(1,473 Champions = 25% of customers, 69% of revenue), and a CLV ranking that concentrates
42% of predicted value in the top decile. Shipped with pytest and CI.

### [Estimating BIXI's Revenue from Open Data](https://github.com/idkibebs/bixi-revenue-model)
`Python` · `pandas`

BIXI publishes 5.6M trip records but not its revenue. I reconstructed the missing number from
first principles and checked it against the audited statements: mid-case **$7.52M vs. $6.32M
audited (+19%)**, with an uncertainty band that contained the truth. The sensitivity analysis
flagged the dominant error source in advance — and back-solving the model confirmed it.

### [BIXI Destination Coupons](https://github.com/idkibebs/bixi-destination-coupons)
`Python` · `geospatial` · [**interactive prototype →**](https://idkibebs.github.io/bixi-destination-coupons/prototype/)

14.2M trips, 128 chronically underused stations, and a partner-funded incentive mechanism that
costs the operator nothing. Includes an **out-of-sample forward test** — predictions published
*before* the week they forecast, then scored.

### [BIXI GBFS Logger](https://github.com/idkibebs/Bixilogger)
`Python` · `GitHub Actions`

The trip history shows rides that happened, never demand that went unmet. So I built a logger
that snapshots the live availability feed every 5 minutes — **~5.95M snapshots over 10 weeks**,
running unattended on free infrastructure, engineered around platform throttling.

---

## Toolkit

**Languages** Python (pandas, scikit-learn, NumPy) · SQL · R
**Methods** Leak-free validation · class imbalance · cost-sensitive thresholds · cohort & RFM analysis · sensitivity analysis · forward testing
**Engineering** Reproducible pipelines · pytest · GitHub Actions · API ingestion · dashboard deployment
**Spoken** French · English · Arabic

---

📫 [LinkedIn](https://linkedin.com/in/kevin-abdallah) · kevin.j.abdallah@gmail.com
