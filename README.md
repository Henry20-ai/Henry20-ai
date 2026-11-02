# Henry Isaac: BI and data engineering

I'm a business analyst moving into data engineering. For three years I wrote requirements and built dashboards for other people's teams. Now I'm building the pipelines underneath them: pull data from an API, load it into a warehouse, test it, and model it so a report can be trusted.

I'm early on the engineering side. Python is my favorite tool and yes am still growing and deepening my expertise in the stack.

## What I've built

- [RWA data pipeline](https://github.com/Henry20-ai/end-to-end-RWA-data-pipeline-Python-Parquet-BigQuery-dbt-): Python pulls real-world-asset token data from the CoinGecko API, saves it as Parquet, and loads it into BigQuery. dbt builds the staging and mart models, with tests for unique and not-null token IDs.
- [Ops SLA warehouse](https://github.com/Henry20-ai/ops-sla-warehouse): 300 synthetic support tickets go into PostgreSQL, Great Expectations checks them, and dbt models SLA breaches by priority. All 8 dbt tests pass. On the fake data, Medium tickets breached SLA more often (45.5%) than Urgent ones (13.9%), because they get pushed behind urgent work. My first data generator gave silly numbers (97.8% breaches for Urgent), so I rebuilt it before modelling anything.
- [Marketing Ops Dashboard](https://github.com/Henry20-ai/Marketing-Ops-Dashboard): SQL and Power BI across 44 campaigns. Email returned about 8x the ROI of paid social ($17 vs $213 per acquisition).
- [AI Lead Gen System](https://github.com/Henry20-ai/AI-Lead-Gen-System): an n8n workflow using the Claude API. It brought cost per lead from about $50 to $5 across 500+ contacts.

## Tools

SQL (PostgreSQL, BigQuery, Snowflake), dbt, Python (pandas, numpy, request, pyarrow), Great Expectations, Power BI, Excel, n8n, HubSpot, Git.

Learning now: Fastapi & pydantic for data engineering, then Airflow, docker,Bash Scripting, AWS.

Certifications: DataCamp Data Engineer Associate, Google Business Intelligence Professional Certificate, Google Cloud Data Analytics Professional Certificate.

## Background

Three years as a business analyst and operations lead, working remotely with teams in the UK, Canada and Ukraine. At NOVA Marketing Agency I cut client onboarding from 5 days to 3 and manual reporting time by 40%. That's why I write requirements before I write queries.

## Looking for

Fulltime & short contracts in BI or Internships/Contracts in data engineering. Remote.

## Contact

- [LinkedIn](https://www.linkedin.com/in/henry-isaac-udochukwu-b866421b1)
- [Book Intro](https://calendly.com/henryisaccudo5000/book-a-15min-intro?month=2026-11)
- Email: Henryisaccudo5000@gmail.com
