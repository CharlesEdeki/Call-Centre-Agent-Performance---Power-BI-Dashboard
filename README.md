# 📞 Call Centre Performance — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Operations](https://img.shields.io/badge/Operations%20Analytics-E05A00?style=flat)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

---

## Dashboard Preview

### Full Dashboard View
<img width="1073" height="596" alt="image" src="https://github.com/user-attachments/assets/3abec4eb-c341-46f7-9826-7dbdf81db90c" />
> 5,000 total calls · 81.08% answer rate · 72.92% resolution rate · Avg satisfaction 3.40/5 · Avg speed of answer 67.52 secs

---

## The Problem with "Average"

A call centre that fails to answer nearly 1 in 5 calls — and fails to resolve more than 1 in 4 of those it does answer — has a structural service delivery problem, not a performance reporting problem. This analysis examines **5,000 call centre interactions** across Q1 2021 to identify where the gaps are, which agents and topics are most affected, and what the data says about the path to improvement.

The 3.40/5.0 average satisfaction score sits squarely in the middle — not a crisis, but not competitive either. Beneath that average is a more telling story: customers are polarising, and the operational data explains why.

> **Key Question:** *Why are 946 calls going unanswered, what is driving a 27% unresolution rate, and what does agent-level performance data reveal about where improvement is possible?*

---

## About the Data

| Field | Detail |
|---|---|
| Source | Call Centre Operations Dataset |
| Total records | 5,000 calls |
| Period | January – March 2021 (Q1) |
| Variables | Agent, date, topic, answered flag, resolved flag, speed of answer, talk duration, satisfaction rating |

---

## What the Dashboard Shows

- **Average Satisfaction Gauge** — Radial gauge displaying 3.40/5.0 overall score across all calls
- **Answered Calls Donut** — 81.08% answered vs. 18.92% unanswered split
- **Resolved Calls Donut** — 72.92% resolved vs. 27.08% unresolved split
- **Average Speed of Answer KPI** — 67.52 seconds across all agents
- **Calls Answered Monthly Bar Chart** — January (1,455/317), February (1,298/318), March (1,301/311) answered vs. unanswered
- **Agent Performance Table** — Per-agent call count, avg satisfaction rating, avg speed of answer
- **Agent and Topic Slicers** — Full dashboard filtering by individual agent or call topic

---

## What the Numbers Actually Say

### By the Numbers

| Metric | Value |
|---|---|
| Total Calls | 5,000 |
| Answer Rate | **81.08%** (4,054 answered) |
| Unanswered Calls | **18.92%** (946 calls lost) |
| Resolution Rate | **72.92%** (3,646 resolved) |
| Unresolved Calls | **27.08%** (1,354 calls) |
| Avg Satisfaction | **3.40 / 5.0** |
| Avg Speed of Answer | **67.52 seconds** |

### The Unanswered Call Problem

946 calls went unanswered across Q1 — and the monthly breakdown reveals the problem is structural, not volume-driven:

| Month | Answered | Unanswered | Miss Rate |
|---|---|---|---|
| January | 1,455 | 317 | 17.9% |
| February | 1,298 | 318 | 19.7% |
| March | 1,301 | 311 | 19.3% |

January had the highest call volume and the lowest miss rate. February saw volume drop by 8% while the unanswered count stayed almost identical. The miss rate is not being driven by call volume spikes — it persists regardless of demand level. This points to a staffing or routing constraint that is independent of how busy the centre is.

### Unanswered Rate by Topic

Technical Support calls are the hardest to reach an agent for:

| Topic | Unanswered Rate |
|---|---|
| Technical Support | **21.0%** |
| Contract related | 19.2% |
| Payment related | 18.8% |
| Admin Support | 18.5% |
| Streaming | **17.1%** |

Customers with technical issues — often the most frustrated to begin with — are the most likely to fail to reach anyone. This compounds dissatisfaction before the conversation even begins.

### Resolution Rate by Topic

Conversely, resolution rates are nearly flat across all topics:

| Topic | Resolution Rate |
|---|---|
| Admin Support | 74.1% |
| Streaming | 73.3% |
| Contract related | 72.6% |
| Payment related | 72.4% |
| Technical Support | **72.2%** |

The 1.9% spread between the best and worst topic resolution rates suggests agents are broadly equally equipped across categories. The resolution problem is not topic-specific knowledge — it is a systemic ceiling on what agents can resolve in a single interaction.

### Agent Performance Analysis

