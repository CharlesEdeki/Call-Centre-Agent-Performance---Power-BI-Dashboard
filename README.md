# 📞 Call Centre Performance — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Operations](https://img.shields.io/badge/Operations%20Analytics-E05A00?style=flat)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

---

## Overview

An interactive Power BI dashboard analysing **5,000 call centre interactions** across Q1 2021 (January – March). Covers call answer rates, resolution rates, agent-level performance, and customer satisfaction — with monthly trend tracking and agent/topic filtering to give operations managers a complete picture of service quality and workload distribution.

> **Key Question:** *How effectively are calls being answered and resolved, which agents are performing best, and where are customers most dissatisfied?*

---

## Dashboard Preview

### Full Dashboard View
<img width="1073" height="596" alt="image" src="https://github.com/user-attachments/assets/3abec4eb-c341-46f7-9826-7dbdf81db90c" />
> 5,000 total calls · 81.08% answer rate · 72.92% resolution rate · Avg satisfaction 3.40/5 · Avg speed of answer 67.52 secs

---

## Dashboard Features

- **Average Satisfaction Gauge** — Radial gauge showing overall satisfaction score of 3.40 out of 5 across all calls
- **Answered Calls Donut** — Visual split between answered (81.08%) and unanswered (18.92%) calls
- **Resolved Calls Donut** — Resolution rate breakdown: 72.92% resolved vs 27.08% unresolved
- **Average Speed of Answer** — KPI card showing 67.52 seconds average response time across all agents
- **Calls Answered Monthly Bar Chart** — Side-by-side answered vs unanswered volumes for January (1,455 / 317), February (1,298 / 318), and March (1,301 / 311)
- **Agent Performance Table** — Per-agent breakdown of total calls handled, average satisfaction rating, and average speed of answer in seconds
- **Agent and Topic Slicers** — Filter the entire dashboard by individual agent or call topic (Streaming, Technical Support, Payment, Contract, Admin Support)

---

## Key Insights

> **Nearly 1 in 5 calls goes unanswered** (18.92% — 946 out of 5,000). Combined with a 27.08% unresolved rate, this means a significant portion of customers are leaving interactions without their issues addressed — a direct risk to retention.

> **Martha leads in satisfaction (3.47) but has the slowest answer speed (69.49 secs)**; Joe has the fastest resolution rate (73.5%) but the lowest satisfaction score (3.33). Agent performance is multi-dimensional — no single metric tells the full story.

> **Satisfaction scores are heavily clustered at 3** (1,218 calls) with meaningful volume at both 1 (417) and 5 (843), suggesting a polarised customer experience rather than a uniform average. The 3.40 mean masks this spread.

> **Resolution rates are nearly identical across all five topics** (72.2% – 74.1%), indicating that call complexity is consistent across categories rather than any one topic being disproportionately difficult to resolve.

> **Call volumes dropped from January to February and stayed flat in March** (1,772 → 1,616 → 1,612), but unanswered call counts remained almost unchanged (317 / 318 / 311) — meaning the miss rate is structural, not volume-driven.

---

## Tools & Skills Demonstrated

| Area | Detail |
|---|---|
| Data Source | Excel (.xlsx) — 5,000 rows, 11 columns |
| Visualisation | Gauge chart, donut charts, grouped bar chart, agent table |
| Interactivity | Agent and topic slicers controlling all visuals simultaneously |
| Analysis | Answer rate, resolution rate, per-agent KPI benchmarking |
| Operations Context | Call centre service metrics — CSAT, speed of answer, resolution tracking |

---

## How to Use

1. Download the `.pbix` file and dataset from the link above
2. Open in **Power BI Desktop** (free from Microsoft)
3. Connect to `01_Call-Center-Dataset.xlsx` when prompted
4. Use the **Agent** slicer to isolate any individual agent's performance
5. Use the **Topic** slicer to filter by call category (e.g. only Technical Support calls)
6. Read the donut charts and agent table together for a complete performance picture

---

## About

Built by **Charles Edeki**
📧 charlesedeki093@gmail.com | [LinkedIn](https://www.linkedin.com/in/charles-edeki/) | [GitHub](https://github.com/CharlesEdeki)
