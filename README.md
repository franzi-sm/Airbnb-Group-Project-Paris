# Airbnb-Group-Project-Paris
This university group project focused on a business case for Airbnb listings in Paris. During the project, the scope shifted toward the pricing data that was available at the time, as newer datasets from Inside Airbnb no longer include this information.

The project started with data cleaning and enrichment in Python, followed by geographical mapping, clustering of host characteristics and listing features. Afterwards, the data model was developed in Microsoft Power BI using Power Query and completed with an interactive visualization layer. The project was later further refined with a stronger focus on the pricing component and pricing-related insights.

Business Case

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/00241dec-1929-4449-afed-b845e04d7e49" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/823cb5fa-7f65-47a5-9f3a-2caa03d0a303" />

Process Steps
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/117de222-4c47-4a06-bd19-2bac645eb871" />

Extract Transform Load (Transform) Process:
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

* Dashbaord zeigen - Video einfügen*

* Key Takeaways / Recommendations *

* Improvements *

Data Disclaimer

This project uses publicly available data provided by Inside Airbnb.  
The dataset includes information covering the period from March 1, 2025 to March 15, 2026.
Data was accessed and used for academic and non-commercial purposes only.

Approval & Contribution Statement

All contributors and collaborators involved in this project have reviewed and approved the publication of this repository and its contents on GitHub.
