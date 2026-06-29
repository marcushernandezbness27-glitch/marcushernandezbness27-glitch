# Marcus Hernandez

I build automation and data systems — ETL pipelines, commission engines, AI-assisted workflows — for businesses that have outgrown spreadsheets and manual processes.

My background is in sales operations, which means I understand the problem before the code: what a broken commission run costs at the end of the month, why a CRM sync that silently drops cancellations is worse than one that fails loudly, and what a non-technical stakeholder actually needs from a dashboard. I moved to the engineering side because I kept being the person who knew what to build but had to ask someone else to build it.

Available for Upwork engagements focused on automation, data pipelines, and backend integrations.

---

## Projects

### [stellapura-payroll](https://github.com/marcushernandezbness27-glitch/stellapura-payroll-public)
Real-money weekly commission payroll running entirely on Cloudflare's edge (Workers + D1 + Durable Objects). Highlights: CAS-based double-disbursement prevention, change-detection diff for automatic cancellation clawbacks, declarative rate-table engine (no `eval` — platform-disabled), BigQuery analytics via Workload Identity Federation.  
`TypeScript` `Cloudflare Workers` `D1` `Hono` `Durable Objects` `BigQuery` `ADP WorkMarket`

### [salon-freedom-pipeline](https://github.com/marcushernandezbness27-glitch/salon-freedom-pipeline)
Multi-source social + survey data pipeline feeding a GPT-4.1-mini analysis stage that clusters pain points, scores buying signals, and generates ranked offer concepts as a DOCX report. Includes two production bug writeups (silent data-loss fix, hardcoded placeholder replaced with real computation).  
`Python` `Meta Graph API` `Mailchimp API` `OpenAI` `pandas` `pydantic` `pytest`

### [Invoice Automation — Airtable + OpenAI + Google Docs](https://us2.make.com/public/shared-scenario/5F6FR14Ou8m/ai-powered-invoice-automation)
New service request in Airtable triggers Make.com to call OpenAI, generate a professional invoice, create a Google Doc, email it to the client, and write the doc link back — full loop, zero manual steps.  
`Make.com` `Airtable` `OpenAI API` `Google Docs` `Gmail`

### [Power BI Dashboards](https://github.com/marcushernandezbness27-glitch/powerbi-dashboards-public)
Three operational dashboards: restaurant ops (covers, COGS%, labor%, table turns), marketing funnel, and SaaS payroll metrics. Built in Power BI Desktop with DAX measures and synthetic datasets.  
`Power BI` `DAX` `Power Query` `Looker Studio`

---

## Stack

**Languages:** TypeScript · Python  
**Edge / Cloud:** Cloudflare Workers · D1 · KV · Durable Objects · Cron Triggers · BigQuery (GCP)  
**APIs & integrations:** Meta Graph API · Mailchimp · OpenAI · ADP WorkMarket · Resend  
**Data:** pandas · pydantic · SQLite · ETL pipeline design  
**Automation:** Make.com · GHL · Airtable  
**Testing:** Vitest · pytest · requests-mock
