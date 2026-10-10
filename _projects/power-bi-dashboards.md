---
title: "Power BI dashboards from scratch"
excerpt: "Four Power BI dashboards designed and built end to end (SQL on Snowflake, Power Query, DAX), used by around 100 people, including a performance dashboard for key account managers."
order: 2
context: "Kenvue · Business Analyst internship"
tools: [Power BI, DAX, Power Query, SQL (Snowflake), Excel]
---

**Context:** Kenvue, pharmacy and FMCG channels · 2026

**Tools:** Power BI, DAX, Power Query, SQL (Snowflake), Excel

Screenshots will be added once the data has been anonymised.
{: .notice--info}

## What I built

**4 dashboards built end to end**, from data extraction to the final report, used by **~100 people**.

- **Parapharmacy performance dashboard** for key account managers (KAM) and the external sales
  network, with **5+ KPIs**: evolution, year-to-date (YTD), numeric distribution (DN)…
- **FMCG (grande consommation) dashboard** for Le Petit Marseillais, which gave me experience
  beyond the pharmacy channel.
- Other sales follow-up dashboards that replaced manual Excel reporting.

## How

- **SQL on Snowflake** to extract and transform the data (`JOIN`, `CASE`, `GROUP BY`, `WHERE`).
- **Power Query** to clean and shape it, and **DAX** for the measures (YTD, year-over-year…).
- Automated refresh so the reports stay up to date without manual work.

## A data quality issue I solved

The Power BI figures did not match an existing Excel report. After investigating, I found that
some **customer codes were linked to the wrong retail group** in the targeting table. Once the
mapping was fixed, both sources matched again.

## Sharing the knowledge

During my first weeks, I also **trained other interns on Power BI**.

## What I learned

- A dashboard is only useful if people use it: start from the users' questions.
- Always reconcile new figures with an existing source before publishing.
