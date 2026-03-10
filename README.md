# Engineering-Analytics-Data-Platform-for-CAD-PLM-Systems

cad-plm-data-engineering-project 
│
├── datasets
│   ├── cad_metadata
│   │      cad_metadata_2024_01.csv
│   │      cad_metadata_2024_02.csv
│   │
│   ├── bom
│   │      bom_structure.csv
│   │
│   ├── eco
│   │      eco_changes.csv
│   │
│   └── usage_logs
│          cad_usage_logs.json
│
├── adf-pipelines
│   ├── ingest_cad_metadata.json
│   ├── ingest_bom.json
│   └── ingest_eco.json
│
├── databricks-notebooks
│   ├── 01_bronze_ingestion.py
│   ├── 02_silver_transformations.py
│   ├── 03_gold_analytics.py
│
├── architecture
│   └── architecture_diagram.png
│
└── README.md
