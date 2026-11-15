### Hi, I'm Lu 👋 I make messy data usable for AI.

Economist by training, data engineer by choice. I take the text nobody wants to read (news, filings, reports, in English **and Chinese**) and turn it into tables an analyst can trust and an LLM can query.

```sql
-- whoami.sql
SELECT
  'Lu'                                       AS name,
  'Xinjiang → Basel'                             AS route,
  'M.Sc. Business & Technology, Uni Basel'       AS studying,     -- class of 2027
  'economics → BI → data engineering → LLMs'     AS path,
  ARRAY('English', 'Deutsch (B2)', '中文')        AS languages,
  'Data × AI roles in Switzerland & Germany'     AS looking_for
FROM   me
WHERE  ai_answers_are_grounded = TRUE;
```

### Built so far

- 🤖 **[Humanoid Robotics Market Intelligence](https://github.com/FelixFelicis7/Humanoid-Robotics-Market-Intelligence-Pipeline)**: an LLM reads EN + 中文 robotics news and writes funding rounds, partnerships and production plans into a star schema. Every row keeps the sentence it came from. Ask it in plain English through Genie Text-to-SQL or a RAG app.
- 📄 **[RAG-APP](https://github.com/FelixFelicis7/RAG-APP)**: document Q&A where ingestion and answering run as event-driven Inngest workflows, and every answer cites its sources.
- 🏗️ **[Sales Data Warehouse](https://github.com/FelixFelicis7/Sales-Data-Warehouse)** → **[on Databricks](https://github.com/FelixFelicis7/databricks-medallion-pipeline)**: one ERP + CRM warehouse, built twice: SQL Server first, then Delta Lake & Unity Catalog.
- 💼 **AUMOVIO, data analyst intern (2026)**: automated a data collection & validation workflow with AI and scripting. The reporting cycle went from **5 days to 3**.

<details>
<summary>Earlier analytics work</summary>

[Tableau sales dashboards](https://github.com/FelixFelicis7/Sales-Profit-Performance-Across-US-Regions) · [Churn & CLV analysis](https://github.com/FelixFelicis7/Churn-and-Customer-Lifetime-Value-CLV-Analysis-for-Fintech-Advisory-Product) · [SQL sales analytics](https://github.com/FelixFelicis7/Sales-Data-Analytics) · [Weather vs. Swiss train delays](https://github.com/FelixFelicis7/-Weather-Impact-on-Public-Transport-Delays-in-Switzerland)
</details>

🌱 **Now:** adding dbt tests, CI and an eval set to the robotics pipeline, so the LLM's extraction gets measured, not just trusted.

📫 [LinkedIn](https://www.linkedin.com/in/christinaluliu/)
