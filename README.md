<div align="center">

<img src="https://raw.githubusercontent.com/kartikeyamandhar/kartikeyamandhar/main/assets/header.svg" alt="Kartikeya Mandhar — AI/LLM Engineer & Data Scientist. Systems that refuse to be confidently wrong." width="850" />

[![Portfolio](https://img.shields.io/badge/Portfolio-kmandhar.com-B22119?style=flat-square&logo=vercel&logoColor=white)](https://kmandhar.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartikeyamandhar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kmandhar@g.ucla.edu)
[![Medium](https://img.shields.io/badge/Blog-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@kartikeya.mandhar511)

</div>

---

I build systems that **retrieve, reason, and rank** — agentic, retrieval, and evaluation systems, plus the applied-ML and full-stack products around them. 4+ years across production data, ML, and applied AI.

<div align="center">

<img src="https://raw.githubusercontent.com/kartikeyamandhar/kartikeyamandhar/main/assets/systems.svg" alt="How I build reliable AI systems: ingest, hybrid retrieval, reason, verify (span citations, refusal gates, deterministic scoring), ship behind a golden-set deploy gate." width="850" />

</div>

### Featured Work

| Project | Stack | What it does |
|:--|:--|:--|
| **[Autonomous Impact Analyst](https://github.com/kartikeyamandhar/autonomous-impact-analyst)** | LangGraph · Claude · Neo4j · sqlglot · dbt | A LangGraph agent that traces a warehouse change through a 451-node column-level lineage graph, scores blast-radius risk with a deterministic formula, and opens a `sqlglot`-validated fix PR. The LLM only writes the summary. |
| **[SEC RAG](https://github.com/kartikeyamandhar/airflow_sec_rag)** | FastAPI · Qdrant · BM25 · XBRL · Claude · MCP | Grounded SEC-filings answer engine that enforces span citations *in code*, refuses on weak retrieval, pulls figures from structured XBRL, and gates releases on a golden set. 106 tests, deps faked behind protocols. |
| **[LedgerBench](https://github.com/kartikeyamandhar/ledgerbench)** | DuckDB · sqlglot · dbt · Anthropic · OpenAI | Open-source benchmark showing analytics agents run SQL 100% cleanly yet are business-correct on only 9–59% of answers. Every number traced to a committed run manifest. |
| **[sliceval](https://github.com/kartikeyamandhar/sliceval)** | scikit-learn · PyPI | Published `pip install sliceval` library that finds underperforming data subgroups with bootstrap confidence intervals and permutation significance tests. 162 tests across 13 model types. |
| **[Neo4j GraphRAG → Apache Hamilton](https://github.com/apache/hamilton/pull/1532)** | Apache Hamilton · Neo4j | A 4-module GraphRAG pipeline (ingest → embed → retrieve → generate) contributed and **merged upstream** as apache/hamilton **PR #1532**. |
| **[Cover Drive](https://github.com/kartikeyamandhar/cover-drive)** | PyTorch · QLoRA · Unsloth · FastAPI · Next.js | A fine-tuned Qwen2.5-1.5B (QLoRA) engineered so it cannot state a wrong fact: deterministic fact-fill plus validate-or-fallback serving. 190 tests. |

🚧 **Now building — MAIRS:** a multi-agent investment-research layer over the SEC grounding engine.

More work, and an "Ask the Projectionist" AI guide, at **[kmandhar.com](https://kmandhar.com)**.

---

### Tech Stack

<table>
<tr>
<td><b>Languages &amp; Compute</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
<img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/Dagster-654FF0?style=flat-square&logo=dagster&logoColor=white" />
</td>
</tr>
<tr>
<td><b>ML &amp; LLM</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LlamaIndex-6B4FBB?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Data &amp; Databases</b></td>
<td>
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" />
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
</td>
</tr>
<tr>
<td><b>Cloud &amp; Serving</b></td>
<td>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
</td>
</tr>
</table>

### Certifications

**AWS** Machine Learning – Specialty &nbsp;·&nbsp; **Azure** Data Engineer Associate (DP-203) &nbsp;·&nbsp; **Azure** AI Engineer Associate

<div align="center">

*Building things that retrieve, reason, and rank. If that overlaps with what you're building, reach out.*

</div>
