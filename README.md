# PeoplePulse — Workforce Intelligence

An interactive HR analytics dashboard that turns employee-level data into clear, actionable workforce insights — built around attrition, employee experience, compensation, performance, and retention risk.

**🔗 Live demo:** https://sabihashaikh-01.github.io/PeoplePulse_Dashboard/ 

---

## Overview

PeoplePulse analyzes a dataset of **1,400+ employee records** to help answer:

> *What is happening to our workforce, where are the risks, and what factors appear to be associated with employee attrition?*

It's built as a single self-contained HTML/CSS/JavaScript file — no backend, no build step, no dependencies. Open it in a browser and it works.

---

## Features

- **Executive Overview** — dynamic KPIs (attrition rate, headcount, tenure, satisfaction), an attrition donut chart, and an auto-generated workforce narrative
- **Attrition Intelligence** — attrition broken down by job role, salary band, job level, tenure, and a job role × overtime heatmap
- **Employee Experience** — satisfaction distributions and a calculated Experience Score (clearly labeled as a custom metric, not an industry standard)
- **Compensation & Performance** — salary distribution, income vs. tenure scatter plot, and correlation analysis
- **Workforce Segmentation** — an interactive segment comparison engine (headcount, attrition, income, satisfaction, performance by any chosen dimension)
- **Employee Explorer** — a searchable, sortable, paginated employee table with a detail drawer and CSV export
- **Retention Watchlist** — flags workforce segments with attrition meaningfully above the overall rate, with an adjustable minimum group-size threshold
- **Ask Your Workforce Data** — a controlled natural-language query interface for common workforce questions
- **Global filters** — 12 filters (department, role, gender, age group, overtime, salary slab, etc.) that update every KPI, chart, and insight live

---

## Data

- **Source file:** `HR_Analytics.csv`
- Duplicate rows are removed from the working copy only — the source file is never modified
- Missing values, constant columns, and inconsistent category labels are detected and handled explicitly (see the **Data Quality** panel in the sidebar)
- All KPIs and insights are calculated dynamically from the data — nothing is hardcoded or fabricated

**Important:** all attrition "drivers" and watchlist segments are described as *associations*, not causes. This is a descriptive analytics tool, not a predictive model.

---

## Tech Stack

- Vanilla **HTML5 / CSS3 / JavaScript** (no frameworks, no build tools)
- Data embedded directly in the page for a fully static, portable deliverable
- Responsive layout with a dark, glassmorphism-inspired UI

---

## Running Locally

No installation needed:

1. Clone or download this repo
2. Open `index.html` directly in any modern browser

Or just visit the live GitHub Pages link above.

---

## Disclaimer

This dashboard is a analytics project. Insights reflect patterns observed in the dataset only and should not be treated as HR policy recommendations without further validation.

---

Built with data-driven workforce analytics.
