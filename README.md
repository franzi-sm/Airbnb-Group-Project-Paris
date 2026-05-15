# Airbnb-Group-Project-Paris
This university group project focuses on the analysis of Airbnb listings in Paris using business intelligence and analytics techniques.

The project includes data extraction, cleaning, and enrichment in Python, followed by geospatial analysis and clustering of host and listing characteristics. The processed data was then integrated into a dimensional data model in Microsoft Power BI using Power Query and finalized through an interactive dashboard and visualization layer.

Business Case

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/00241dec-1929-4449-afed-b845e04d7e49" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/823cb5fa-7f65-47a5-9f3a-2caa03d0a303" />

Process Steps
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/117de222-4c47-4a06-bd19-2bac645eb871" />

Extract Transform Load (Transform) Process
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/d1de843d-a48d-4fb0-b8dd-69fa5224b374" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/17e41cfd-1e0b-418a-8e8b-cfe5449b47cd" />

Extract

The extraction process focused on collecting Airbnb listing and availability data for Paris from publicly available sources. The primary datasets, listings.csv and calendar.csv, were extracted from Inside Airbnb and contain detailed information on property characteristics, host information, pricing, reviews, and daily availability.

In addition, a dataset containing nearby attractions and points of interest was integrated to enrich the analytical potential of the project. This supplementary dataset supports location-based analysis and provides further context for understanding Airbnb market dynamics and tourist activity patterns.

The extracted data covers the period from March 2025 to mid-March 2026.

Data Sources

* Source: https://insideairbnb.com/get-the-data
* Source: https://data.mendeley.com/datasets/vh4g4g2322/1

Transform

The Python script focuses on the first transformation step of the data by cleaning and extending it for analysis. The workflow includes preprocessing listings.csv, integrating neighbourhood GeoJSON data for geospatial mapping (Centre/North/South/West/East), handling missing values, and creating additional features to improve data quality and usability.

Further steps include host clustering, cleaning and transforming calendar.csv, exploring pricing patterns, enriching the dataset with nearby attractions, and analyzing amenity counts to identify additional insights into Airbnb listings and market dynamics.


Data Modelling

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/892ba10a-6452-4577-ae88-8057d3d5261c" />

The data model was designed in Power BI using a relational star-schema approach to create a scalable structure for analysis. Multiple fact and dimension tables were connected, including listings, calendar availability, reviews, host information, neighbourhood data, amenities, and nearby attractions.

The focus was placed on data normalization, relationship management, and the integration of geospatial and clustering data. The model supports interactive reporting, pricing analysis, host segmentation, and availability.

Power BI Dashboard

A comprehensive walkthrough video of the Power BI dashboard is currently in progress. The current screenshots and descriptions serve as temporary placeholders until the final showcase is completed.

Market Overview
<img width="1013" height="570" alt="image" src="https://github.com/user-attachments/assets/0ed438be-9bbd-4d7e-b02b-8efdec8dde91" />
* Availability by Month
* Average Price by Neighborhoods
* Distribution Across Neighborhoods

Property Overview
<img width="1008" height="569" alt="image" src="https://github.com/user-attachments/assets/7251e55b-2e26-47f0-aff1-e270434b9592" />
* Amenities Statistics & Property Type
* Instant Bookable / Short-Term Share

Host Overview
<img width="1014" height="562" alt="image" src="https://github.com/user-attachments/assets/265929f4-ceeb-44c7-9f0f-4f3685f9fbb8" />
<img width="588" height="318" alt="image" src="https://github.com/user-attachments/assets/ffd36036-506d-46ee-bfa4-6577c86525cc" />
* Verification Types
* Superhost Status & Host Categories based on Revenue and Response Behavior

Review Overview
<img width="1014" height="562" alt="image" src="https://github.com/user-attachments/assets/d104ccc8-12c3-46d9-ab91-7c5c648734e0" />
Hidden Gems are listings that have received fewer than 10 reviews but already hold an exceptionally high average rating (≥ 4.9). These accommodations are still relatively undiscovered, yet early guest feedback highlights them as high-quality stays, true insider tips worth exploring!  

* Review Analysis
* Strengthening Customer Satisfaction & Loyalty
* Identifying Hidden Gems

Key Takeaways
* Proximity to major landmarks, such as the Eiffel Tower, has a strong impact on pricing.
* Listings with 5-star ratings offer the best price-performance ratio.
* Superhost status is associated with better reviews and higher occupancy rates.
* On average, each listing generates approximately $21k in annual revenue.
* Private rooms show high occupancy rates within the mid-price segment.
* The Élysée and Louvre neighborhoods have the highest prices while also having some of the fewest listings.

Data Disclaimer

This project uses publicly available data provided by Inside Airbnb.  
The dataset includes information covering the period from March 1, 2025 to March 15, 2026.
Data was accessed and used for academic and non-commercial purposes only.

Approval & Contribution Statement

All contributors and collaborators involved in this project have reviewed and approved the publication of this repository and its contents on GitHub.
