---
layout: single
title: "Hi, I'm Jacqueline"
permalink: /
author_profile: true
---

I'm a **Business Intelligence & Data Analyst** in the making: Grande École student at
**emlyon business school**, with a background in economics and econometrics from the
**Magistère d'économie (Paris 1 Panthéon-Sorbonne)**.

I'm currently a **Business Analyst intern at Kenvue** (formerly Johnson & Johnson Consumer
Health), where I build Power BI dashboards and run sales and marketing analyses for the
pharmacy channel.

My approach: **start from a business question → find and clean the right data → turn it into a
clear recommendation.**

## Highlights

- 📊 **4 Power BI dashboards** built end to end, used by **~100 people**
- 🧪 **Campaign cohort analysis** (test vs. control) on **1,500+ pharmacies** for Nicorette and Neutrogena
- ⚡ **AI-assisted automation** that cut control-group creation from **~4 h to ~5 min** per cohort
- 💼 **4 years managing a beauty salon**: KPIs, a team of 5 and client relationships

## Featured projects

{% assign projects = site.projects | sort: "order" %}
{% for post in projects limit: 3 %}
  {% include archive-single.html %}
{% endfor %}

[See all projects]({{ "/projects/" | relative_url }}){: .btn .btn--primary}

## Toolbox

| Area | Tools |
|---|---|
| Business Intelligence | Power BI, Power Query, DAX, KPI design, dashboarding |
| Data | SQL (Snowflake), Excel (TOSA 921/1000), R, ETL, data cleaning |
| Analysis | Cohort analysis, test vs. control, marketing performance, econometrics |
| AI & productivity | Microsoft Copilot, ChatGPT, Claude, Figma, PowerPoint |
