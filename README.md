# Data Platform Portfolio (Healthcare + Finance Patterns)

This portfolio demonstrates production-style data engineering and analytics patterns:
- **audit-ready reporting**
- **data quality gates**
- **reconciliation / tie-outs**
- **KPI & SLA monitoring**
- **repeatable ETL factory**
- **churn modeling + causal analysis**

All projects use **synthetic/mock data** so the repos are safe and shareable.

## Projects
1) **Audit-Ready Regulatory Reporting Pipeline**  
   `projects/01_audit_ready_reg_reporting`

2) **KPI + SLA Monitoring Suite**  
   `projects/02_kpi_sla_monitoring`

3) **Reconciliation Engine (Cross-Source Tie-Outs)**  
   `projects/03_reconciliation_engine`

4) **PySpark ETL Factory (Config-driven pipelines + CI)**  
   `projects/04_pyspark_etl_factory`

5) **Churn + Causal Analysis (ML + explainability)**  
   `projects/05_churn_and_causal_analysis`

## How to run (common)
Most projects follow:
```bash
python -m venv .venv
source .venv/bin/activate   # mac/linux
# .venv\Scripts\activate    # windows
pip install -r requirements.txt
