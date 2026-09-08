# Data

This project uses the ACNC Registered Charities dataset (Australian
Charities and Not-for-profits Commission).

- Source: https://data.gov.au/ (search "ACNC Registered Charities")
- Not committed here (licensing + size).
- To reproduce: download the CSV, place it in this folder as
  `charities.csv`, then run `notebooks/analysis.ipynb`.
- Filtering applied: Country = Australia; operates in >=1 of the 8
  states/territories. ~38,000 rows after filtering.