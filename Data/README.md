# Data Directory

This directory contains galaxy property datasets from the Portsmouth Group galaxy catalog. These datasets are used for analyzing and exploring galaxy characteristics in the analysis script.

## Dataset Files

### 1. Random-AGN-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Properties of a random sample of Active Galactic Nuclei (AGN) galaxies from the Portsmouth Group catalog
- **Size**: ~114 KB
- **Galaxy Type**: AGN (Active Galactic Nuclei)
- **Number of Entries**: Sample of galaxies with active nuclei

### 2. Random-SF-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Properties of a random sample of Star-Forming (SF) galaxies from the Portsmouth Group catalog
- **Size**: ~123 KB
- **Galaxy Type**: SF (Star-Forming)
- **Number of Entries**: Sample of actively star-forming galaxies

### 3. Random-SB-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Properties of a random sample of Starburst (SB) galaxies from the Portsmouth Group catalog
- **Size**: ~120 KB
- **Galaxy Type**: SB (Starburst)
- **Number of Entries**: Sample of starburst galaxies

## Data Format

All files are in CSV (Comma-Separated Values) format and contain galaxy property measurements. Each row represents an individual galaxy object with various physical properties and measurements as columns.

## Usage

These datasets are designed to be read and analyzed using the Python analysis scripts in this repository. The scripts explore and compare properties across different galaxy types.

### Example Loading in Python
```python
import pandas as pd

# Load AGN galaxy data
agn_data = pd.read_csv('Data/Random-AGN-Galaxies-PortsmouthGroup_properties.csv')

# Load star-forming galaxy data
sf_data = pd.read_csv('Data/Random-SF-Galaxies-PortsmouthGroup_properties.csv')

# Load starburst galaxy data
sb_data = pd.read_csv('Data/Random-SB-Galaxies-PortsmouthGroup_properties.csv')
```

## Data Source

These datasets are derived from the Portsmouth Group galaxy catalog, a compilation of galaxy properties from spectroscopic surveys and multi-wavelength observations.

## Notes

- Each dataset contains a random sample of galaxies of its respective type
- The datasets can be used independently or combined for comparative analysis
- For detailed information about specific columns and their meanings, refer to the analysis scripts and any documentation provided in the main repository
