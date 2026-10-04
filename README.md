# Weather Data Processing Pipeline 🌤️📊

A dual-mode (Batch & Streaming) data engine designed to ingest, transform, and analyze meteorological and ecological metrics for major Polish cities using the **Medallion Architecture** (Delta Lake) on Databricks.

---

## 📌 Project Overview

This project provides an automated pipeline for fetching, processing, and aggregating real-time and batch weather and air quality data from the **Open-Meteo API**. It monitors the **7 largest agglomerations in Poland** (Warsaw, Kraków, Gdańsk, Łódź, Poznań, Szczecin, and Wrocław) and processes short-term (24h), medium-term (7 days), and historical time-series metrics.

### Key Metrics Tracked
* **Weather Indicators:** Temperature, wind speed, wind direction, rainfall.
* **Ecological Indicators:** PM10 and PM2.5 particulate matter concentrations.

---

## 🏗️ Architecture & Data Flow

The architecture supports both **Streaming** and **Batch** execution modes using Databricks Auto Loader and Delta Lake.
