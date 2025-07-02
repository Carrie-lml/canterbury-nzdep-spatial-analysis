# canterbury-nzdep-spatial-analysis
Spatial analysis of deprivation in Canterbury using NZDep2018 and meshblock data

# Topic: Spatial Analysis of Deprivation and Public Transport Accessibility in Canterbury, New Zealand

This project explores the relationship between area-level deprivation (using NZDep2018 and meshblock data) and public transport accessibility in the Canterbury region. 

## Key Features 
Data Integration: Combines NZDep2018/IMD deprivation scores with meshblock boundaries and open public transport data (bus stops, routes) from Environment Canterbury.

Advanced Spatial Analysis: Calculates accessibility metrics (e.g., distance to nearest bus stop, number of stops/routes within walking distance) for each meshblock or SA1.

Predictive & Clustering Models: Uses spatial regression, geographically weighted regression (GWR), and spatial clustering (e.g., DBSCAN) to identify patterns and predictors of deprivation linked to transport access.

Policy Relevance: Highlights priority areas for transport intervention and supports evidence-based urban and social planning in Canterbury.

## Data Sources 
- NZDep2018/IMD: University of Otago & University of Auckland (NZDep2018, IMD)

- Meshblock Boundaries: Stats NZ, Canterbury Maps Open Data Portal

- Public Transport Data: Environment Canterbury Open Data

# Project Structure

- data/: Raw and processed datasets
- notebooks/: Jupyter notebooks for analysis
- scripts/: Python scripts for automation
- results/: Output maps and tables
- figures/: Key figures for reports and README
- README.md: Project overview and instructions
