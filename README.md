# # Data Analysis Notebooks 
A collection of Python notebooks exploring real-world datasets in education, research, and open source community analysis.

Written with reproducibility and clarity in mind. Each notebook is self-contained, well-documented, and designed to be run top to bottom without side effects.

---

## Notebooks

### 01 — Global Education Access EDA
`01_education_access_eda.ipynb`

Explores trends in primary school enrolment and youth literacy rates across global regions using World Bank Education Statistics data.

Topics covered:
- Data loading and cleaning with Pandas
- Summary statistics by group
- Multi-line trend charts with Matplotlib
- Scatter plots and Pearson correlation
- Written interpretation of findings

### 02 — Open Source Contributor Activity Analysis
`02_contributor_activity_analysis.ipynb`

Analyses contributor behaviour patterns in an open source project — who contributes, how often, what type of contributions, and when activity peaks.

Topics covered:
- Simulating realistic contributor data (Pareto distribution)
- Contribution type breakdowns
- Monthly and day-of-week activity trends
- Identifying core contributors vs casual participants
- Community manager insights derived from the data

---

## Requirements

```
bash

pip install pandas numpy matplotlib

```

Or use the included requirements file:

```bash
pip install -r requirements.txt
```
l
---

## Running the notebooks

```bash
jupyter notebook
```
Then open any `.ipynb` file from the browser interface.

---
