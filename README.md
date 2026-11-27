## José Paz Rangel Rojas

**Data & Machine Learning Engineer** — I build the data systems a real estate
and media group in Mexico runs on: incremental ELT into Snowflake,
anti-money-laundering regulatory reporting, geospatial dashboards, and
machine learning on top of them. Actuary by training, which is mostly why I
care whether a number can be defended.

### ▶ [**Portfolio with live demos → Paz-RangelR.github.io**](https://Paz-RangelR.github.io)

Four of the projects below are **interactive apps you can open right now**.
All of them run on synthetic data and need no credentials.

---

### Projects

| Project | What it is | |
|---|---|---|
| **[Property Portfolio — Geospatial](https://github.com/Paz-RangelR/property-portfolio-geo)** | Every property on one map. Areas measured geodesically from each parcel's own polygon; values restated for inflation. Built twice — R/Shiny and Python/Dash — over the same warehouse. | [▶ Demo](https://property-portfolio-geo.streamlit.app) |
| **[Land Valuation Model](https://github.com/Paz-RangelR/property-valuation-model)** | What is this parcel worth, and how sure? Returns a **calibrated range, not a number** — 90% promised, 90.2% measured. Finds the purchases made outside the market. | [▶ Demo](https://property-valuation-model.streamlit.app) |
| **[Retail Space Manager](https://github.com/Paz-RangelR/retail-space-manager)** | Leasing for three shopping centres. Releasing a unit **never deletes anything** — it posts negative square metres, so history and current state cannot drift apart. | [▶ Demo](https://retail-space-manager.streamlit.app) |
| **[AML Anomaly Detection](https://github.com/Paz-RangelR/pld-anomaly-detection)** | Unsupervised review queue for money-laundering risk, when nobody has ever labelled a case. 10.1× better than chance at a fixed review budget. | [▶ Demo](https://pld-anomaly-detection.streamlit.app) |
| **[ERP → Snowflake ELT](https://github.com/Paz-RangelR/erp-snowflake-elt)** | Incremental load of 24 entities from a paginated ERP API. `MERGE` on a content hash that **excludes the timestamps**, because the ERP restamps rows it never changed. | |
| **[Bank Reconciliation — Host-to-Host](https://github.com/Paz-RangelR/bank-reconciliation-h2h)** | Hourly reconciliation of a bank feed against ERP invoices, with a six-hour overlapping window because banks backfill. | |
| **[Bank Statement Consolidator](https://github.com/Paz-RangelR/bank-statement-consolidator)** | An Excel VBA macro rebuilt as an application: 78 classification rules, header-row detection, 525 movements, none unclassified. | |

---

### Stack

**Python** — pandas, scikit-learn, Streamlit, Dash, pytest · the pipelines, the
models and every live demo
**SQL / Snowflake** — incremental ELT, `MERGE`, data-quality views, Cortex agents
**R** — Shiny, `sf`, plumber · two production systems, and the reason some
repositories read as R-heavy
**AWS** — Cognito (OAuth2 + JWT), S3, CodeBuild

### Working on

An AWS Machine Learning Engineer Associate certification, and moving the
modeling work closer to production instead of next to it.

### Contact

[LinkedIn](https://www.linkedin.com/in/jos%C3%A9-paz-rangel-rojas-9a49b7334) ·
[pazjpaz17@gmail.com](mailto:pazjpaz17@gmail.com) ·
[soltecmty.com](http://soltecmty.com) — independent consulting

📍 Mexico
