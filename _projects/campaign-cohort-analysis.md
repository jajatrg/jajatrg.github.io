---
title: "Measuring in-pharmacy campaign impact with cohorts"
excerpt: "Test vs. control cohort analysis of 2026 Nicorette and Neutrogena campaigns across 1,500+ pharmacies, with an AI-assisted workflow that cut control-group creation from ~4 h to ~5 min."
order: 1
context: "Kenvue · Business Analyst internship"
tools: [SQL (Snowflake), Excel, Power BI, Microsoft Copilot]
---

**Context:** Kenvue (formerly J&J Consumer Health), pharmacy channel · 2026

**Tools:** SQL (Snowflake), Excel, Power BI, Microsoft Copilot

Visuals will be added once the data has been anonymised.
{: .notice--info}

## Business question

Kenvue runs in-store campaigns in pharmacies for brands such as **Nicorette** and **Neutrogena**,
using different promotional mechanisms. The question was simple: **which of them actually drive
extra sales, and which are not worth their cost?**

## Approach

- Built **test groups** (pharmacies that ran a campaign) and **comparable control groups**
  (similar pharmacies that did not) for each campaign, covering **1,500+ pharmacies**.
- Compared sales before and after the campaign in both groups, so that seasonality and market
  trends were not mistaken for campaign impact.
- Compared promotional levers to each other in terms of uplift and return on investment.

## Automating the control groups with AI

Building a good control group for each cohort was manual and took **about 4 hours**.
I used **Microsoft Copilot** to automate the matching logic, then checked every output by hand.
Result: **~5 minutes per cohort**, which made it possible to analyse many more campaigns.

## Limitations I identified

Looking at pharmacy location data (GERS), I noticed that pharmacies **located very close to a
test pharmacy (~100 m)** were also affected by the campaign. This spillover effect can make
neighbouring "control" pharmacies look better than they should, so the measured uplift is likely
**underestimated**. I flagged it and took it into account when presenting the results.

## Outcome

- Identified **the most effective promotional lever** and shared the recommendation with the teams.
- A repeatable method that can be reused for future campaigns.

## What I learned

- A test vs. control design is only as good as its control group.
- Always question the method: the most interesting insight was a limitation.
- AI saves time only if the output is checked.
