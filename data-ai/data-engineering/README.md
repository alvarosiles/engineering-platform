# Data Engineering

Pipelines de ingesta, transformación y almacenamiento de datos.

## Ejemplo de pipeline

```
Fuentes (APIs, DB, eventos)
        │
   Ingesta (batch/streaming)
        │
  Transformación (ETL/ELT)
        │
   Data Warehouse
```

## Stack propuesto

- Python, Apache Airflow para orquestación.
- Data warehouse: BigQuery / Redshift / Snowflake.

> Placeholder de ejemplo. Los pipelines reales se agregarán conforme se definan las fuentes de datos.
