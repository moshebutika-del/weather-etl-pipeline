# weather-etl-pipeline

Automated ETL pipeline for aggregating and storing daily weather station data across multiple regions.

Fetches raw meteorological readings (temperature, humidity, pressure, wind) from public APIs,
normalizes them into a unified schema, and uploads Parquet snapshots to a data lake every few hours.

## Features
- Multi-source ingestion
- Parquet output with zstd compression
- Scheduled via GitHub Actions
- Zero infrastructure cost
