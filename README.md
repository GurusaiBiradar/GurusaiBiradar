# Hi, I'm Guru 👋

### Data Scientist → Quantitative Asset Management

MS Computer Science (Data Science) student at RPTU Kaiserslautern, Germany, working at the intersection of machine learning and financial markets. My research and projects focus on asset pricing, factor models, and portfolio construction.

Currently building: **[Decoding Stock Return Predictors with KANs](https://github.com/GurusaiBiradar)** at RPTU's Financial Management Department.

---

## 🔬 Featured Projects

### 📈 [Icarus — Quantitative Portfolio Research Pipeline](https://github.com/GurusaiBiradar/Icarus-Quant-Portfolio-Research-Pipeline)
> End-to-end equity factor research: signals → risk model → optimizer → walk-forward backtest

- **Alpha signals:** Momentum + Reversal (12-1 month, 1-month returns)
- **Risk model:** Ledoit-Wolf shrinkage covariance estimation
- **Optimizer:** Mean-variance (cvxpy), long-only, max 10% concentration
- **Backtest:** 47 monthly out-of-sample periods (2019–2024), benchmarking XGBoost vs rank-average via **Sharpe ratio** and **IC**

`Python` `cvxpy` `XGBoost` `scikit-learn` `Streamlit`

---

### 🧠 AlphaDecoderKAN — Decoding Functional Forms of Stock Return Predictors
> Applying Kolmogorov-Arnold Networks to global asset pricing data (LSEG)

- Benchmarking KAN interpretability and predictive accuracy against MLPs and linear regressions
- Evaluating **150+ cross-sectional predictors** on international market data
- Constructing and backtesting portfolios from newly-identified non-linear predictors
- Running on HPC clusters at RPTU

`Python` `PyTorch` `HPC` `LSEG Data` `Asset Pricing`

---
 
### 🏗️ [Osiris — DAX 15 Low Volatility Index Pipeline](https://github.com/GurusaiBiradar/Osiris-dax15-lowvol-index-pipeline)
> Production-style index construction pipeline replicating real index provider methodology
 
- **Index methodology:** selects the 15 lowest-volatility stocks from the DAX 40 universe via trailing 12-month realized volatility ranking, weighted by inverse-volatility
- **Divisor continuity:** index level maintained across monthly rebalances, constituent changes, and stock splits — no artificial jumps
- **Buffer/banding rules:** entry at rank ≤ 12, exit at rank > 20 — mirrors real index provider turnover controls
- **Pipeline:** PostgreSQL → dbt transformations → Apache Airflow orchestration → Streamlit dashboard with PDF reporting
`Python` `PostgreSQL` `Docker` `Airflow` `dbt` `Streamlit` `pytest`

---

## 🛠️ Tech Stack
 
**Programming**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
 
**Finance & Quant**
 
![cvxpy](https://img.shields.io/badge/cvxpy-013243?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-026E00?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
 
**Data Engineering & Infrastructure**
 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
 
**Business Intelligence**
 
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 🏅 Recognition

- 🎓 Two-time **Deutschlandstipendium** scholar (1% acceptance rate) — BMBF, Germany
- 🏆 All India Rank **396 / 400,000** — UPSC NDA
- 📜 Commendation from the **Indian Minister of Education** — Perfect 10/10 CGPA, Grade 10

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gurusaibiradar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gurusaibiradar@gmail.com)

---

*Open to Werkstudent, internship and full-time roles in quantitative research and portfolio management — Open to relocation*
