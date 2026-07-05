# Hi, I'm Shubham

Data Architect in New York. I build enterprise data platforms and wire them up to AI so non-technical people can actually use the data they're sitting on.

## What I've built

Most of my work lives in private repos, but here's the shape of it:

**Enterprise data warehouse** -- built from zero on Microsoft Fabric. 21+ source systems (CRM, ERP, HRIS, billing, project management) consolidated into a medallion-architecture warehouse serving 400+ users across 8 business units. Config-driven PySpark ingestion, 125 production pipelines, 98.2% success rate. I recruited and led the team of 8 that delivered it.

**AI analytics layer** -- 7 MCP servers (~8,200 lines of Python/TypeScript, 65 tools) that connect Claude to the warehouse. People query data in plain English instead of writing SQL or waiting for someone to pull a report. 8-layer query security, 3-tier observability. This is what surfaced $7.6M in unrealized revenue that leadership didn't know existed.

**AI entity matching** -- cross-system reconciliation between CRM and ERP using deterministic matching + LLM-powered fuzzy matching with human-in-the-loop approval via email. Cut data rejection rates from 25% to 5%.

**LLM pipeline diagnostics** -- an agent that ingests pipeline failure logs, compares them against source code, and outputs a root cause + fix instructions. Cut mean time to resolution from hours to minutes. (The agent caught a specific employee's ID conflict that would've taken a human half a day to trace.)

**AI booking assistant** -- built on the same MCP infrastructure. Matches consultants to projects based on their historical work patterns, expertise, and availability. Natural language in, staffing recommendation out.

**Infrastructure as code** -- 17 Terraform modules, 84 .tf files, 3 environments. Automated workspace provisioning, secrets management, RBAC. Took the team from zero version control to automated gated deployments in 8 weeks.

## What I'm tinkering with

- [InvestFlow](https://github.com/malpanishubham2/investflow) -- investment tracker with AI-driven analysis (Next.js, Gemini, Prisma)
- [fabricpipelines](https://github.com/malpanishubham2/fabricpipelines) -- subset of my PySpark ingestion framework
- Working on open-sourcing a reference MCP server with the 2-tool pattern and security architecture I use in production

## Stack

**Daily:** Python, PySpark, T-SQL, Microsoft Fabric, Azure (DevOps, Key Vault, Entra ID), Terraform, Power BI

**AI/LLM:** MCP servers (FastMCP), Claude integration, LLM-powered entity resolution, agentic diagnostics, prompt engineering for SQL generation

**Also used:** Next.js, TypeScript, React, Power Apps, Power Automate, Logic Apps, PostgreSQL

## Links

[LinkedIn](https://www.linkedin.com/in/malpanishubham/) ·
[Email](mailto:shubham.malpani@gmail.com)
