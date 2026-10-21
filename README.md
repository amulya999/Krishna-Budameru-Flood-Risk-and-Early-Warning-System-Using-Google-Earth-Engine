# Krishna-Budameru-Flood-Risk-and-Early-Warning-System-Using-Google-Earth-Engine
GIS and remote-sensing based flood-risk mapping and early-warning prototype for the Krishna–Budameru basin, Vijayawada, Andhra Pradesh.
krishna-budameru-flood-risk-ews/
│
├── README.md
├── LICENSE
├── requirements.txt
├── environment.yml
├── .gitignore
│
├── data/
│   ├── raw/                  # Original downloaded data
│   ├── interim/              # Cleaned/processed intermediate files
│   ├── processed/            # Final analysis-ready rasters/vectors
│   └── external/             # Boundaries, roads, DEM, rainfall, etc.
│
├── notebooks/
│   ├── 01_data_download.ipynb
│   ├── 02_dem_preprocessing.ipynb
│   ├── 03_landcover_ndvi_analysis.ipynb
│   ├── 04_sar_flood_mapping.ipynb
│   ├── 05_flood_hazard_model.ipynb
│   ├── 06_exposure_vulnerability_risk.ipynb
│   └── 07_early_warning_dashboard.ipynb
│
├── src/
│   ├── __init__.py
│   ├── config.py
│   ├── data_utils.py
│   ├── raster_utils.py
│   ├── vector_utils.py
│   ├── flood_mapping.py
│   ├── risk_analysis.py
│   └── alerting.py
│
├── scripts/
│   ├── download_sentinel1.py
│   ├── preprocess_dem.py
│   ├── calculate_ndwi.py
│   ├── generate_flood_mask.py
│   ├── build_risk_map.py
│   └── send_alert_demo.py
│
├── outputs/
│   ├── figures/
│   ├── maps/
│   └── reports/
│
├── dashboard/
│   ├── app.py
│   ├── assets/
│   └── requirements.txt
│
└── docs/
    ├── methodology.md
    ├── data_sources.md
    ├── project_report_outline.md
    └── images/
