# canterbury-nzdep-spatial-analysis
Spatial analysis of deprivation in Christchrch using NZDep2023, meshblock data and Christchurch Transport data.

# Topic: Spatial Analysis of Deprivation and Public Transport Accessibility in Christchurch

This project explores the relationship between area-level deprivation (using NZDep2023 and meshblock data SA1) and public transport accessibility in the Christchurch city. 

## Key Features 
Data Integration: Combines NZDep2023/IMD deprivation scores with meshblock boundaries and open public transport data (bus stops, routes).

Advanced Spatial Analysis: Calculates accessibility metrics (e.g., distance to nearest bus stop, number of stops/routes within walking distance) for each meshblock or SA1.

Predictive & Clustering Models: Uses spatial regression, geographically weighted regression (GWR), and spatial clustering (e.g., DBSCAN) to identify patterns and predictors of deprivation linked to transport access.

Policy Relevance: Highlights priority areas for transport intervention and supports evidence-based urban and social planning in Canterbury.

## Data Sources 

- NZDep2023 Index
Socioeconomic deprivation scores by SA1, provided by the University of Otago.

- Bus Stop (OpenData)
Locations of all public bus stops in Christchurch, provided by Christchurch City Council.
Bus Stop (OpenData)

- Cycleway (OpenData)
Spatial data of dedicated cycleway routes in Christchurch, provided by Christchurch City Council.
Cycleway (OpenData)

- Bus Shelter (OpenData)
Locations of bus shelters across Christchurch, provided by Christchurch City Council.
Bus Shelter (OpenData)

- DP Key Activity Centre (OpenData)
Geographic boundaries of key activity centres as defined in the District Plan, provided by Christchurch City Council.
DP Key Activity Centre (OpenData)


# Project Structure

- data/: Raw and processed datasets
- notebooks/: Jupyter notebooks for analysis
- scripts/: Python scripts for automation
- results/: Output maps and tables
- figures/: Key figures for reports and README
- README.md: Project overview and instructions

# License and Attribution
- The NZDep2023 index and associated data are licensed under the Creative Commons Attribution 4.0 International Licence (CC BY 4.0). You are free to copy, distribute, and adapt the material, provided that appropriate credit is given to the University of Otago and you comply with the terms of the licence.
- Attribution: University of Otago