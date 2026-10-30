# Lab 2: County School Installation Analysis

## Objective

This lab preprocesses the supplied county school dataset and explores unusual observations and groups of counties with similar school-installation profiles.

[Open the executed notebook](lab2_school_analysis.ipynb)

The notebook documents data inspection, county-name normalization, percentage and numeric conversion, source consistency checks, and preparation of three interpretable features. It applies an IQR baseline and Isolation Forest for anomaly detection, then compares K-means solutions using inertia, silhouette score, and the Davies–Bouldin index. Results, four graphs, county memberships, interpretations, and limitations are visible inside the notebook.

## Setup

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
jupyter lab lab2_school_analysis.ipynb
```