| Agent | Calls | Answer Rate | Resolve Rate | Avg Satisfaction | Avg Speed (secs) |
|---|---|---|---|---|---|
| Martha | 638 | 80.6% | 72.3% | **3.47** | 69.49 |
| Dan | 633 | **82.6%** | **74.4%** | 3.45 | 67.28 |
| Diane | 633 | 79.1% | 71.4% | 3.41 | 66.27 |
| Greg | 624 | 80.4% | 72.9% | 3.40 | 68.44 |
| Stewart | 582 | 82.0% | 72.9% | 3.40 | **66.18** |
| Jim | 666 | 80.5% | 72.8% | 3.39 | 66.34 |
| Becky | 631 | 81.9% | 73.2% | 3.37 | 65.33 |
| Joe | 593 | 81.6% | 73.5% | 3.33 | **70.99** |

Three findings stand out:

**Martha leads in satisfaction but is the slowest to answer.** Her 69.49-second speed is the second slowest of any agent, yet customers rate her highest. Speed of answer and satisfaction are effectively uncorrelated (correlation coefficient: 0.001) — customers care about quality of interaction, not how quickly the phone is picked up.

**Dan leads in both answer rate and resolution rate** while maintaining the second-highest satisfaction score. He handles the highest proportion of calls successfully across all three dimensions — a benchmark worth studying for team training.

**Joe resolves the most calls per interaction (73.5%) but has the lowest satisfaction (3.33) and slowest speed (70.99 secs).** High resolution does not guarantee high satisfaction — how the interaction feels to the customer matters independently of whether the issue gets fixed.

### Satisfaction Distribution

The 3.40 average masks a notably polarised distribution:

| Rating | % of Calls |
|---|---|
| 1 (Very Poor) | 10.3% |
| 2 (Poor) | 9.8% |
| 3 (Average) | **30.0%** |
| 4 (Good) | 29.1% |
| 5 (Excellent) | 20.8% |

20.1% of customers are rating their experience 1 or 2 — that is 1 in 5 calls generating active dissatisfaction. Meanwhile 20.8% rate it 5. The centre is simultaneously delivering both its best and worst experiences at roughly equal rates, with a large neutral block in the middle. A single average score hides this entirely.

---

## Why Is This Happening?

1. **Unanswered calls are structurally persistent** — the rate holds steady regardless of call volume, pointing to a routing or capacity allocation problem rather than demand spikes
2. **Technical Support has the highest miss rate** — customers with the most complex, frustrating issues are the least likely to reach an agent, creating a compounding dissatisfaction effect
3. **Resolution ceiling is systemic** — the near-identical 72–74% resolution rate across all topics and agents suggests agents hit the boundary of what they are empowered or equipped to resolve in a single call
4. **Speed and satisfaction are decoupled** — the near-zero correlation (0.001) means optimising for faster answer times will not improve satisfaction scores, yet it may be a management focus if the data is not analysed this way

---

## What Good Looks Like

- Answer rate above 95% through improved routing and staffing alignment
- Resolution rate above 85% through agent empowerment and knowledge base improvements
- Satisfaction score above 4.0 by addressing the 20% of calls generating ratings of 1–2
- Technical Support miss rate reduced to match Streaming (currently the best at 17.1%)
- Consistent agent performance benchmarks using Dan's profile as the internal standard

---

## What Should Change

**1. Investigate the routing constraint driving persistent unanswered calls**
Since the miss rate is volume-independent, the fix is not adding agents — it is diagnosing whether calls are being lost at queue, routing, or availability level. An IVR audit and queue analysis would isolate the exact point of failure.

**2. Prioritise Technical Support capacity**
21% of technical calls go unanswered — the highest of any topic. Dedicated routing priority or a specialist queue for technical issues would address the highest-risk customer segment first.

**3. Study Dan's approach for team training**
With the highest answer rate (82.6%), highest resolution rate (74.4%), and second-highest satisfaction (3.45), Dan's interaction style and call handling approach are the most replicable internal benchmark available. Structured observation and knowledge transfer is lower-cost than external training.

**4. Reframe performance management away from speed**
The 0.001 correlation between speed of answer and satisfaction means current speed targets — if they exist — are optimising the wrong variable. Shifting focus to resolution quality and interaction tone will move satisfaction scores where speed metrics cannot.

**5. Investigate the 1–2 rating cohort specifically**
20.1% of customers giving a 1 or 2 is a significant dissatisfied segment. Filtering call recordings for this cohort and identifying common failure patterns (topic type, agent, time of day) would surface the specific interactions driving the most damage.

---

## Under the Hood

| Area | Detail |
|---|---|
| Data Source | Excel (.xlsx) — 5,000 rows, 11 columns |
| Analysis | Python (Pandas) — agent benchmarking, topic segmentation, correlation analysis |
| Visualisation | Gauge chart, donut charts, grouped bar chart, agent performance table |
| Interactivity | Agent and topic slicers controlling all visuals simultaneously |
| Operations Context | Call centre KPIs — answer rate, FCR, CSAT, speed of answer, topic routing |

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
