# Airbnb Paris — Market Analysis & BI Dashboard

> End-to-end business intelligence project analysing 70,000+ Airbnb listings 
> in Paris: from raw data to an interactive Power BI dashboard with geospatial, 
> pricing, host, and review insights.

---

## Project Overview

This university group project covers the full analytics pipeline for the Paris 
Airbnb market — data extraction, cleaning, geospatial enrichment, host clustering, 
dimensional data modelling in Power BI, and an interactive multi-page dashboard.

**Data period:** March 2025 – March 2026  
**Data source:** [Inside Airbnb](https://insideairbnb.com/get-the-data) · 
[Mendeley (POI dataset)](https://data.mendeley.com/datasets/vh4g4g2322/1)

---

## Tech Stack

`Python` · `pandas` · `scikit-learn` · `Power BI` · `Power Query` · `GeoJSON`

---

## Pipeline

### 1. Extract
- `listings.csv` and `calendar.csv` from Inside Airbnb
- Points of interest dataset (nearby attractions) for location-based enrichment
- GeoJSON neighbourhood boundaries for geospatial mapping (Centre / North / South / West / East)

### 2. Transform (`Data Cleaning + Extension.ipynb`)
- Data cleaning & missing value handling
- Feature engineering (amenity counts, price categories, host tenure)
- Host clustering based on revenue and response behaviour
- Geospatial mapping of listings to Paris neighbourhoods
- Proximity analysis to major landmarks (e.g. Eiffel Tower)

### 3. Load & Model (Power BI)
- Star-schema dimensional data model
- Fact tables: listings, calendar availability, reviews
- Dimension tables: hosts, neighbourhoods, amenities, attractions
- Integrated clustered host data (`clustered_hosts_powerbi.csv`)

---

## Dashboard Pages

| Page | Key Metrics |
|------|-------------|
| Market Overview | Availability by month · Avg. price by neighbourhood · Listing distribution |
| Property Overview | Amenity stats · Property types · Instant bookable share |
| Host Overview | Superhost status · Host segments · Verification types |
| Review Overview | Review trends · Hidden gems (rating ≥ 4.9, < 10 reviews) 
<img width="1013" height="570" alt="image" src="https://github.com/user-attachments/assets/0ed438be-9bbd-4d7e-b02b-8efdec8dde91" />
<img width="1008" height="569" alt="image" src="https://github.com/user-attachments/assets/7251e55b-2e26-47f0-aff1-e270434b9592" />
<img width="1014" height="562" alt="image" src="https://github.com/user-attachments/assets/265929f4-ceeb-44c7-9f0f-4f3685f9fbb8" />
<img width="588" height="318" alt="image" src="https://github.com/user-attachments/assets/ffd36036-506d-46ee-bfa4-6577c86525cc" />
<img width="1014" height="562" alt="image" src="https://github.com/user-attachments/assets/d104ccc8-12c3-46d9-ab91-7c5c648734e0" />
Hidden Gems are listings that have received fewer than 10 reviews but already hold an exceptionally high average rating (≥ 4.9). These accommodations are still relatively undiscovered, yet early guest feedback highlights them as high-quality stays, true insider tips worth exploring!  

---

## Key Findings

- Proximity to major landmarks (e.g. Eiffel Tower) has a strong impact on nightly pricing
- Listings rated 5 stars offer the best price-to-performance ratio
- Superhost status correlates with higher occupancy and better review scores
- Average estimated annual revenue per listing: ~$21,000
- Private rooms show high occupancy in the mid-price segment
- Élysée and Louvre have the highest prices but the fewest listings

---

## Repository Structure
Airbnb-Group-Project-Paris/
├── Data Cleaning + Extension.ipynb   # Full Python pipeline
├── clustered_hosts_powerbi.csv        # Host clustering output for Power BI
└── README.md

---

## Data Disclaimer

Data sourced from Inside Airbnb for academic, non-commercial purposes only.  
All contributors have reviewed and approved the publication of this repository.
