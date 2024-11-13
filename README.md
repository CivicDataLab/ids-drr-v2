# IDS DRR

## Project Structure
```
.
├── README.md
├── requirements.txt
├── setup.py
└── states
    └── himachal_pradesh
        ├── data
        │   ├── processed
        │   │   ├── district_geojson
        │   │   └── worldpop_data
        │   └── raw
        └── src
            ├── api
            ├── data_processing
            ├── models
            ├── notebooks
            ├── scrapers
            ├── utils
            └── visualization
```

## Overview
IDS DRR V2 - more concise rewrite

## Data Structure
- `data/raw`: Raw  data
- `data/processed`: Contains processed data after transformation
  - `district_geojson`: Individual district boundary files
  - `worldpop_data`: Processed population data

## Source Code
- `api`: API endpoints and services
- `data_processing`: Data transformation scripts
- `models`: Analysis models
- `notebooks`: Jupyter notebooks for analysis
- `scrapers`: Data collection utilities
- `utils`: Helper functions
  - `geojson_processor.py`: GeoJSON manipulation tools
  - `worldpop_data_fetcher.py`: Population data retrieval
- `visualization`: Data visualization components

## Setup
1. Install dependencies: `pip install -r requirements.txt`
2. To fetch age sex pyramid and population data for Himachal Pradesh run
  `python3 path/to/worldpop_data_fetcher.py`


## License
[Add License Information]

## Contact
[Add Contact Information]

## Usage


## Contributing
[Add contribution guidelines]

## License
[Add license information]
