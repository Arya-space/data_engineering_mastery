# Data Engineering Mastery

Interactive study notes for data engineering interviews — built as GitHub Pages.

---

## Interactive Study Pages

### Core Topics

| Module | Topics Covered | Link |
|--------|---------------|------|
| Data Architecture | Pipeline layers, ETL/ELT, ingestion patterns, Medallion/Lambda/Kappa/Mesh, storage, transform, AI layer, orchestration, governance, security, cost, tools | [View](https://arya-space.github.io/data_engineering_mastery/Data_Engineer_Topic/data_architure.html) |
| Architecture Designer | 6-question wizard + rules engine that recommends your stack (tools, cloud services, diagram) | [View](https://arya-space.github.io/data_engineering_mastery/Data_Engineer_Topic/arch_designer.html) |
| Data Modelling | OLTP vs OLAP, normalization, grain, schema types, fact table types, dimension types, dbt conventions, interactive schema designer | [View](https://arya-space.github.io/data_engineering_mastery/Data_Engineer_Topic/datamodelling.html) |
| Slowly Changing Dimensions | SCD Type 1 / 2 / 3 / 4 / 6 with interactive walkthroughs | [View](https://arya-space.github.io/data_engineering_mastery/Data_Engineer_Topic/SCD.html) |
| Streaming | Kafka internals, delivery semantics, windowing, watermarks, state management, Flink vs Spark, event-driven architecture, interview prep | [View](https://arya-space.github.io/data_engineering_mastery/Data_Engineer_Topic/streaming.html) |

---

## Folder Structure

```
data_engineering_mastery/
├── Data_Engineer_Topic/          # Main interactive HTML study pages
│   ├── data_architure.html       # Data architecture (all layers, patterns, tools)
│   ├── arch_designer.html        # Architecture designer wizard
│   ├── datamodelling.html        # Data modelling fundamentals + dbt
│   ├── SCD.html                  # Slowly Changing Dimensions
│   └── streaming.html            # Streaming internals (Kafka, Flink, EDA)
│
├── Modern_Data_Modelling_Data_warehouse/  # Kimball vs Inmon, dimensional modelling notes
│
├── excaildraws/                  # Data modelling interview case studies (Excalidraw + SVG)
│   └── Q1 — Library Management System
│
└── Big_Data_Lab/                 # Lab exercises
```

---

## What to Study and In What Order

1. **Data Architecture** — understand the full picture first
2. **Data Modelling** — fact/dim tables, normalization, dbt
3. **SCD** — slowly changing dimensions (type 1/2/3/6)
4. **Streaming** — Kafka, Flink, delivery semantics
5. **Architecture Designer** — test yourself by designing a stack from scratch
6. **excaildraws/** — practice with real interview case studies
