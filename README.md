# Cincinnati Traffic Safety Analysis

This project analyzes traffic crash data from the City of Cincinnati Open Data Portal to identify temporal and spatial trends in transportation safety.

## Project Overview

The goal is to demonstrate data cleaning, spatial analysis, and insight generation relevant to transportation planning.

## Methodology

- **Data Source**: [Traffic Crash Reports (CPD)](https://data.cincinnati-oh.gov/Safety/Traffic-Crash-Reports-CPD-/rvmt-pkmq)
- **Cleaning**: 
  - Filtered for recent data (2024-present).
  - Removed records with missing or invalid coordinates (verification of quality).
  - Standardized date formats.
- **Analysis**:
  - **Temporal**: Analyzed crash frequency by hour of day.
  - **Spatial**: Mapped crash locations to visualize high-density areas.

## Technical Details

- **Language**: Python
- **Libraries**: 
  - `pandas` for data manipulation and cleaning.
  - `geopandas` to handle spatial operations programmatically, similar to ArcGIS workflows.
  - `matplotlib` for visualization.

## Usage

1. Install requirements: `pip install -r requirements.txt`
2. Run the notebook: `jupyter notebook analysis.ipynb`