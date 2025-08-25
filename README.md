# AI-Driven Content Performance (Case Study Deck)
**An operator-grade, Azure-AI workflow for turning content sprawl into CMO-ready insights.**

<p align="center">
  <!-- If you keep the current filename, keep the first link; if you rename to a clean slug, use the second link -->
  <a href="https://github.com/Mo-Awad-AI/AI-Driven-Content-Performance/blob/cab7bcf12bceb2af5ca2943bb4ea7cbd98453eff/Mo%20Awad_%20AI-Driven%20Content%20Performance%20.pdf">📄 View the PDF</a> • 
</p>

---

## Why this exists
CMOs need fast, actionable readouts across many content channels. Manual reporting is slow, inconsistent, and siloed. This deck shows how **AgentC** automates the pipeline end-to-end with Azure AI—so insights (and next steps) arrive on time, every time.

## Who it’s for
- **Marketing leaders / CMOs** who need one source of truth and a monthly executive summary
- **Content & Growth teams** aligning production with what actually converts
- **Data/RevOps** teams standardizing taxonomy, KPIs, and delivery

## What’s inside
1) **Executive Summary** — the “what, why, next” in one slide  
2) **Workflow Overview** — ingestion → tagging → KPI rollups → anomalies → exec recs → automated delivery  
3) **Data Ingestion & Normalization** — Azure Data Factory / AI Foundry; single source of truth  
4) **Classification & Tagging** — Azure Cognitive Services (Text Analytics, Entities, custom NLP) for channel/format/topic taxonomy  
5) **Performance Patterns** — rollups showing top formats/topics/channels (eBooks, guides, webinars; CX/Workplace/Phone)  
6) **Anomaly & Trend Detection** — Azure ML time-series to catch spikes/drops and outliers early  
7) **Strategic Insights** — Azure OpenAI (GPT-4) converts KPIs into C-suite takeaways and next steps  
8) **Automated Delivery & Dashboards** — Logic Apps / Power Automate / Power BI for monthly snapshots & live views

> Key takeaway: double-down on high-intent formats & topics; fix data hygiene; respond quickly to outliers with playbooks.

## Architecture at a glance
- **Ingest:** Azure Data Factory / AI Foundry → unified content DB  
- **Enrich:** Azure Cognitive Services (Text Analytics, Entity Recognition) → standardized tags (channel, format, topic, language)  
- **Analyze:** Azure ML aggregations + anomaly detection → KPI rollups, outlier surfacing  
- **Narrate:** Azure OpenAI (GPT-4) → concise exec summary (“What happened, Why it matters, What to do next”)  
- **Deliver:** Logic Apps / Power Automate + Power BI → automated monthly report + dashboards

## How to reuse this deck
- **Adopt the taxonomy:** standardize format/topic/channel tags in your CMS and data warehouse  
- **Instrument KPIs:** views, engagement, conversions, lead quality, assisted revenue  
- **Schedule anomaly reviews:** monthly triage of high/low outliers; replicate winners, fix losers  
- **Close the loop:** share executive highlights, assign owners, and track changes in Power BI

## Credits & Contact
Authored by **Mo Awad** — AI-obsessed marketer & growth leader.  
Questions or collaboration: **mowadmarketer@gmail.com**

[![Built by Mo Awad](https://img.shields.io/badge/Built%20by-Mo%20Awad-0A66C2?style=for-the-badge&logo=github)](https://github.com/mo-awad-ai)

