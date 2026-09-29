# Disaster Shield

This is an AI-based disaster monitoring and thermal classification system which tries to detect and classify potential industrial fires and persistent thermal sources using various satellite and geospatial data sources.

It utilizes the thermal anomaly data provided by NASA FIRMS, infrastructure data from OpenStreetMap(OSM), land cover data from Sentinel 2, and thermal and surface analysis from Landsat 8/9 and uses Machine Learning models to classify the possible causes of these thermal anomalies based on contextual information and tries to learn patterns from past events.

# Features

-Near real-time thermal anomaly detection with FIRMS (NASA)
-Detect industrial and infrastructural objects with OSM
-Detect land cover with Sentine-2
-Surface and thermal analysis with Landsat 8/9
-AI/ML Based thermal source classification
-Pattern analysis of past events
-AI Confidence Scoring to avoid false positives

# Tech Stack
Frontend: React + Leaflet
Backend: Python + FastAPI
DB: Postgres + PostGIS
ML: Random Forest + XGBoost
Processing: Joblib/Pickle
Deployment: Docker + AWS
# Data

NASA FIRMS
OpenStreetMap
Copernicus Sentinel-2
USGS Landsat 8/9

# Objective

While most thermal monitoring systems are capable of detecting potential hotspots, the challenge is to identify the possible source of the detected hotspot. By utilizing multiple satellite data sources along with geospatial data and using pattern recognition algorithms, this project tries to classify the possible sources of the heat anomaly to help with quicker and more accurate disaster response and management.
