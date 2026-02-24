<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Kaviarasan+M+%F0%9F%91%8B;SDET+III+%40+UST;Data+Quality+Engineer;Open+Source+Author" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kaviarasanmani&label=Profile+Views&color=00d4ff&style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20Source-ValidateX%20on%20PyPI-brightgreen?style=flat-square&logo=pypi&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Trivandrum%2C+India-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-blue?style=flat-square" />
</p>

---

## 🧪 I don't just test data pipelines — I build the tools that test them.

I'm a **Senior SDET (SDET III) at UST** specializing in **Data Quality Engineering and ETL Automation Testing**. With 4+ years of experience validating production-scale PySpark pipelines (10M+ records/day), I sit at the intersection of data engineering and QA — catching the bugs that hide *inside* your data, not just your code.

In 2026, I published **[ValidateX](https://github.com/kaviarasanmani/ValidateX)** — a lightweight Python data quality validation framework — to PyPI. Because after years of writing the same validation boilerplate across projects, I decided to ship it as a library instead.

```python
pip install validatex
```

---

## 🚀 Featured: ValidateX

> **A lightweight, production-ready data quality validation framework for Python**
> Supports Pandas & PySpark • 25+ built-in expectations • Weighted quality scoring • Modern HTML reports

[![PyPI Latest Version](https://img.shields.io/pypi/v/validatex.svg?style=for-the-badge&logo=pypi&logoColor=white&color=00d4ff)](https://pypi.org/project/validatex/)
[![Build Status](https://img.shields.io/github/actions/workflow/status/kaviarasanmani/ValidateX/tests.yml?branch=main&style=for-the-badge&logo=github)](https://github.com/kaviarasanmani/ValidateX/actions/workflows/tests.yml)
[![Code Coverage](https://img.shields.io/badge/coverage-96%25-brightgreen?style=for-the-badge)](https://github.com/kaviarasanmani/ValidateX)
[![Tests](https://img.shields.io/badge/tests-66%20passed-brightgreen?style=for-the-badge)](https://github.com/kaviarasanmani/ValidateX)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge)](https://github.com/kaviarasanmani/ValidateX/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/python-3.9+-blue?style=for-the-badge&logo=python&logoColor=white)](https://pypi.org/project/validatex/)

```python
import pandas as pd
import validatex as vx

suite = (
    vx.ExpectationSuite("production_data")
    .add("expect_column_to_not_be_null",          column="user_id")
    .add("expect_column_values_to_be_unique",      column="user_id")
    .add("expect_column_values_to_be_between",     column="age", min_value=0, max_value=150)
    .add("expect_column_values_to_match_regex",    column="email", regex=r"^[\w.]+@[\w]+\.\w+$")
)

result = vx.validate(df, suite)
print(result.summary())          # Data Quality Score: 97/100
result.to_html("report.html")    # Beautiful dark-theme HTML report
```

**Why ValidateX?**

| | ValidateX | Great Expectations |
|---|---|---|
| **Setup** | `pip install` → validate in 5 lines | Multi-step setup with contexts & stores |
| **Quality Score** | ✅ Weighted 0–100 | ❌ |
| **Severity Levels** | ✅ Critical / Warning / Info | ❌ |
| **CI/CD CLI** | ✅ Built-in | ❌ |
| **Learning Curve** | Minutes | Hours to days |

📦 **[PyPI](https://pypi.org/project/validatex/)** • 💻 **[GitHub](https://github.com/kaviarasanmani/ValidateX)** • 📖 **[Docs](https://validatex.readthedocs.io/)**

---

## 💼 What I Do

```
┌─────────────────────────────────────────────────────────────┐
│  ETL Testing          →  Validate PySpark pipelines at scale │
│  Data Quality         →  Schema checks, SCD-2, drift detect  │
│  Test Automation      →  Selenium + Robot Framework + pytest │
│  Open Source          →  Building tools the data world needs │
│  CI/CD Integration    →  Jenkins, GitHub Actions, Airflow    │
└─────────────────────────────────────────────────────────────┘
```

**By the numbers from my 4+ years in production:**

- 🔴 **60%** reduction in data quality issues through automated testing frameworks
- ⚡ **40%** reduction in manual reconciliation effort via Python automation
- 📊 **10M+** records/day validated across PySpark ETL pipelines
- 🧪 **96%** code coverage on ValidateX (66 tests passing)

---

## 🛠️ Tech Stack

**Data & ETL**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Azure%20Databricks-EF3B2D?style=flat-square&logo=databricks&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-36AEBE?style=flat-square)

**Testing & Automation**

![Robot Framework](https://img.shields.io/badge/Robot%20Framework-000000?style=flat-square&logo=robotframework&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Cloud & Storage**

![Azure Data Lake](https://img.shields.io/badge/Azure%20Data%20Lake-0089D6?style=flat-square&logo=microsoftazure&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📂 Projects

### 🧪 [ValidateX](https://github.com/kaviarasanmani/ValidateX) — *Published on PyPI*
Open-source Python data quality validation framework. Pandas + PySpark support, 25+ expectations, severity scoring, HTML reports, CLI for CI/CD integration.
`pip install validatex`

### 📈 [NSE/BSE Stock Market Data Ingestion Tool](https://github.com/kaviarasanmani)
Python ETL pipeline for Indian stock market data — bulk ingestion via CSV/Excel, OHLCV schema normalization, API constraint handling, Streamlit control layer. A hands-on data engineering project focused on ingestion, transformation, and delivery.

---

## 🏅 Certifications

- 🏆 **Databricks — Data Governance Fundamentals** (Jan 2026)
- 🏆 **Databricks — Databricks Fundamentals** (Nov 2025)
- 📜 **Big Data Analytics with Hadoop & Apache Spark** — LinkedIn Learning (Sep 2025)
- 📜 **Selenium WebDriver with Python** — Udemy (Apr 2025)
- 📜 **Getting Started in Test Automation Engineering** — LinkedIn Learning (Apr 2025)

---

## ✍️ Writing

I write about data engineering, ETL automation, and real-world pipeline challenges on Medium.

📝 **[medium.com/@kavim1996](https://medium.com/@kavim1996)**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kaviarasanmani&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kaviarasanmani&theme=tokyonight&hide_border=true" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kaviarasanmani&layout=compact&theme=tokyonight&hide_border=true" width="40%" />
</p>

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/kaviarasanmani/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://medium.com/@kavim1996" target="_blank">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
  <a href="https://pypi.org/project/validatex/" target="_blank">
    <img src="https://img.shields.io/badge/PyPI-validatex-blue?style=for-the-badge&logo=pypi&logoColor=white" />
  </a>
  <a href="mailto:kavikavi41@rocketmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <i>"Bad data is worse than no data — it gives you false confidence."</i><br/>
  <i>That's why I build systems that catch it before it reaches your dashboards.</i>
</p>
