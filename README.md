# ISRO-BAH2026: AI-Driven Air Quality Forecasting

## Overview
A research-oriented project for the ISRO Hackathon 2026, utilizing JAX-based Transformers and 1D Diffusion models to predict PM2.5 levels and identify pollution hotspots across the Indo-Gangetic Plain.

## Features
- **Data Ingestion**: Dynamic extraction from Google Earth Engine (S5P, MODIS MAIAC, ERA5).
- **AI Models**: SpatioTemporal Transformer for regression and Conditional Diffusion 1D for denoising predictions.
- **Diagnostics**: DBSCAN-based hotspot detection and automated dashboard generation.

## Installation
```bash
pip install -r requirements.txt
