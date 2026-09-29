# Market-Intelligence-Analysis
Sprint 3: Market Data to Market Intelligence

A spatial analysis project that transforms land-market data into indicative market intelligence for selected towns in Lagos State.

Project Overview

This project uses Python and spatial analysis to clean, summarize, compare, and visualize land prices across five towns:

Isheri-Olofin
Ikotun
Igando
Egan
Abaranje / Okerube

The analysis produces both a market-level comparison and a spatial market map.

Indicative Market Levels
Town	Price (₦/sqm)
Isheri-Olofin	₦196,000
Ikotun	₦140,000
Igando	₦85,380
Egan	₦75,000
Abaranje / Okerube	₦60,600

These are indicative asking-price signals based on the collected listings, not formal property valuations.

Outputs

Bar Chart
Compares indicative land-market levels across the five towns.

Spatial Map
Shows the towns coloured according to their indicative market levels.

Workflow
Market Data
     ↓
Data Cleaning
     ↓
Market-Level Calculation
     ↓
Comparison & Visualization
     ↓
Spatial Mapping
     ↓
Market Intelligence
Tools
Python
Pandas
GeoPandas
Matplotlib
Folium
Mapclassify
NumPy
Repository Structure
├── sprint3_market_data_to_market_intelligence.ipynb
├── market_intelligence.csv
├── market_intelligence.json
├── market_levels_bar.png
├── towns_market_map.png
└── README.md
Limitation

The current dataset contains one market observation per town. Therefore, the results should be interpreted as indicative market signals rather than comprehensive market estimates.

Project Context

Developed as part of the GeoRAD Emerging Spatial Professionals Mentorship Program – Sprint 3.
