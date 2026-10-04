# Weather Data Processing Pipeline 🌤️📊

A modern, declarative data engine leveraging **Delta Live Tables (DLT)** to ingest, transform, and analyze meteorological and ecological metrics for major Polish cities using the **Medallion Architecture** on Databricks.

---

## 📌 Project Overview

This project provides an automated pipeline for fetching, processing, and aggregating real-time and batch weather and air quality data from the **Open-Meteo API**. It monitors the **7 largest agglomerations in Poland** (Warsaw, Kraków, Gdańsk, Łódź, Poznań, Szczecin, and Wrocław) and processes short-term (24h), medium-term (7 days), and historical time-series metrics.

### Key Metrics Tracked
* **Weather Indicators:** Temperature, wind speed, wind direction, rainfall, latitude & longitude coordinates.
* **Ecological Indicators:** PM10 and PM2.5 particulate matter concentrations.

---

## 🏗️ Architecture & Data Flow

The project utilizes **Delta Live Tables (DLT)** for declarative pipeline execution, automated quality expectations, data testing and data governance.
