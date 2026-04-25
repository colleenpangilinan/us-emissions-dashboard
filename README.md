# U.S. Emissions & Energy Mix Dashboard

An exploratory data project analyzing U.S. electricity generation trends and 
greenhouse gas emissions by sector, using real data from the EIA and EPA.

## Project Goals

- Visualize how the U.S. electricity mix has shifted across fossil fuels and 
  renewables over time
- Break down GHG emissions by sector to identify where reductions are happening
- Surface insights relevant to the clean energy transition through an 
  interactive Tableau Public dashboard

## Tools & Data Sources

- **Python** (Pandas, Requests) — data fetching and cleaning
- **EIA Open Data API** — U.S. electricity generation by source
- **EPA GHG Inventory** — state-level and sector-level emissions data
- **Tableau Public** — interactive dashboard and visualization

## Project Structure
us-emissions-dashboard/
├── data/
│   ├── raw/          # Original data pulled from EIA/EPA (do not edit)
│   └── processed/    # Cleaned, Tableau-ready CSVs
├── notebooks/
│   └── 01_fetch_data.ipynb
└── outputs/          # Exported charts and dashboard screenshots

## Status

In progress — data pipeline complete, dashboard in development.
